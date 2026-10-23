# 公子教代码做事 · 效果看板

【效果看板】一次性展示官方基准测试中位数：代码量更少、成本更低、速度更快。 注意是基准数据，不是当前仓库的真实统计。只展示，不改任何东西。 触发词：/ponytail-gain、ponytail 有什么用、能省多少。

## 📺 看看效果

![ponytail-gain](screenshots/hero.png)

> 把 `screenshots/hero.png` 换成真实效果图（建议 1200px 宽、不超过 400KB）

## What This Does

【效果看板】一次性展示官方基准测试中位数：代码量更少、成本更低、速度更快。 注意是基准数据，不是当前仓库的真实统计。只展示，不改任何东西。 触发词：/ponytail-gain、ponytail 有什么用、能省多少。

### Key Features

- Scoreboard
- Honesty boundary
- Boundaries

## Installation

### WorkBuddy

```bash
git clone https://github.com/<you>/ponytail-gain.git ~/.workbuddy-ai/skills/ponytail-gain
pip install -r ~/.workbuddy-ai/skills/ponytail-gain/requirements.txt
```

### Claude Code / 其他 Agent

```bash
mkdir -p ~/.claude/skills/ponytail-gain
cp -R SKILL.md README.md requirements.txt scripts references \
      ~/.claude/skills/ponytail-gain/
```

把仓库链接丢给 agent，它会按 `SKILL.md` 加载所需文件。

## Usage

触发词：**/ponytail-gain、ponytail 有什么用、能省多少**

## Architecture

| 文件 | 作用 |
|---|---|
| `SKILL.md` | 触发条件与流程 |

## Requirements

- Python 3.9+
- `pip install -r requirements.txt`

## Credits

基于 [Ponytail](https://github.com/DietrichGebert/ponytail)（MIT，作者 DietrichGebert）改写

Created by 公子 · [@你的GitHub](https://github.com/).

## License

MIT — Use it, modify it, share it.
