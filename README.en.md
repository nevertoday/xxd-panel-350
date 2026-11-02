<div align="center">

# XXD Panel 350｜Neon Spirits

**Draws your photo's corner as a pale line drawing and turns the subject into a glowing, chubby rainbow spirit.**

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 350 · 01 · Cat on a sofa"><br><sub>01 · Cat on a sofa</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 350 · 02 · Windowsill plants"><br><sub>02 · Windowsill plants</sub></td>
  </tr>
</table>

<p align="center"><sub>Top: the original photo. Bottom: the same photo in this style.</sub></p>

## What it is

A Skill for AI agents such as Claude Code and Codex. Give it a photo and it paints a finished PNG following the original Panel 350 prompt.

- **What it looks like:** Clutter is removed, and the subject's small corner is drawn as a careful, realistic fine-ink line drawing that follows the photo's structure and perspective, tinted so lightly it is almost warm white. The subject itself is no longer line work but a soft, chubby spirit made only of glow: it keeps its outline, and its body spreads ring after ring from the centre, moving from the photo's brightest colour into pink, orange, yellow, green and blue, with just two small round eyes and a short line mouth. A few smaller spirits peek out from behind objects, crouch at the edges or trail a wisp of coloured smoke, joined by one arc of light, with plenty of empty space around. In the lower-right corner a tiny handwritten pencil line reads like a title written beside a painting.
- **Keywords:** Pale fine-ink line drawing · Chubby glowing spirit · Ringed rainbow halo · Dot eyes and line mouth · Coloured light arc · Pencilled title at lower right
- **What you can make:** A top–bottom comparison (photo above, design below), a left–right comparison, the design alone, or a wallpaper set for phone, tablet, desktop and watch. Pick several at once, at any ratio or exact pixel size.
- **What it is not:** Not a filter and not a template: every image is redrawn from your photo, and each photo is its own job.

## Get started in three steps

**1. Install.** Works with Claude Code, Codex and other agents that support Skills:

```bash
npx skills add https://github.com/nevertoday/xxd-panel-350 --skill xxd-panel-350
```

Then restart your agent session. You can also `git clone` this repository and link the folder to `~/.claude/skills/xxd-panel-350` or `~/.codex/skills/xxd-panel-350`.

**2. Make sure your agent can generate images.** This Skill has no image model of its own; it uses your agent's image generation, preferably GPT Image 2.

