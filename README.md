<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 049 项目横幅" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 049

### 把照片最动人的记忆，刻成一枚清新的限色版画

**简体中文** · [English](README.en.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [العربية](README.ar.md)

</div>

> 限色木刻 · 手工刀痕 · 哑光套印 · 温暖纸面 · 不完整边缘

XXD Panel 049 主动删去复杂背景与细碎信息，把照片中真正承载识别度与情绪的轮廓、比例、方向、明暗块、关键结构和关系，重构为悬浮在温暖纸面上的木刻或油毡版画印记。

## 审美动机

```text
锁定身份、剪影、方向和情绪关系 → 保留三个线索 → 删除无关背景 → 压缩为可刻轮廓、色块与负形 → 用少量清新哑光油墨手工套印 → 让缺墨、断裂、露纸、错位与磨损边缘按结构消散 → 保留大面积暖纸留白 → 让文案沿轮廓与版画边缘生长
```

- 刀痕允许迟疑、粗细不均、发毛、断裂、缺口、错位和漏印，但必须顺应主体结构。
- 一个视觉锚点、大面积暖纸与自然消失的不完整边缘；不复制完整背景。
- 从源图提炼少量高明度、低至中饱和的清新油墨层，不套固定配色。
- 拒绝一键滤镜、光滑矢量、卡通描边、完整矩形边框、均匀做旧和旅游模板。

完整规则：[Skill 工作流](SKILL.md) · [原始提示词](references/049-source.md) · [中文运行适配器](references/xxd-panel-049-prompt.zh-CN.md) · [英文运行适配器](references/xxd-panel-049-prompt.en.md)

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091453089954070791) · 2026 年 8 月 23 日<br>
> GPT2 × 版画 × 治愈系 × 美学提示词 × VOL.049

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 049 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 049 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 049 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 049 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791">查看原推文与完整提示词 →</a></p>

这些样张用于展示 049 的美学动机，不会把样张中的主体、构图、配色、文案或旧画幅变成生成参考或当前默认值。

## 原始提示词优先，而不是二次导演

`references/049-source.md` 是本项目唯一的创作与审美权威。Skill 不再额外总结或扩写它，也不会统一规划颜色、色板、美学动机、标题或微文案。原始提示词要求怎样处理颜色、材料、构图、留白与文字，GPT Image 2 就按那套逻辑执行。

模式与尺寸会完整替换原始提示词旧有的 3:4 上下交付容器，但不改写它的转译美学。每张成品只向 GPT Image 2 发送一个已选模式的最终契约，不再把四种模式放进同一个通用模板让模型自行猜测。

## 四种可组合输出模式

模式可以单选或多选：`top-bottom`、`left-right`、`design-only`、`wallpaper-pack`；多选时，每个模式分别生成、分别拥有自己的提示词。

- `top-bottom`：整张画面由上方现实画面与下方设计转译两个主要部分组成。
- `left-right`：整张画面从顶部到底部保持完整左右结构，原图在左、设计在右；文字融入这两个区域，不再生成横跨全宽的第三块底栏。左右宽度可以不对称，由模型自主构图。
- `design-only`：原图只作为不可见的身份、结构、颜色与事实依据；整张成品的每个可见元素都必须属于该 Skill 自己的设计转译语言。
- `wallpaper-pack`：每台设备分别生成完整画布的设计转译壁纸，原图不作为照片区域出现。

上下或左右都不做分界线、中线百分比或像素坐标检测。只有用户明确要求像素级分区或原片逐像素不变时，才使用确定性拼合。

普通成品尺寸同样可以多选：自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5，或自定义比例／准确像素。没有静默默认尺寸；每个不同比例都会基于同一份原始提示词独立重构。

壁纸套装可选“连贯”或“四张独立”。连贯模式先生成一张定调图，其余设备同时参考原图与定调图重新构图；不会把一张图机械裁成四种尺寸。

## 文字方式

正式生图前只确认三种选择：

