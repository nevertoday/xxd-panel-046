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

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 046 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 046 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 046 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

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

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

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
