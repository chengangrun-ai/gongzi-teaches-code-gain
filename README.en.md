English | [中文](README.md)

# gongzi-teaches-code-gain

An agent skill that prints a one-shot **benchmark scoreboard**: how much less code, how much less money, how much faster.

It only displays. Nothing is edited, no mode is changed, nothing is persisted. Look at it and close it.

![效果看板：基准测试中位数](screenshots/hero.png)

## Why it exists

"Writing less code saves money" is a sentence that says nothing — nobody knows how much.

This skill puts the numbers on the table: the published medians across 5 everyday tasks (email validator, debounce, CSV sum, countdown timer, rate limiter) and 3 models (Haiku, Sonnet, Opus).

## What it looks like

```
  ponytail gain                     benchmark median · 5 tasks · 3 models

  Lines of code   no-skill  ████████████████████  100%
                  ponytail  ██▌·················    6–20%   ▼ 80–94%
  Cost            no-skill  ████████████████████  100%
                  ponytail  █████▌··············   23–53%  ▼ 47–77%
  Speed           ponytail  ▸ 3–6× faster

  This repo:  /ponytail-debt  (shortcuts you deferred)
              /ponytail-audit (what's still cuttable)
```

## The honest part

These are **benchmark medians, not your repo**.

It will never print a per-repo savings number ("you saved X lines here") — the unbuilt version was never written, so there's no real baseline to subtract from. The only real per-repo figure comes from `/ponytail-debt`, which counts an actual ledger. So the card points there instead of inventing one.

## Install

```bash
git clone https://github.com/chengangrun-ai/gongzi-teaches-code-gain.git \
  ~/.workbuddy-ai/skills/gongzi-teaches-code-gain
```

No dependencies, no pip install.

## Usage

```
/ponytail-gain
```

Or just ask: "how much does this actually save?" / "show me the numbers."

## Boundaries

- One-shot display. Edits nothing, changes no mode, leaves no trace.
- Never fabricates per-repo savings.
- To exit: say "normal mode" or `stop ponytail`.

## The series

<p>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/01-main.png" width="32%" alt="主技能"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-review"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/02-review.png" width="32%" alt="改动审查"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-audit"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/03-audit.png" width="32%" alt="整仓审计"></a>
</p>
<p>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-debt"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/04-debt.png" width="32%" alt="欠账本"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-help"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/06-help.png" width="32%" alt="速查卡"></a>
</p>

> Five companions, one idea: the best code is the code you never wrote.

## Credits

Rewritten from [Ponytail](https://github.com/DietrichGebert/ponytail) (MIT, by DietrichGebert). The original copyright notice is preserved in `LICENSE`.

## License

MIT. See [LICENSE](LICENSE).

Made by [Gongzi](https://github.com/chengangrun-ai).
