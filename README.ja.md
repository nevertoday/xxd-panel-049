<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 049 プロジェクトバナー" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 049

### 写真の心に残る記憶を、爽やかな限定色の版画に刻む

[简体中文](README.md) · [English](README.en.md) · **日本語** · [한국어](README.ko.md) · [العربية](README.ar.md)

</div>

> 限定色木版 · 手彫りの跡 · マットな重ね刷り · 暖かな紙 · 不完全な縁

XXD Panel 049 は複雑な背景と細部を積極的に削り、認識と感情を支える輪郭、比率、方向、明暗の塊、主要構造、関係だけを、暖かな紙に浮かぶ木版・リノカットの印影へ再構築します。

## 美的動機

身元、シルエット、方向、感情的関係を固定し、元写真固有の手掛かりを三つ以上保ちます。背景を省き、彫れる輪郭、色面、ネガティブスペースへ還元し、少数の明るいマットインクで刷ります。かすれ、断裂、紙の露出、版ずれ、摩耗した縁は形に沿って現れ、均一な汚し加工にはしません。滑らかなベクター、漫画的輪郭、完全な矩形、暗く重い古色、旅行ポスターテンプレートを拒否します。

完全な仕様：[Skill](SKILL.md) · [原文](references/049-source.md) · [英語生成プロンプト](references/xxd-panel-049-prompt.en.md) · [中国語生成プロンプト](references/xxd-panel-049-prompt.zh-CN.md)

## 作例 · X より

> [小小東（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091453089954070791) · 2026年8月23日<br>
> GPT2 × 版画 × 癒やし × 美学プロンプト × VOL.049

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 049 作例 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 049 作例 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 049 作例 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 049 作例 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791">元の投稿と完全なプロンプトを見る →</a></p>

これらの作例は 049 の美的意図を示すものであり、作例の被写体、構図、配色、コピー、旧キャンバス比率が生成時の参照や現在の既定値になることはありません。

## 組み合わせ可能な4つの出力

`1`、`1+3`、`1,2,4`、`全部` で一つまたは複数を選べます。`全部` は元画像ごとに7点の独立PNGを出力します。モード選択後、生成前に完成画像全体の画角を必ず確認します：元プロンプトの `3:4`、明示的な元画像比率、一般的な比率、またはカスタム比率／正確なピクセルです。元画像寸法を暗黙には適用しません。

| モード | 画角ルール | 成果物 |
| --- | --- | --- |
| `top-bottom` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：上に高忠実度の元画像、下に 049 デザイン、約50/50 |
| `left-right` | ユーザー確認済みの完成画角 | 完成キャンバスを一度に生成：左に高忠実度の元画像、右に 049 デザイン、約50/50 |
| `design-only` | ユーザー確認済みの完成画角 | 049 デザインが全画面を満たし、元画像は表示しない |
| `wallpaper-pack` | 端末ごとに確認 | スマートフォン、iPad、デスクトップ、子ども用ウォッチの個別PNG |

二連モードは元画像を高忠実度の編集／参照入力として使い、完全なスタイルプロンプト一式で完成画面を直接生成します。写真、デザイン、色、光、文字、意味を一体化するためです。決定論的な合成は、完成画面の再試行後も失敗した場合、原画像のピクセル完全保持を明示された場合、生成経路が指定画角に対応しない場合、または無劣化の最終ピクセル調整が必要な場合だけ使います。

壁紙は連動または独立を選べます。連動はiPad基準作を一つ承認し、他の端末を元画像＋同じ基準作から個別に再構成します。独立は各端末が元画像だけを参照します。どちらも他端末の成果を切り抜かず、派生を連鎖しません。

## インストールと作者

```bash
git clone https://github.com/nevertoday/xxd-panel-049.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-049" ~/.codex/skills/xxd-panel-049
```

XXD は Xiaoxiaodong のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は CNY 299／時間、Skills ユーザー交流グループは一回払い CNY 99 です。Knowledge Planet＋会員プロンプトライブラリは年額 CNY 699 の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は、WeChat で Xiaoxiaodong に連絡して[会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取ってください。プロンプトライブラリで自動開通した場合は、WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
