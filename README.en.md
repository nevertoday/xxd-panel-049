<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 049 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 049

### Carve the photograph's most affecting memory into a fresh limited-colour print

[简体中文](README.md) · **English** · [日本語](README.ja.md) · [한국어](README.ko.md) · [العربية](README.ar.md)

</div>

> LIMITED-COLOUR WOODCUT · HAND-CARVED MARKS · MATTE INK · WARM PAPER · BROKEN EDGES

XXD Panel 049 actively removes complex background and trivia, rebuilding only the contours, proportions, directions, tonal masses, key structures, and relations that carry recognition and emotion as one woodcut or linocut impression hovering on warm paper.

## Aesthetic motive

```text
lock identity, silhouette, direction, and emotional relation → preserve three cues → remove incidental background → reduce into carveable contour, ink masses, and negative space → hand-print a small fresh matte palette → let missing ink, breaks, paper show-through, misregistration, and worn edges dissolve according to form → keep abundant warm paper → let copy grow from contour and print edge
```

- Carved marks may hesitate, vary in width, fray, break, notch, misregister, or lose ink, but every imperfection follows form.
- Use one anchor, abundant warm paper, and naturally incomplete edges rather than reconstructing the whole background.
- Derive a small high-lightness, low-to-medium-saturation ink palette from the source; never impose a fixed palette.
- Reject one-click filters, polished vectors, cartoon outlines, complete frames, uniform grunge, and travel-poster templates.

Full specifications: [Skill](SKILL.md) · [source brief](references/049-source.md) · [English production prompt](references/xxd-panel-049-prompt.en.md) · [Chinese production prompt](references/xxd-panel-049-prompt.zh-CN.md)

## Samples

Samples are still in production. This repository does not borrow another Panel's artwork or create fake placeholders. Future samples demonstrate only the 049 aesthetic motive and never become fixed subjects, palettes, compositions, copy, or canvas sizes. [Sample policy](assets/examples/README.md)

## Four combinable modes

| Mode | Unspecified size | Result |
| --- | --- | --- |
| `top-bottom` | source-adaptive `W×2H` | full source above + equal design below, exact 50/50 |
| `left-right` | source-adaptive `2W×H` | full source left + equal design right, exact 50/50 |
| `design-only` | source-adaptive `W×H` | transformed design only |
| `wallpaper-pack` | labelled per device | separate phone, iPad, desktop, and watch PNGs |

Choose one or several; all modes create seven PNGs per source. Wallpaper packs may be linked or independent. A linked set references the original plus one approved anchor and never crops or chains derivatives.

## Copy, locale, and output

Before generation, resolve automatic copy, exact custom copy, or text-free output, and independently confirm target language or locale. Automatic copy uses a 1–3-word title drawn from identity, action, mood, state, place, or metaphor, integrating type with contour, negative space, and broken print edge. Exact user copy remains verbatim. Ordinary sizes adapt to the source; all deliverables are PNGs in a fresh `~/Desktop/xxd/xxd-panel-049/<fresh-task>/` directory.

## Install

```bash
git clone https://github.com/nevertoday/xxd-panel-049.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-049" ~/.codex/skills/xxd-panel-049
```

Claude Code users may link the folder under `~/.claude/skills/xxd-panel-049`. Restart the agent session and invoke `$xxd-panel-049`.

## About and support

XXD abbreviates Xiaoxiaodong's brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01). In-depth consultation is CNY 299/hour. The Skills User Community is a CNY 99 one-time fee. Knowledge Planet + Member Prompt Library is one CNY 699/year payment for both benefits: after joining [Knowledge Planet](https://wx.zsxq.com/group/15554814142882), contact Xiaoxiaodong on WeChat for a [Member Prompt Library](https://vip.xiaoxiaodong.ai/) redemption code; after self-service activation in the prompt library, contact Xiaoxiaodong on WeChat for an invitation to Knowledge Planet. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center">

## ☕ Support this open-source project

Support is optional and never changes open-source access.

<a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a>

</div>
