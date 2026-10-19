# Product reel · omnigami

Everything you make, one item a beat.

A short reel of a whole range. Each item gets a beat: its photo, its name, a detail line and its kind huge and pale behind it. The last item pulls back into your real catalogue screen, your numbers count up, every item orbits one line, your real search finds one, and your name and address hold to the end.

Watch it play live, and change its words, at [omnigami.ai/skills/product-reel](https://omnigami.ai/skills/product-reel).

## Install

In Claude Code:

```
/plugin marketplace add omnigami-ai/skills
/plugin install omnigami-product-reel@omnigami
```

With the skills CLI, for Claude Code and other agents that read SKILL.md:

```bash
npx skills add omnigami-ai/product-reel
```

Or copy `skills/product-reel/` into your agent's skills folder (for Claude Code, `~/.claude/skills/product-reel/`). Then ask:

```
Make a product reel of everything on https://your-shop.com
```

## What it runs

The skill works on your computer. It runs the Node scripts in `skills/product-reel/scripts/`: they open your product's pages in a local headless browser to capture its real screens, then render the film with that browser and ffmpeg, writing MP4s and an editable HTML film to your project. It sends nothing to omnigami or anyone else, and uses no network beyond loading your own product's pages and the fonts and assets in this folder.

## You need

- Claude Code with Opus 5.5
- Node 20 or later
- ffmpeg
- Chrome, Chromium, Edge or Brave

None beyond your Claude plan’s usage. Node, ffmpeg and the browser are free.

## Licence

Free to use. Use the films and anything else the skill makes for anything, commercial work included. Don't redistribute the skill. See [LICENSE.md](LICENSE.md). The bundled fonts keep their own licence (SIL Open Font License, beside them in `reference/assets/fonts/`).

## Credits

Style inspired by @justinmfarrugia’s video (https://x.com/justinmfarrugia/status/2103822390870569266); @justinmfarrugia didn’t make or endorse this skill. Its example shows Fernwise, a fictional company made for omnigami’s examples, with sample data.

omnigami is not affiliated with Anthropic. More skills at [omnigami.ai](https://omnigami.ai).
