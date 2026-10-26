中文 | [English](README.en.md)

# 公子教代码做事 · 效果看板

一个 agent 技能，一次性打印一块**基准测试记分板**：少写多少代码、省多少钱、快多少倍。

只展示，不改任何东西。看完就关掉，不驻留、不写文件、不改模式。

![效果看板：基准测试中位数](screenshots/hero.png)

## 为什么有它

「少写代码更省钱」这句话，说了等于没说——没人知道到底省多少。

这个技能把数字摊在桌面上：5 个日常任务（邮箱校验、防抖、CSV 求和、倒计时、限流器）× 3 个模型（Haiku / Sonnet / Opus）的中位数。

## 它长什么样

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

## 一句实话

这些是**基准测试的中位数，不是你仓库的实测**。

这个技能永远不报「你这个仓库省了 X 行」——因为那版没写的代码根本不存在，没有基线可以减。真实数字只有一个来源：`/ponytail-debt` 数出来的账本。所以这张卡片会指向它，而不是编一个数字。

## 安装

```bash
git clone https://github.com/chengangrun-ai/gongzi-teaches-code-gain.git \
  ~/.workbuddy-ai/skills/gongzi-teaches-code-gain
```

没有依赖，不用 pip install。

## 用法

```
/ponytail-gain
```

或者直接问「这个技能到底能省多少」「给我看看数据」。

## 边界

- 一次性展示。不改代码、不改模式、不留痕迹。
- 不虚构单仓库收益数字。
- 想退出：说「正常模式」或 `stop ponytail`。

## 同系列

<p>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/01-main.png" width="32%" alt="主技能"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-review"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/02-review.png" width="32%" alt="改动审查"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-audit"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/03-audit.png" width="32%" alt="整仓审计"></a>
</p>
<p>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-debt"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/04-debt.png" width="32%" alt="欠账本"></a>
  <a href="https://github.com/chengangrun-ai/gongzi-teaches-code-help"><img src="https://raw.githubusercontent.com/chengangrun-ai/gongzi-teaches-code/main/screenshots/06-help.png" width="32%" alt="速查卡"></a>
</p>

> 五个配套，一个主张：最好的代码是没写的那行。

## 致谢

基于 [Ponytail](https://github.com/DietrichGebert/ponytail)（MIT，作者 DietrichGebert）改写，保留了原作者的版权声明（见 `LICENSE`）。

## License

MIT. See [LICENSE](LICENSE).

Made by [公子](https://github.com/chengangrun-ai).
