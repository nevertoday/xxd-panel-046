<p align="center">
  <img src="./assets/banner.svg" alt="XXD Panel 046 项目横幅" width="1200">
</p>

<div align="center">

# 🦁 XXD Panel 046

### 把照片重构成一座明亮、鲜活、可以触摸的厚涂微景观

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Four Modes](https://img.shields.io/badge/Modes-4-d75d32?style=flat-square)](#四种输出共享同一种厚涂逻辑)
[![Raster Output](https://img.shields.io/badge/Output-PNG-3c6f67?style=flat-square)](#边界与信任)

<strong>简体中文</strong> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

> 明亮白底 · 鲜活厚涂 · 微缩实体 · 斜向色带 · 温暖光感

XXD Panel 046 是一个面向 Codex 与兼容 Agent 的图像生成 Skill。它从照片中保留可辨认的主体身份，再把主体重构为具有颜料厚度、刮刀痕迹和微缩尺度的油画微景观。

主体由一条源图推导出的斜向色带承托，周围保留大面积暖白纹理纸面；色彩明亮、清透、有生命力，文字则像艺术出版物中的精致标注，而不是后贴的大标题。

## 为什么需要 046

普通“厚涂风”很容易退化成两种模板：把整张照片套上暗沉油画滤镜，或把主体做成塑料玩具，再放到一条与原图无关的彩色笔刷上。

046 的顺序完全相反：

```text
锁定主体身份 → 推导斜向承托场 → 集中真实厚涂 → 提亮源图色彩 → 留出暖白呼吸空间 → 加入精致出版物文字
```

如果换成一张无关照片，微缩主体、斜向色带、配色、光线和文字仍然成立，这张图就不属于 046。

## 046 的视觉契约

- **可辨认的微缩主体：** 至少保留三个源图专属身份线索，优化角度与细节但不更换主体。
- **一条斜向承托场：** 色带可成为水面、地面、路径、光带或风景切片，但必须来自源图并真正承托主体。
- **真实厚涂材料：** 颜料堆积、刮刀纹、起伏边缘、纸张肌理和薄厚对比同时存在。
- **明亮源图配色：** 提取照片中最鲜活的颜色，提高明度和纯净度，但不套固定糖果色盘。
- **大面积暖白留白：** 让纸面、光线和微缩尺度共同呼吸，不把整张画布涂满。
- **清透温暖光感：** 晴朗、轻快、有生命力，不做暗褐滤镜、荧光光效或商业棚拍。
- **艺术出版物文字：** 使用精细、克制、略带纸面吸墨感的编辑字体，沿斜向轴、主体边缘或安静白边排布。

## 样张 · 来自 X

> [小小东（@xiaoxiaodong01）](https://x.com/xiaoxiaodong01/status/2091337011403882991) · 2026 年 8 月 23 日<br>
> GPT2 × 厚涂 × 浮现 × 美学提示词 × VOL.046<br>
> 一套带有油画触感的明亮厚涂风格：颜色更鲜活，主体像从暖白纸面与清透色带中慢慢浮现。

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrOaFb0AAgHbh.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 样张 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrSePaAAA9ZPO.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 样张 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrT6wa4AANlxa.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 样张 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991"><img src="https://pbs.twimg.com/media/HQXrVbna4AAm6My.jpg?format=jpg&amp;name=large" alt="XXD Panel 046 样张 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091337011403882991">查看原推文与完整提示词 →</a></p>

这些样张用于展示 046 的美学动机，不会把样张中的主体、色带方向、配色、文案或旧画幅变成生成参考或当前默认值。

## 四种输出共享同一种厚涂逻辑

四种模式支持单选或多选。可回复 `1`、`1+3`、`1、2、4` 或 `全部`；Skill 去重后按 1→4 执行。每种模式独立输出并进入独立子文件夹，不制作总图；`全部` 每张原图得到 7 个 PNG（前三种各 1 张＋壁纸 4 张）。尺寸可在同一回复中按模式标注，未标注普通模式按源图适配；文案默认跨所选模式共用，也可按模式单独指定。

| 模式 | 尺寸逻辑 | 成品 |
| --- | --- | --- |
| `top-bottom` | 源图自适应 | 上方完整原图，下方 046 厚涂微景观；两块都保持原图完整尺寸，严格 50/50 |
| `left-right` | 源图自适应 | 左侧完整原图，右侧 046 厚涂微景观；两块都保持原图完整尺寸，严格 50/50 |
| `design-only` | 源图自适应 | 只显示变化设计，不显示原照片；沿用原图比例和尺寸 |
| `wallpaper-pack` | 四种设备尺寸 | 分别输出手机、iPad、电脑、儿童手表四张 PNG |

用户精确尺寸 > 指定比例或用途 > 普通模式源图自适应。原始 `046.md` 里的 3:4 只是一开始的创作画幅，不会被写成当前 Skill 的静默默认值。

双联模式的摄影区域保持真实，只允许克制调色和必要的环境扩展。纯设计版与壁纸仍以照片为事实依据，但不显示原片。

### 四端壁纸：连贯或独立

壁纸没有静默尺寸默认。可选择常用预设——手机 `1440×3200`、iPad `2048×2732`、电脑 `3840×2160`、儿童手表 `1024×1024`——也可逐设备自定义。

- **连贯套装（推荐）：** 先生成并验收 iPad 定调图，另外三张都直接参考原照片＋同一张定调图，分别为设备重新构图。
- **四张独立：** 每张只参考原照片，可以探索更自由的微缩主体位置、斜向色带与光线关系。

连贯不等于裁切。四张壁纸始终分别生成、分别构图、分别验收，也不会按 iPad→手机→电脑→手表顺序垫图造成漂移。

## 文字必须像艺术出版物的一部分

正式生图前，先选择自动文案、自定义文案或无文字。有文字时还要指定目标语言或地区。

自动文案从主体身份、已知地点、可见气氛或有证据的象征意义中提炼一个简短标题。它可以温暖而有诗意，但不强求双关、反转或统一的“会心一击”。

默认只有一个标题；只有确有信息价值时才增加零至两条短注释，不会为了显得高级而编造编号、年份、坐标或档案标签。文案仍需通过换图测试。

用户提供最终成稿时逐字保留。用户提供的是方向或可编辑草稿时，才会在保留受众、目的、必备词、语气和潜台词的前提下专业深化。

语言遵循目标受众，而不是用户下指令时使用的语言：

```text
目标市场或受众 > 指定成品语言 > 用户方向语言；都不明确时生图前询问
```

日本版使用自然日语，韩国受众使用自然韩语与正确空格，英国版使用英式英语，阿拉伯语版默认使用自然的现代标准阿拉伯语和真正的从右到左排版。字体也会转译为当地文字系统中自然的精致编辑字形，而不是把拉丁字体规则生硬套过去。

## 精确拼版交给代码，作品交给图像生成

图像模型负责微缩主体、斜向承托场、真实厚涂、清透光线、留白和文字。`scripts/compose_panel.py` 只负责画布规划、精确 50/50 位图拼合、最终尺寸和审计，不会用程序绘图伪造成品。

```bash
python3 scripts/compose_panel.py --plan --layout top-bottom --source photo.png
python3 scripts/compose_panel.py --plan --layout left-right --size 2560x1440
python3 scripts/compose_panel.py --audit result.png --layout design-only --size 2048x2048
```

精确上下画布的总高度必须为偶数，精确左右画布的总宽度必须为偶数。Skill 不会静默修改用户指定的像素。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-046.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-046" ~/.codex/skills/xxd-panel-046
```

Claude Code 用户可以把同一目录链接到 `~/.claude/skills/xxd-panel-046`。安装后重新启动 Agent 会话。

```text
$xxd-panel-046
把这张照片做成左右双联，文案由你根据照片内涵创作，使用自然韩语。
```

只上传照片也可以调用。Skill 会先用分行编号菜单询问一个或多个模式，再询问文字设置；选择壁纸时还会确认连贯或独立以及设备尺寸。

完整规范：

- [Skill 工作流](SKILL.md)
- [中文完整提示词](references/xxd-panel-046-prompt.zh-CN.md)
- [英文完整提示词](references/xxd-panel-046-prompt.en.md)
- [原始风格提示词](references/046-source.md)

## 边界与信任

- 每张照片只在自己的任务中使用，不借用其他输入、旧成品或样张里的主体、颜色、文案和构图。
- 每次调用都创建新的任务子文件夹；相同原图和参数也要重新生成，旧成品不能冒充当前任务。
- 最终交付为 PNG 位图，不是 SVG、HTML、Canvas 或程序绘图替代品。
- 已配置位图桥接只返回脱敏状态，不显示供应商、端点、请求头、凭据、提示词或服务器响应正文。
- 每个所选普通模式各返回一张；若选择 `wallpaper-pack`，再返回四张独立壁纸。选择 `全部` 时每张原图共返回 7 个 PNG，分处四个同级模式文件夹，绝不生成拼贴总览。

本地拼版需要 Python 3 和 Pillow。安全位图桥接使用 Python 3.11+ 的 `tomllib`。图像生成仍需要主机 Agent 的内置位图能力或已经配置好的兼容位图路径。

## 项目结构

```text
xxd-panel-046/
├── SKILL.md
├── README.md / README.en.md / README.ja.md / README.ko.md / README.ar.md
├── agents/openai.yaml
├── assets/
│   ├── banner.svg
│   └── examples/（未来本地样张占位）
├── scripts/
│   ├── compose_panel.py
│   └── configured_imagegen.py
└── references/
    ├── xxd-panel-046-prompt.zh-CN.md
    ├── xxd-panel-046-prompt.en.md
    └── 046-source.md
```

## 关于 XXD

XXD 是小小东的品牌名称缩写。项目由 [@xiaoxiaodong01](https://x.com/xiaoxiaodong01) 创建并维护。

## 服务与会员

### 深度咨询 · 299 元/小时

Skills 使用的一对一深度咨询按 299 元/小时收费。请通过下方微信二维码联系小小东预约。

### 小小东 Skills 用户交流群 · 入群 99 元

一次支付 99 元加入用户交流群，用于交流工作流、作品与互助；不包含按小时的一对一深度咨询。扫码后请备注“Skills 用户交流群”。

### 知识星球＋成员提示词库 · 699 元/年

[知识星球](https://wx.zsxq.com/group/15554814142882)与[小小东成员提示词库](https://vip.xiaoxiaodong.ai/)是同一份会员权益：**一次年费同时开通两边，无需重复付费。**

1. 在[知识星球](https://wx.zsxq.com/group/15554814142882)开通后，微信联系小小东领取成员提示词库兑换码。
2. 在[成员提示词库](https://vip.xiaoxiaodong.ai/)自助开通后，微信联系小小东邀请进入知识星球。

<p align="center">
  <a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="小小东付费服务微信二维码" width="320"></a>
</p>

<div align="center">

**保留照片的身份，让它从颜料、纸面和光里重新浮现。**

</div>

---

<div align="center">
  <h2>☕ 为开源项目赞助算力</h2>
  <p>如果这个项目为你节省了时间，可以通过微信或支付宝赞助后续测试与生成算力。</p>
  <table>
    <tr>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/wechat-reward-qr.png" alt="小小东微信算力赞助二维码" width="180"></a><br>
        <strong>微信算力赞助</strong>
      </td>
      <td align="center" width="240">
        <a href="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png"><img src="https://colors.xiaoxiaodong.ai/docs/images/alipay-reward-qr.png" alt="小小东支付宝算力赞助二维码" width="180"></a><br>
        <strong>支付宝算力赞助</strong>
      </td>
    </tr>
  </table>
  <p><sub>赞助完全自愿，不会改变这个开源项目的使用权限。</sub></p>
</div>
