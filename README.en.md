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
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrOaFb0AAgHbh.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrSePaAAA9ZPO.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrT6wa4AANlxa.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrVbna4AAm6My.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991">View the original post and full prompt →</a></p>

These samples demonstrate the 046 aesthetic motive. Their subjects, field direction, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four outputs, one impasto logic

The four modes support single or multiple selection. Reply with `1`, `1+3`, `1,2,4`, or `all`; the Skill deduplicates and runs them in menu order 1→4. Every mode is delivered independently in its own task directory—never as an overview—and `all` yields seven PNGs per source (one for each ordinary mode plus four wallpapers). Sizes may be labelled by mode in the same reply; unlabeled ordinary modes remain source-adaptive. Copy is shared across selected modes by default and may be overridden per mode.

| Mode | Sizing logic | Deliverable |
| --- | --- | --- |
| `top-bottom` | source-adaptive | complete source above, 046 impasto micro-landscape below; both panels retain the source size and split exactly 50/50 |
| `left-right` | source-adaptive | complete source left, 046 impasto micro-landscape right; both panels retain the source size and split exactly 50/50 |
| `design-only` | source-adaptive | transformed design only, with no visible source photo; retains source ratio and dimensions |
| `wallpaper-pack` | four device sizes | separate phone, iPad, desktop, and children's-watch PNGs |

Exact user pixels > explicit ratio or destination > source adaptation for ordinary modes. The original `046.md` used a 3:4 creative canvas, but that historical example is not a silent default in the current Skill.

Photography in paired modes stays truthful, with only restrained grading and necessary environmental extension. Design-only and wallpapers still use the photograph as evidence but do not show it.

### Wallpaper packs: linked or independent

Wallpaper mode has no silent size default. Choose the common preset—phone `1440×3200`, iPad `2048×2732`, desktop `3840×2160`, watch `1024×1024`—or give labelled custom sizes.

- **Linked pack (recommended):** generate and approve the iPad anchor first; every other device references the original photo plus that same anchor and is recomposed for its canvas.
- **Independent set:** every device references only the source photograph and may explore freer miniature placement, diagonal fields, and light relationships.

Linked never means cropped. All four files are separately generated, composed, and reviewed, with no iPad→phone→desktop→watch reference chain.

## Copy must belong to the art publication

Before generation, choose automatic copy, custom copy, or text-free output. Name the target language or locale whenever copy is present.

Automatic copy distils one short title from subject identity, known place, visible atmosphere, or a symbol supported by the photograph. It may be warm and poetic, but does not force a pun, reversal, or standardised “moment of recognition”.

The default is one title. Add zero to two short annotations only when they carry real information; never invent catalogue numbers, years, coordinates, or archival labels merely to look sophisticated. Copy must still pass the unrelated-image swap test.

Finished user wording stays verbatim. A direction or editable draft is refined only while preserving audience, purpose, mandatory words, tone, and implication.

Language follows the intended audience rather than the command language:

```text
target market or audience > requested output language > direction language; if none is explicit, ask before generation
```

A Japanese edition uses natural Japanese, a Korean-audience edition uses natural Korean and correct spacing, a UK edition uses British English, and Arabic defaults to natural Modern Standard Arabic with genuine right-to-left composition. The Skill never guesses nationality from appearance, clothing, scenery, or signs and never uses pseudo-foreign text.

## Code guarantees geometry; image generation creates the artwork

The image model creates the miniature subject, diagonal support field, genuine impasto, luminous light, whitespace, and type. `scripts/compose_panel.py` only plans canvases, performs exact 50/50 raster composition, finalises dimensions, and audits results. It never fakes artwork with programmatic drawing.

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

Exact top-bottom canvases need an even total height; left-right canvases need an even total width. Requested pixels are never silently changed.

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
- [Chinese full prompt](references/xxd-panel-046-prompt.zh-CN.md)
- [English full prompt](references/xxd-panel-046-prompt.en.md)
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
