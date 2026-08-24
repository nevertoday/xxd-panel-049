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

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091453089954070791) · 23 August 2026<br>
> GPT2 × printmaking × healing mood × aesthetic prompt × VOL.049

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 049 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 049 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 049 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 049 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091453089954070791">View the original post and full prompt →</a></p>

These samples demonstrate the 049 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 049 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 049 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 049 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy, locale, and output

Before generation, resolve automatic copy, exact custom copy, or text-free output, and independently confirm target language or locale. Automatic copy uses a 1–3-word title drawn from identity, action, mood, state, place, or metaphor, integrating type with contour, negative space, and broken print edge. Exact user copy remains verbatim. Ordinary sizes adapt to the source; all deliverables are PNGs in a fresh `~/Desktop/xxd/xxd-panel-049/<fresh-task>/` directory.

## Selectable controls and inline parameters

When the host provides genuine interactive controls, the Skill prefers card-style selection: output modes and ordinary output sizes are multi-select, while copy mode and wallpaper relationship are single-select. Size choices include auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, and custom ratios or pixels. Without an interactive control, it falls back to a clear multiline numbered menu rather than showing fake checkboxes.

Every setting can also be supplied as an inline variable:

```text
/xxd-panel-049 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text auto --locale ja-JP
```

Supported parameters include `--mode`, repeatable or comma-separated `--size`, `--text auto|custom|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip all preflight questions; partial parameters trigger only the missing questions. Different aspect ratios are independently recomposed, and the four-device wallpaper pack remains a separate branch rather than being multiplied by ordinary sizes.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

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