1. **模型根据原始提示词生成文字**：用户只指定语言或地区，文字内容、数量、气质与排版由 GPT Image 2 按原始提示词生成；所有文字都从当前图片的内容、气质或隐喻中自然生长，任何事实或资料式信息都必须有用户输入、图片可见内容或已核实信息作为依据。
2. **使用我的准确文字**：逐字传给图像模型，不改写、不翻译、不补标题；排版仍遵循原始提示词。
3. **不要文字**：严格禁止文字与伪文字。

外层 Skill 不再预编标题、微文案或文案包。文字语言与操作语言分开确认，不根据人物、场景或文件名猜测国家与受众。

## 能力自适应问询与快捷参数

同一个 Skill 会根据宿主真正提供的交互能力选择界面，不会把文本符号伪装成可点击控件：

- **Claude Code 提供 `AskUserQuestion + multiSelect: true` 时**：模式和尺寸使用真正的 checkbox；文字方式与壁纸关系使用单选。常用尺寸会按方形、竖版、横版分组展示，并累计多组选项；自定义尺寸进入自由输入。
- **Codex 只提供 `request_user_input` 时**：它只用于文字方式、壁纸关系等互斥单选，不拿来伪装模式或尺寸多选。模式与尺寸改用清楚的组合输入。
- **没有交互工具时**：使用两轮文字问询。第一轮选择一个或多个模式；第二轮填写尺寸与文字方式。Skill 不显示假的 `- [ ]`，也不会为了获得表单要求用户切换 Plan mode。

默认第二轮只展示“智能推荐／跟随原图／常用比例／自定义”四个入口；只有选择常用比例时，才展开完整比例库：方形 `1:1`，竖版 `3:4、4:5、2:3、9:16、5:7`，横版 `4:3、5:4、3:2、16:9、21:9、7:5`。所有比例都可组合，也可直接输入准确像素。

全部设置都可以直接作为参数传入：

```text
/xxd-panel-049 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

支持 `--mode`、可重复或逗号分隔的 `--size`、`--text prompt|exact|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询；参数不完整时只询问缺失项。

## 生图模型优先级

GPT Image 2 是默认首选，并继续执行本项目现有的高保真垫图、生成前确认整张画幅、双联一次生成完整画布、脚本仅作条件式兜底等逻辑。

当当前工具或已配置兼容通道确实可用，并能满足原图保真、整张成品比例、目标语言文字和连贯壁纸多图参考等要求时，也支持 Seedance 5.0 Pro、Nano Banana Pro（Gemini Image Pro）、Nano Banana 2（Gemini Image Flash）或其他兼容位图模型。备用模型只替换生成通道，不得改变模式、画幅、文案、语言、壁纸关系和完整画布优先策略。

如果没有合适的生图通道，Skill 会请用户启用生图工具或提供 API Key。用户主动提供的凭据可以用于当前任务，但不得在回复或日志中回显、展示或泄露；未经用户明确要求，不会长期保存凭据或修改供应商、账户、计费及全局路由配置。

## 安装

```bash
git clone https://github.com/nevertoday/xxd-panel-049.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-049" ~/.codex/skills/xxd-panel-049
```

Claude Code 用户可链接到 `~/.claude/skills/xxd-panel-049`。安装后重启 Agent 会话，并使用 `$xxd-panel-049`。

## 关于 XXD 与支持

XXD 是小小东品牌名的缩写。创建与维护者：[@xiaoxiaodong01](https://x.com/xiaoxiaodong01)。深度咨询 299 元／小时；Skills 用户交流群 99 元，一次付费入群；知识星球＋成员提示词库 699 元／年，一次年费同时开通两项权益。若从[知识星球](https://wx.zsxq.com/group/15554814142882)开通，请微信联系小小东领取[成员提示词库](https://vip.xiaoxiaodong.ai/)兑换码；若在成员提示词库自助开通，请微信联系小小东邀请进入知识星球。[微信](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center">

## ☕ 支持这个开源项目

算力赞助完全自愿，不改变开源项目的访问权限。

<table><tr><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="XXD 微信赞赏" width="180"></a><br><strong>WeChat</strong></td><td align="center"><a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="XXD 支付宝赞赏" width="180"></a><br><strong>Alipay</strong></td></tr></table>

</div>