- Codex works as is when its built-in image generation is on.
- Claude Code and other agents without built-in image generation need an OpenAI-compatible image API. It takes about five minutes: see [Setting up image generation](#setting-up-image-generation).

Not sure? Just try it. If images can't be generated, the Skill stops and tells you before doing any work.

**3. Send a photo and say one sentence:**

> Use xxd-panel-350 to turn this photo into a 3:4 top–bottom poster with an English title.

If your request is complete, it starts right away; anything you left out (layout, ratio, text) it asks about, usually in one or two questions. Results are PNGs in a new folder under `~/Desktop/xxd/xxd-panel-350/`.

## Which photos work best

**Works well**

- An ordinary corner with one clear subject: a cat on a sofa, a dog on a porch, a pot plant on a windowsill
- Everyday objects with a recognisable shape: a teapot on a table, a bicycle against a wall, an old TV, a red door
- Photos with weak composition, messy backgrounds or a small subject, since the setting fades to line and only the subject glows

**Not a good fit**

- Subjects with a vague outline that are recognised only by detail, which get lost once they become glow
- Requests for a fully coloured illustration, a complete scene or a glossy commercial cartoon character
- Photos that call for a dark, realistic or serious mood, such as ID photos or news documentary

## Samples

Each image below is a finished result this Skill made from one photo. The top–bottom and left–right sets use different photos.

### Top–bottom: photo above, design below

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-01.png" alt="XXD Panel 350 · 01 · Cat on a sofa"><br><sub>01 · Cat on a sofa</sub></td>
    <td width="50%"><img src="./assets/examples/sample-02.png" alt="XXD Panel 350 · 02 · Windowsill plants"><br><sub>02 · Windowsill plants</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-03.png" alt="XXD Panel 350 · 03 · Dog on a porch"><br><sub>03 · Dog on a porch</sub></td>
    <td width="50%"><img src="./assets/examples/sample-04.png" alt="XXD Panel 350 · 04 · Teapot on a table"><br><sub>04 · Teapot on a table</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-05.png" alt="XXD Panel 350 · 05 · Bicycle against a wall"><br><sub>05 · Bicycle against a wall</sub></td>
    <td width="50%"><img src="./assets/examples/sample-06.png" alt="XXD Panel 350 · 06 · Kitchen stove"><br><sub>06 · Kitchen stove</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-07.png" alt="XXD Panel 350 · 07 · Desk lamp"><br><sub>07 · Desk lamp</sub></td>
    <td width="50%"><img src="./assets/examples/sample-08.png" alt="XXD Panel 350 · 08 · Laundromat"><br><sub>08 · Laundromat</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-09.png" alt="XXD Panel 350 · 09 · Bus stop"><br><sub>09 · Bus stop</sub></td>
    <td width="50%"><img src="./assets/examples/sample-10.png" alt="XXD Panel 350 · 10 · Pigeons by a bench"><br><sub>10 · Pigeons by a bench</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-11.png" alt="XXD Panel 350 · 11 · Old car"><br><sub>11 · Old car</sub></td>
    <td width="50%"><img src="./assets/examples/sample-12.png" alt="XXD Panel 350 · 12 · Bathtub"><br><sub>12 · Bathtub</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-13.png" alt="XXD Panel 350 · 13 · Upright piano"><br><sub>13 · Upright piano</sub></td>
    <td width="50%"><img src="./assets/examples/sample-14.png" alt="XXD Panel 350 · 14 · Armchair"><br><sub>14 · Armchair</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-15.png" alt="XXD Panel 350 · 15 · Basketball hoop"><br><sub>15 · Basketball hoop</sub></td>
    <td width="50%"><img src="./assets/examples/sample-16.png" alt="XXD Panel 350 · 16 · Watering can"><br><sub>16 · Watering can</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-17.png" alt="XXD Panel 350 · 17 · Convenience store"><br><sub>17 · Convenience store</sub></td>
    <td width="50%"><img src="./assets/examples/sample-18.png" alt="XXD Panel 350 · 18 · Staircase"><br><sub>18 · Staircase</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-19.png" alt="XXD Panel 350 · 19 · Dog on a bed"><br><sub>19 · Dog on a bed</sub></td>
    <td width="50%"><img src="./assets/examples/sample-20.png" alt="XXD Panel 350 · 20 · Balcony chair"><br><sub>20 · Balcony chair</sub></td>
  </tr>
</table>

</details>

### Left–right: photo left, design right

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-21.png" alt="XXD Panel 350 · 21 · Cat in a doorway"><br><sub>21 · Cat in a doorway</sub></td>
    <td width="50%"><img src="./assets/examples/sample-22.png" alt="XXD Panel 350 · 22 · Fridge"><br><sub>22 · Fridge</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-23.png" alt="XXD Panel 350 · 23 · Floor lamp"><br><sub>23 · Floor lamp</sub></td>
    <td width="50%"><img src="./assets/examples/sample-24.png" alt="XXD Panel 350 · 24 · Hallway"><br><sub>24 · Hallway</sub></td>
  </tr>
</table>

<details>
<summary>Show 16 more</summary>

<table>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-25.png" alt="XXD Panel 350 · 25 · Walker with umbrella"><br><sub>25 · Walker with umbrella</sub></td>
    <td width="50%"><img src="./assets/examples/sample-26.png" alt="XXD Panel 350 · 26 · Espresso machine"><br><sub>26 · Espresso machine</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-27.png" alt="XXD Panel 350 · 27 · Bookshelf"><br><sub>27 · Bookshelf</sub></td>
    <td width="50%"><img src="./assets/examples/sample-28.png" alt="XXD Panel 350 · 28 · Dog at a window"><br><sub>28 · Dog at a window</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-29.png" alt="XXD Panel 350 · 29 · Red door"><br><sub>29 · Red door</sub></td>
    <td width="50%"><img src="./assets/examples/sample-30.png" alt="XXD Panel 350 · 30 · Mailbox"><br><sub>30 · Mailbox</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-31.png" alt="XXD Panel 350 · 31 · Street lamp"><br><sub>31 · Street lamp</sub></td>
    <td width="50%"><img src="./assets/examples/sample-32.png" alt="XXD Panel 350 · 32 · Aquarium"><br><sub>32 · Aquarium</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-33.png" alt="XXD Panel 350 · 33 · Clothes rail"><br><sub>33 · Clothes rail</sub></td>
    <td width="50%"><img src="./assets/examples/sample-34.png" alt="XXD Panel 350 · 34 · Monstera"><br><sub>34 · Monstera</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-35.png" alt="XXD Panel 350 · 35 · Old TV"><br><sub>35 · Old TV</sub></td>
    <td width="50%"><img src="./assets/examples/sample-36.png" alt="XXD Panel 350 · 36 · Ladder"><br><sub>36 · Ladder</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-37.png" alt="XXD Panel 350 · 37 · Rotary phone"><br><sub>37 · Rotary phone</sub></td>
    <td width="50%"><img src="./assets/examples/sample-38.png" alt="XXD Panel 350 · 38 · Wall lamp by a door"><br><sub>38 · Wall lamp by a door</sub></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/examples/sample-39.png" alt="XXD Panel 350 · 39 · Cat on a chair"><br><sub>39 · Cat on a chair</sub></td>
    <td width="50%"><img src="./assets/examples/sample-40.png" alt="XXD Panel 350 · 40 · Front steps"><br><sub>40 · Front steps</sub></td>
  </tr>
</table>

</details>

## Just say it

No parameters to memorise. Say what you want:

| You want | Say |
|---|---|
| Top–bottom comparison | Make a 3:4 top–bottom comparison |
| Left–right comparison | Make a 16:9 left–right comparison, photo on the left |
| Design only | Just the design, no photo, 9:16 portrait |
| A wallpaper set | Make matching wallpapers for phone, tablet, desktop and watch |
| Several ratios | Make this one at 1:1, 3:4 and 16:9 |
| Your own text | Use the title “Let the wind pass through” exactly as written |
| No text | No text at all |
| Text language | Write the text in Japanese |
| A whole folder | Turn every photo in this folder into a top–bottom comparison |
| Same as last time | Use my settings from last time |

Prefer the command line? The flags map one to one:

```text
/xxd-panel-350 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale en-US
/xxd-panel-350 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-350 ./photos --mode left-right --size 16:9 --text prompt --locale ja-JP
```

All flags are listed under [Parameters](#parameters).

## FAQ

**Does the original photo have to appear?** No. Ask for “design only” or a wallpaper set and the whole canvas is design.

**Who writes the text?** By default the image model writes it from your photo; you only choose the language. Give your own words and they are used exactly; or ask for no text. Anything that looks factual (places, dates, numbers) comes only from you or from what is visible in the photo, never invented.

**What if I don't like the result?** Say “one more”. It redraws from the original photo instead of editing the last result, so every attempt is different.

**Do photos in a batch mix together?** No. Each photo is generated on its own and never borrows another photo's colours, text or layout. Settings are asked once for the whole batch.

**Where do my photos go?** Only to the image model your agent uses. The Skill uploads nothing elsewhere and never prints endpoints or keys.

**How does this relate to other Panels?** XXD Panels are a family of styles, one per number, fully independent; install only the ones you like. To have AI recommend a style for a photo, or compare several at once, use the catalog [xxd-panel-all](https://github.com/nevertoday/xxd-panel-all).

## Original prompt

This style is defined entirely by Xiaoxiaodong's [original prompt](references/original-prompt/zh-CN.md) (in Chinese). The Skill only appends the layout, size and text settings you choose; it never summarises, translates or rewrites the prompt.

Reading translations (for reading only; never sent to the image model): [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

## Setting up image generation

You need an OpenAI-compatible API that serves `gpt-image-2` (or a compatible model) and its API key. This creates a separate config and leaves your Codex settings alone:

```bash
mkdir -p ~/.xxd-imagegen
cat > ~/.xxd-imagegen/config.toml <<'EOF'
model_provider = "image"

[model_providers.image]
base_url = "https://api.openai.com/v1"   # or your compatible endpoint
env_key = "XXD_IMAGE_API_KEY"
EOF

# add to ~/.zshrc or ~/.bashrc so your agent can read them
echo 'export XXD_IMAGEGEN_CODEX_DIR=~/.xxd-imagegen' >> ~/.zshrc
echo 'export XXD_IMAGE_API_KEY=your-key' >> ~/.zshrc
```

Reopen your terminal and agent, then check once from this Skill's folder:

```bash
python3 scripts/configured_imagegen.py probe
```

`"ok":true` means it works. The check only reports readiness; it never prints the endpoint or key. If your Codex already generates images through a compatible API, skip this step.

## Parameters

| Flag | Values |
|---|---|
| `--mode` | `top-bottom` · `left-right` · `design-only` · `wallpaper-pack` (phone, tablet, desktop, watch); combine freely |
| `--size` | `auto` recommended · `source` match the photo · `1:1` `3:4` `4:3` `4:5` `5:4` `2:3` `3:2` `9:16` `16:9` `21:9` `5:7` `7:5` · exact pixels such as `2160x3840`; combine freely |
| `--text` | `prompt` written from the photo · `exact` your words (with `--copy "…"`) · `none` no text |
| `--locale` | text language, e.g. `zh-CN` `en-US` `ja-JP` `ko-KR` `ar` |
| `--wallpaper` | `linked` a matching set · `independent` four separate designs |
| `--wallpaper-size` | device pixels, e.g. `phone=1440x3200,desktop=3840x2160` |
| `--out` | another output root (default `~/Desktop/xxd/xxd-panel-350/`) |
| `--prefs` | `last` reuse · `edit` start from last time · `new` choose again · `off` don't remember this time · `clear` forget |

- With every value given, nothing is asked; otherwise only the missing values are. Pass a folder instead of `photo.jpg` to batch.
- Combinations are generated one by one: 2 modes × 3 sizes = 6 images, each composed for its own canvas rather than cropped.
- Comparisons are exactly 50:50. Usually the model paints only the design half and a script places the untouched photo beside it, so the split is centred and the photo is unchanged.
- Files are named like `source-001-street-top-bottom-3x4-1152x1536.png`, all in one flat task folder.
- Only layout, size, text mode and language are remembered, never photos, copy or keys.

<!-- xxd-readme-ads:start -->
## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. This project is created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Xiaoxiaodong multi-platform membership · CNY 699/year

> **Advertising disclosure:** The QR code, membership, and paid-service links below are XXD promotional information. Scanning or purchasing is entirely optional and does not affect access to this project.

One annual membership unlocks three benefits together: **Knowledge Planet + the XXD Member Prompt Library + membership for all General Skills**. They are included in one membership; no separate purchase is required.

<!-- xxd-panel-command-system:start -->

### How the Skills work together

| Level | Included | What it does |
|---|---|---|
| **General** | [`xxd-panel-all`](https://github.com/xiaoxiaodong-ai/xxd-panel-all) | Detects available numbered Skills, recommends them by image, theme, or use, and organizes multi-style and batch tasks. |
| **Soldier** | `xxd-panel-NNN` | Each numbered Skill follows its own original brief and aesthetic to complete the specific task assigned by the General. |

<!-- xxd-panel-command-system:end -->

### What you receive

1. **One-to-one WeChat AI learning and project support**
   Add Xiaoxiaodong on WeChat via the QR code below to discuss AI learning, tools, and real projects one to one, with practical guidance and answers. Representative questions may be organized into member resources.
2. **A growing member prompt library**
   The [XXD Member Prompt Library](https://vip.xiaoxiaodong.ai/) currently contains about 32,000 prompts and will keep expanding, with a goal of exceeding 100,000.
3. **All General Skills and usage support**
   One membership covers every General Skill, with usage guidance and Q&A when you need help.
4. **Priority for high-need requests**
   Frequently requested, high-need prompts and Skills are reviewed and developed first where appropriate.

### How to join

- [Activate membership on the member website](https://vip.xiaoxiaodong.ai/).
- Or scan the QR code below to add Xiaoxiaodong on WeChat for one-to-one activation support.

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="Contact Xiaoxiaodong" width="280"></a></p>
<!-- xxd-readme-ads:end -->

## License

**Free for noncommercial use; commercial use needs separate permission.** This project (Skill, original prompts, scripts and documentation) is licensed under [PolyForm Noncommercial 1.0.0](LICENSE). The source is public, but it is not open source as the OSI defines it.

- **Free:** personal study and hobby work; making images from your own photos to keep or share on your personal accounts (not ads, sponsored posts or product promotion); noncommercial changes and redistribution with the LICENSE included.
- **Commercial use by individuals needs permission:** paid client work, ads and product promotion, small-batch merchandise, paid courses or communities. Usually granted, as the author confirms in writing.
- **Organisations must sign an agreement:** any commercial use by a company, studio, MCN or brand, internal use included, and any integration into an app, website, SaaS or API.
- **Not licensed:** reselling, renaming or repackaging the Skills, prompts or samples.
- The Xiaoxiaodong membership does not include a commercial licence. The original photos in the samples belong to their photographers and are shown for demonstration only.

To apply, add Xiaoxiaodong on WeChat and write "commercial licence". Full terms and the QR code: [Commercial licensing](COMMERCIAL.md).
