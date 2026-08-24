<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 049 프로젝트 배너" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 049

### 사진의 가장 인상적인 기억을 맑은 제한색 판화로 새기기

[简体中文](README.md) · [English](README.en.md) · [日本語](README.ja.md) · **한국어** · [العربية](README.ar.md)

</div>

> 제한색 목판 · 손으로 새긴 흔적 · 무광 겹인쇄 · 따뜻한 종이 · 불완전한 가장자리

XXD Panel 049는 복잡한 배경과 자잘한 정보를 적극적으로 덜어내고, 인식과 감정을 지탱하는 윤곽, 비례, 방향, 명암 덩어리, 핵심 구조, 관계만을 따뜻한 종이 위에 떠 있는 목판화 또는 리노컷 자국으로 재구성합니다.

## 미학적 동기

정체성, 실루엣, 방향, 감정 관계를 고정하고 원본 고유 단서를 세 개 이상 보존합니다. 배경을 지우고 새길 수 있는 윤곽, 색면, 여백으로 환원한 뒤 소수의 밝은 무광 잉크로 인쇄합니다. 잉크 빠짐, 끊김, 종이 노출, 판 어긋남, 닳은 가장자리는 형태를 따라야 하며 균일한 낡음 오버레이가 아니어야 합니다. 매끈한 벡터, 만화 윤곽, 완전한 사각형, 어둡고 무거운 빈티지, 여행 포스터 템플릿을 거부합니다.

전체 사양: [Skill](SKILL.md) · [원문](references/049-source.md) · [영문 생성 프롬프트](references/xxd-panel-049-prompt.en.md) · [중문 생성 프롬프트](references/xxd-panel-049-prompt.zh-CN.md)

## 예시 · X에서

> [샤오샤오둥（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091453089954070791) · 2026년 8월 23일<br>
> GPT2 × 판화 × 치유 감성 × 미학 프롬프트 × VOL.049

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 049 예시 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 049 예시 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 049 예시 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 049 예시 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791">원문 게시물과 전체 프롬프트 보기 →</a></p>

이 예시는 049의 미학적 의도를 보여 줄 뿐이며, 예시의 주제, 구성, 색상, 문구, 이전 캔버스 비율은 생성 참고나 현재 기본값이 되지 않습니다.

## 조합 가능한 네 가지 출력

`1`, `1+3`, `1,2,4`, `전체`로 하나 또는 여러 모드를 선택할 수 있으며 `전체`는 원본당 독립 PNG 7개를 만듭니다. 모드 선택 뒤, 생성 전에 완성 이미지 전체의 화면비를 반드시 확인합니다: 원래 프롬프트의 `3:4`, 명시적인 원본 비율, 일반 비율, 사용자 지정 비율／정확한 픽셀입니다. 원본 크기를 묵시적으로 적용하지 않습니다.

| 모드 | 화면비 규칙 | 결과물 |
| --- | --- | --- |
| `top-bottom` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 위에 고충실도 원본, 아래에 049 디자인, 약 50/50 |
| `left-right` | 사용자가 확인한 전체 캔버스 | 완성 캔버스를 한 번에 생성: 왼쪽에 고충실도 원본, 오른쪽에 049 디자인, 약 50/50 |
| `design-only` | 사용자가 확인한 전체 캔버스 | 049 디자인이 전체를 채우며 원본 사진은 보이지 않음 |
| `wallpaper-pack` | 기기별 확인 | 휴대전화, iPad, 데스크톱, 어린이용 스마트워치 PNG 개별 출력 |

이중 패널 모드는 원본을 고충실도 편집／참조 입력으로 사용하고 완전한 스타일 프롬프트 한 세트로 최종 화면을 직접 생성합니다. 사진, 디자인, 색, 빛, 타이포그래피와 의미가 하나로 이어지게 하기 위해서입니다. 결정적 합성은 전체 캔버스 재시도 후에도 실패한 경우, 원본의 픽셀 완전 보존을 명시한 경우, 현재 경로가 목표 화면비를 만들 수 없는 경우, 또는 무손실 최종 픽셀 조정이 필요한 경우에만 사용합니다.

배경화면은 연결형 또는 독립형입니다. 연결형은 iPad 기준 작품 하나를 승인한 뒤 다른 기기를 원본＋같은 기준 작품에서 각각 재구성합니다. 독립형은 각 기기가 원본만 참조합니다. 어느 쪽도 다른 기기 결과를 자르거나 파생 결과를 연쇄 참조하지 않습니다.

## 이미지 모델 우선순위

GPT Image 2를 기본 최우선 모델로 사용합니다. 고충실도 원본 참조, 생성 전 완성 캔버스 확인, 이중 패널의 완성 화면 일괄 생성, 조건이 충족될 때만 사용하는 스크립트 합성이라는 기존 흐름은 그대로 유지합니다.

현재 도구 또는 설정된 경로에서 실제로 사용할 수 있고 원본 충실도, 완성 화면비, 대상 언어의 문자, 연결형 배경화면의 다중 참조 요구를 충족할 때는 Seedance 5.0 Pro, Nano Banana Pro(Gemini Image Pro), Nano Banana 2(Gemini Image Flash) 또는 다른 호환 비트맵 모델도 사용할 수 있습니다. 대체 모델은 생성 경로만 바꾸며 모드, 캔버스, 문구, 언어, 배경화면 관계와 완성 캔버스 우선 전략을 바꾸지 않습니다.

적합한 경로가 없으면 이미지 생성 도구를 활성화하거나 API Key를 제공하도록 사용자에게 요청합니다. 사용자가 제공한 인증 정보는 현재 작업에 사용할 수 있지만 답변이나 로그에 다시 표시·기록·노출하지 않습니다. 사용자가 명시적으로 요청하지 않는 한 장기 저장하거나 제공자, 계정, 결제 또는 전역 경로 설정을 변경하지 않습니다.

## 설치와 제작자

```bash
git clone https://github.com/nevertoday/xxd-panel-049.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-049" ~/.codex/skills/xxd-panel-049
```

XXD는 Xiaoxiaodong 브랜드 이름의 약자입니다. 제작: [@xiaoxiaodong01](https://x.com/xiaoxiaodong01). 심층 상담은 CNY 299/시간이며 Skills 사용자 교류 그룹은 CNY 99 일회 결제입니다. Knowledge Planet＋회원 프롬프트 라이브러리는 연 CNY 699 한 번의 결제로 두 혜택을 모두 엽니다. [Knowledge Planet](https://wx.zsxq.com/group/15554814142882)에서 가입한 뒤 WeChat으로 Xiaoxiaodong에게 연락해 [회원 프롬프트 라이브러리](https://vip.xiaoxiaodong.ai/) 교환 코드를 받으세요. 프롬프트 라이브러리에서 셀프서비스로 개통한 뒤에는 WeChat으로 연락해 Knowledge Planet 초대를 받으세요. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
