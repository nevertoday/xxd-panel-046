<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 046 project banner" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 046

### Rebuild a photograph as a bright, vivid, tactile impasto micro-landscape

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#four-outputs-one-impasto-logic)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#boundaries-and-trust)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> BRIGHT GROUND · VIVID IMPASTO · MINIATURE VOLUME · DIAGONAL FIELD · WARM LIGHT

XXD Panel 046 is an image-generation Skill for Codex and compatible agents. It preserves a recognisable subject from the photograph, then rebuilds it as an oil-painted miniature with palpable paint depth, palette-knife marks, and a convincing small-scale presence.

A single diagonal field, derived from the source, supports the subject. Warm-white textured paper remains open around it; colour is luminous, clear, and alive, while type behaves like a refined annotation in an art publication rather than a headline pasted on afterwards.

## Why it exists

“Impasto style” easily collapses into one of two templates: a murky oil-paint filter over the whole photograph, or a plastic-looking subject placed on an arbitrary brushstroke.

046 reverses that logic:

```text
lock subject identity → derive one diagonal support field → concentrate genuine impasto → brighten source colour → preserve warm-white breathing room → add refined editorial type
```

If an unrelated photograph could replace the source without materially changing the miniature subject, diagonal field, palette, light, or copy, the result is not 046.

## The 046 visual contract

- **Recognisable miniature subject:** retain at least three source-specific identity cues; improve angle and detail without replacing the subject.
- **One diagonal support field:** it may become water, ground, a path, a band of light, or a landscape slice, but it must derive from the source and genuinely carry the subject.
- **Real impasto material:** accumulated paint, knife marks, raised edges, paper grain, and thick-thin contrast must coexist.
- **Bright source-derived colour:** lift the clearest colours in the photograph in value and purity without imposing a fixed candy palette.
- **Large warm-white breathing room:** paper, light, and miniature scale remain visible rather than filling the entire canvas.
- **Clear, warm illumination:** sunny, buoyant, and alive—never a brown oil filter, neon glow, or commercial studio setup.
- **Art-publication typography:** delicate, restrained letterforms with a faint absorbed-ink character follow the diagonal axis, subject edge, or a quiet margin.

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091337011403882991) · 23 August 2026<br>
> GPT2 × impasto × emerging forms × aesthetic prompt × VOL.046<br>
> A luminous impasto treatment with an oil-painted touch: fresher colour, tactile miniature volume, and subjects that seem to emerge from warm-white paper and a clear diagonal field.

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 046 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 046 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 046 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 046 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991">View the original post and full prompt →</a></p>

These samples demonstrate the 046 aesthetic motive. Their subjects, field direction, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## The original brief is authoritative

`references/046-source.md` is this project's sole creative and aesthetic authority. The Skill no longer summarizes or expands it, and it does not impose a shared palette, colour plan, aesthetic motive, title, or microcopy package. GPT Image 2 follows that brief's own rules for colour, material, composition, whitespace, wording, and typography.

Mode and size completely replace the legacy 3:4 top-bottom delivery container without rewriting the transformation aesthetic. Each asset sends GPT Image 2 one selected mode's final contract instead of asking it to interpret four alternatives inside a generic template.

## Four combinable output modes

Select one or more of `top-bottom`, `left-right`, `design-only`, and `wallpaper-pack`. When several are selected, each is generated independently with its own prompt.

- `top-bottom`: one complete canvas with the reality view above and transformed design below.
- `left-right`: one complete canvas whose left-right structure runs from top edge to bottom edge, source left and design right. Typography stays inside that structure rather than creating a shared third footer; widths may be asymmetric.
- `design-only`: the source is a non-visible reference for identity, structure, colour logic, and facts; every visible element follows this Panel's transformation language.
- `wallpaper-pack`: each device receives an independently composed full-canvas transformed wallpaper, with no source-photo region.

There is no seam, midpoint-percentage, or pixel-coordinate test. Deterministic assembly is used only when the user explicitly requests exact panel geometry or pixel-identical source preservation.

Ordinary sizes are also multi-select: auto-fit, source aspect, 1:1, 3:4, 4:3, 4:5, 5:4, 2:3, 3:2, 9:16, 16:9, 21:9, 5:7, 7:5, or custom ratios/exact pixels. There is no silent default. Every distinct aspect is independently recomposed from the same verbatim source brief.

Wallpaper packs may be linked or independent. A linked pack creates one anchor image, then recomposes each remaining device from the original source plus that anchor; it never crops one image into four sizes.

## Text modes

Before generation, resolve one of three choices:

1. **Model generates text from the original prompt**: the user supplies only the language or locale; GPT Image 2 follows the source brief's wording, amount, tone, and typography logic. Every word arises from the current image's content, atmosphere, or implied meaning, and anything presented as factual or documentary information must be grounded in supplied, visible, or verified facts.
2. **Use my exact text**: pass it verbatim, without rewriting, translating, or adding a title; typography still follows the source brief.
3. **No text**: prohibit visible text and pseudo-text.

The outer Skill no longer pre-writes titles, microcopy, or copy packages. Output language is resolved separately from the interface language and is never guessed from a person, scene, or filename.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Capability-adaptive questions and inline parameters

