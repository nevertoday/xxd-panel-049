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

完全な仕様：[Skill](SKILL.md) · [原文](references/049-source.md) · [英語ランタイムアダプター](references/xxd-panel-049-prompt.en.md) · [中国語ランタイムアダプター](references/xxd-panel-049-prompt.zh-CN.md)

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

## 原文プロンプトを唯一の美的基準にする

`references/049-source.md` が、このプロジェクト唯一の創作・美的基準です。Skill は原文を要約・拡張せず、共通の配色計画、美的動機、タイトル、マイクロコピーを追加しません。色、素材、構図、余白、言葉、タイポグラフィは、GPT Image 2 が原文プロンプトの規則どおりに実行します。

モードとサイズが上書きするのは、旧来の 3:4 上下構成だけです。左右モードは元画像とデザイン変換の左右関係を示しますが、二つの等分領域やトリミング枠を固定しません。デザイン単体と壁紙では下半分のデザイン言語をキャンバス全体へ広げます。それ以外の原文指示はすべて維持されます。

## 組み合わせ可能な4つの出力

`top-bottom`、`left-right`、`design-only`、`wallpaper-pack` は単独でも複数でも選べます。ペア構成では元画像、原文プロンプト、視覚関係、最終キャンバスを一度に画像モデルへ渡し、一枚の完成画面として構成させます。決定論的な合成は、ユーザーがピクセル単位の分割または元写真の完全保持を明示した場合だけ使います。

上下／左右は視覚的な関係であり、固定された等分容器ではありません。領域比率、スケール、余白、重なり、トリミングや背景拡張は、画像モデルが元画像と最終キャンバスから判断し、境界線、中央比率、ピクセル座標は測定しません。

通常サイズも複数選択できます：自動適応、元画像比率、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5、カスタム比率／正確なピクセル。暗黙の既定サイズはありません。異なる比率は、同じ原文プロンプトから個別に再構成します。

壁紙セットは連動型または独立型。連動型は最初の一枚を基準画像とし、残りを元写真＋基準画像から各端末向けに再構成します。一枚を四サイズへ機械的に切り抜くことはありません。

## 文字モード

生成前に次の一つを選びます。

1. **原文プロンプトに従ってモデルが文字を生成**：ユーザーは言語・地域だけを指定し、内容、量、調子、組版は GPT Image 2 が原文どおりに生成します。表示される言葉はすべて、現在の画像の内容、空気感、または暗示から自然に生まれるものにします。
2. **自分の正確な文言を使う**：一字一句そのまま渡し、書き換え・翻訳・タイトル追加をしません。組版は原文に従います。
3. **文字なし**：文字と疑似文字を厳格に禁止します。

外側の Skill はタイトルやマイクロコピーを先に書きません。出力言語は操作言語と別に確認し、人物、風景、ファイル名から推測しません。

## 宿主能力に適応する質問とインライン引数

同じ Skill が、宿主に実在する対話機能へ適応します。装飾記号をクリック可能な UI のようには見せません。

- **Claude Code に `AskUserQuestion + multiSelect: true` がある場合**：モードとサイズは本物のチェックボックス、文字方式と壁紙関係は単一選択。一般サイズは正方形・縦・横のグループに分け、選択を累積し、カスタム値は自由入力します。
- **Codex に `request_user_input` しかない場合**：文字方式や壁紙関係など、相互排他的な項目だけに使います。モードやサイズを単一選択に見せかけず、組み合わせ入力で受け取ります。
- **対話ツールがない場合**：1回目にモード、2回目にサイズ＋文字方式を入力します。偽の `- [ ]` は表示せず、フォームのためだけに Plan mode への切り替えも求めません。

2回目は最初に「自動推薦／元画像比率／一般比率／カスタム」だけを表示します。一般比率を選んだときだけ、正方形 `1:1`、縦 `3:4、4:5、2:3、9:16、5:7`、横 `4:3、5:4、3:2、16:9、21:9、7:5` を展開します。複数比率と正確なピクセルを指定できます。

すべての設定はインラインでも指定できます。

```text
/xxd-panel-049 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

`--mode`、複数指定可能な `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size`、`--out` に対応します。必要な値が揃っていれば質問を省略し、不足分だけを尋ねます。

## 画像モデルの優先順位

GPT Image 2 を既定の第一候補とします。高忠実度の参照画像、生成前の完成キャンバス確認、二連モードの完成画面一括生成、条件を満たした場合だけのスクリプト合成という既存の流れは変わりません。

現在のツールまたは設定済み経路から実際に利用でき、元画像の忠実度、完成画角、対象言語の文字、連動壁紙の複数参照を満たせる場合は、Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）、その他の互換ビットマップモデルも利用できます。代替モデルが変更できるのは生成経路だけで、モード、画角、文案、言語、壁紙関係、完成キャンバス優先の方針は変更できません。

適切な経路がない場合は、画像生成ツールを有効にするか API Key を提供するようユーザーに案内します。ユーザーが提供した認証情報は現在のタスクで利用できますが、返信やログに再表示・記録・開示しません。明示的な依頼がない限り、長期保存やプロバイダー、アカウント、課金、グローバル経路の設定変更も行いません。

## インストールと作者

```bash
git clone https://github.com/nevertoday/xxd-panel-049.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-049" ~/.codex/skills/xxd-panel-049
```

XXD は Xiaoxiaodong のブランド名の略称です。作者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。個別相談は CNY 299／時間、Skills ユーザー交流グループは一回払い CNY 99 です。Knowledge Planet＋会員プロンプトライブラリは年額 CNY 699 の一回の支払いで両方を利用できます。[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) から加入した場合は、WeChat で Xiaoxiaodong に連絡して[会員プロンプトライブラリ](https://vip.xiaoxiaodong.ai/)の引換コードを受け取ってください。プロンプトライブラリで自動開通した場合は、WeChat で連絡して Knowledge Planet への招待を受けてください。[WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>
