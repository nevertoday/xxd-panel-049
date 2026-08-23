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

## 样张

样张仍在制作中，当前不会借用其他 Panel 的图片或生成占位图。未来加入的样张只展示 049 的审美动机，不会成为固定主体、配色、构图、文案或画幅。[样张说明](assets/examples/README.md)

## 四种可组合模式

| 模式 | 未指定尺寸 | 成果物 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 `W×2H` | 完整原图在上＋同尺寸设计图在下，严格 50/50 |
| `left-right` | 源图自适应 `2W×H` | 完整原图在左＋同尺寸设计图在右，严格 50/50 |
| `design-only` | 源图自适应 `W×H` | 只显示变化设计 |
| `wallpaper-pack` | 设备分别指定 | 手机、iPad、电脑、儿童手表四张 PNG |

可选择一个或多个模式；选择全部时每张源图输出 7 张 PNG。壁纸可选“连贯”或“独立”：连贯套装共同参考原图与同一批准定调图，绝不裁切或串联衍生图。

## 文案、语言与输出

生成前确认自动文案、准确自定义文案或无文字，并单独确认目标语言／地区。自动文案从身份、动作、情绪、状态、地点或隐喻中提炼 1–3 词标题，让排版与轮廓、负形和断裂边缘互相承托；用户准确文案逐字保留。普通模式按源图自适应，全部结果为 PNG，并写入新的 `~/Desktop/xxd/xxd-panel-049/<fresh-task>/` 任务目录。

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