The same Skill adapts to the host's real interaction capabilities and never presents decorative symbols as clickable controls:

- **When Claude Code exposes `AskUserQuestion + multiSelect: true`**: modes and sizes use genuine checkboxes; text mode and wallpaper relationship use single-select. Common sizes are grouped into square, portrait, and landscape checkbox questions, selections accumulate across groups, and custom sizes use free input.
- **When Codex exposes only `request_user_input`**: use it only for mutually exclusive fields such as text mode and wallpaper relationship. Do not misrepresent modes or sizes as single-choice; collect them through clear combination input.
- **With no interactive question tool**: use two typed rounds—modes first, then sizes plus text. Never draw fake `- [ ]` boxes or ask the user to switch to Plan mode merely to obtain a form.

The second round initially shows only Smart recommendation, Source aspect, Common ratios, and Custom. Expand the full library only when requested: square `1:1`; portrait `3:4, 4:5, 2:3, 9:16, 5:7`; landscape `4:3, 5:4, 3:2, 16:9, 21:9, 7:5`. Any ratios may be combined, and exact pixels are always accepted.

All settings can also be passed inline:

```text
/xxd-panel-046 photo.jpg --mode top-bottom,design-only --size auto,3:4,9:16 --text prompt --locale ja-JP
```

Supported parameters are `--mode`, repeatable or comma-separated `--size`, `--text prompt|exact|none`, `--locale`, `--copy`, `--wallpaper linked|independent`, `--wallpaper-size`, and `--out`. Complete parameters skip preflight; partial parameters trigger only missing questions.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-046.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-046" ~/.codex/skills/xxd-panel-046
```

Claude Code users may link the same directory to `~/.claude/skills/xxd-panel-046`. Restart the agent session after installation.

```text
$xxd-panel-046
Turn this photograph into a left-right composition. Derive the copy from the image and write it in natural Korean.
```

You may invoke the Skill with only a photograph. It first asks for one or more modes in a numbered multiline menu, then for copy settings; wallpaper mode also asks for linked/independent continuity and device sizes.

Full specifications:

- [Skill workflow](SKILL.md)
- [Chinese runtime adapter](references/xxd-panel-046-prompt.zh-CN.md)
- [English runtime adapter](references/xxd-panel-046-prompt.en.md)
- [Original style brief](references/046-source.md)

## Boundaries and trust

- Each photograph stays within its own task and never borrows subjects, colours, copy, or composition from other inputs, old results, or samples.
- Every invocation creates a fresh task directory; even identical sources and parameters must generate anew.
- Deliverables are PNG bitmaps, never SVG, HTML, Canvas, or programmatic-drawing substitutes.
- The configured bitmap bridge emits sanitised status only and does not expose providers, endpoints, headers, credentials, prompts, or response bodies.
- Each selected ordinary mode returns one file; selected `wallpaper-pack` adds four separate wallpapers. `all` returns seven PNGs per source across four sibling mode directories, never a contact sheet or overview.

Local composition needs Python 3 and Pillow. The safe bitmap bridge uses Python 3.11+ `tomllib`. Image generation still requires a host agent with built-in raster generation or an already configured compatible raster route.

## Repository

```text
xxd-panel-046/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/ (reserved for future local samples)
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-046-prompt.zh-CN.md
    ├── xxd-panel-046-prompt.en.md
    └── 046-source.md
```

## About XXD

XXD is the abbreviated brand name of Xiaoxiaodong. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and Membership

### In-depth Consultation · CNY 299/hour

One-to-one consultation for using the Skills is billed at CNY 299 per hour. Contact Xiaoxiaodong through the WeChat QR code below to book.

### Xiaoxiaodong Skills User Community · CNY 99 to join

A one-time CNY 99 fee joins the community for workflow sharing, work discussion, and peer support. It does not include hourly one-to-one consultation. Include “Skills User Community” in your WeChat message.

### Knowledge Planet + Member Prompt Library · CNY 699/year

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) and the [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) are one membership: **one annual payment unlocks both, with no second purchase required.**

1. Subscribe through [Knowledge Planet](https://wx.zsxq.com/group/15554814142882), then contact Xiaoxiaodong on WeChat for a Prompt Library redemption code.
2. Subscribe through the [Member Prompt Library](https://vip.xiaoxiaodong.ai/), then contact Xiaoxiaodong on WeChat for a Knowledge Planet invitation.

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD paid community WeChat QR code" width="320"></a>
</p>

<div align="center">

**Keep the photograph recognisable; let it emerge again through paint, paper, and light.**

</div>

---

<div align="center">
  <h2>☕ Support this open-source project</h2>
  <p>If this project saved you time, a Star, a share, or a coffee helps keep it moving.</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Support Xiaoxiaodong through Buy Me a Coffee" width="180"></a><br>
        <strong>Buy me a coffee</strong><br>
        <sub>Scan or open the QR code to support Xiaoxiaodong</sub>
      </td>
    </tr>
  </table>
  <p><sub>Support is entirely optional and never changes access to this open-source project.</sub></p>
</div>
