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

完整规则：[Skill 工作流](SKILL.md) · [原始提示词](references/049-source.md) · [中文生产提示词](references/xxd-panel-049-prompt.zh-CN.md) · [英文生产提示词](references/xxd-panel-049-prompt.en.md)

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

## 四种可组合输出模式

可用 `1`、`1+3`、`1、2、4` 或 `全部` 选择一个或多个模式；`全部` 每张源图输出 7 个独立 PNG。模式确定后，Skill 会在生图前继续询问整张最终成品的画幅：`3:4` 原提示词画幅、明确跟随原图、常用比例，或自定义比例／准确像素。不会再静默套用源图尺寸。

| 模式 | 画幅逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在上，049 设计在下，约 50/50 |
| `left-right` | 用户确认的整张成品画幅 | 一次生成完整画布：高保真原图在左，049 设计在右，约 50/50 |
| `design-only` | 用户确认的整张成品画幅 | 049 设计铺满画布，不显示原照片 |
| `wallpaper-pack` | 逐设备确认 | 手机、iPad、电脑、儿童手表四张独立 PNG |

双联默认把原图作为高保真垫图／编辑参考，用一套完整提示词直接生成一张整体成品，让摄影、设计、色彩、光线、文字与含义自然呼应。只有完整画布针对性重试仍失败、用户要求原片逐像素不变、当前通道无法实现目标画幅，或需要无创像素校准时，才启用确定性拼合兜底。

壁纸可选连贯或独立。连贯套装先批准一张 iPad 定调图，另外三张分别参考原图＋同一定调图重新构图；独立套装的四张都只参考原图。两者都不会裁切其他设备成品或串联衍生图。

## 文案、语言与输出

生成前确认自动文案、准确自定义文案或无文字，并单独确认目标语言／地区。自动文案从身份、动作、情绪、状态、地点或隐喻中提炼 1–3 词标题，让排版与轮廓、负形和断裂边缘互相承托；用户准确文案逐字保留。普通模式在生成前明确最终画幅，全部结果为 PNG，并写入新的 `~/Desktop/xxd/xxd-panel-049/<fresh-task>/` 任务目录。

## 勾选式选择与快捷参数

当运行环境提供真正的交互控件时，Skill 会优先使用卡片式选择：成品模式和普通成品尺寸均可多选，文字方式与壁纸关系为单选。尺寸提供自动适配、跟随原图、1:1、3:4、4:3、4:5、5:4、2:3、3:2、9:16、16:9、21:9、5:7、7:5 和自定义比例／像素。没有交互控件时，会自动改用清楚的多行编号菜单，不显示无法点击的假复选框。

所有设置也可以作为变量直接跟在调用指令后：

```text
/xxd-panel-049 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

可使用 `--mode`、可重复或逗号分隔的 `--size`、`--text auto|custom|none`、`--locale`、`--copy`、`--wallpaper linked|independent`、`--wallpaper-size` 和 `--out`。参数齐全时跳过全部问询并直接生成；参数不完整时只补问缺失项。不同比例会分别重新构图，四端壁纸仍是独立设备分支，不与普通尺寸机械相乘。

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
