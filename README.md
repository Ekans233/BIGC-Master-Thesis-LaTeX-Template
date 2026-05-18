# 北京印刷学院硕士学位论文 LaTeX 模板 ✧˖°

```
  ╔══════════════════════════════════════╗
  ║  BIGC-Master-Thesis-LaTeX-Template   ║
  ╚══════════════════════════════════════╝
```

![Stone Badge](https://stone.professorlee.work/api/stone/Ekans233/BIGC-Master-Thesis-LaTeX-Template)

> 学校不提供官方 LaTeX 模板，于是自己按撰写规范搭建了一套 (ง •̀_•́)ง
> 开箱即用，格式无误，论无忧查重万字错误率为 0 ✿

如果你觉得有用，点个 star 喵⭐ (´▽`ʃ♡ƪ)

---

## ♡ 快速开始

1. 编辑 `config/metadata.tex`，填入你的个人信息（姓名、学号、导师、题目等）
2. 在 `chapters/` 目录下撰写各章内容
3. 编译：

```bash
xelatex  BIGC_Masters_Thesis.tex
bibtex   BIGC_Masters_Thesis
xelatex  BIGC_Masters_Thesis.tex
xelatex  BIGC_Masters_Thesis.tex
```

或使用 `latexmk -xelatex BIGC_Masters_Thesis.tex` 一键编译~

> 详细使用说明请查看 [README-使用前请读我.md](README-使用前请读我.md)

## ♡ 项目结构

```
BIGC_LatexTemplate/
├── BIGC_Masters_Thesis.tex   ← 主文件（入口）
├── config/
│   ├── preamble.tex          ← 宏包、页面样式、页眉页脚配置
│   └── metadata.tex          ← 个人信息（姓名、学号、导师等）
├── frontmatter/
│   ├── titlepage.tex         ← 封面/题名页
│   ├── acknowledgements.tex  ← 致谢
│   ├── abstract_cn.tex       ← 中文摘要
│   └── abstract_en.tex       ← 英文摘要
├── chapters/
│   ├── chapter1.tex ~ chapter5.tex  ← 正文各章
├── backmatter/
│   ├── references.tex        ← 参考文献页
│   ├── achievements.tex      ← 攻读学位期间成果
│   └── declaration.tex       ← 独创性声明与授权说明
├── Figures/                  ← 所有图片存放目录
└── ref.bib                   ← 参考文献数据库
```

## ♡ 环境要求

- **TeX 发行版**：TeX Live 2023+（推荐）或 MiKTeX
- **编译引擎**：XeLaTeX（必须）
- **编辑器**：VS Code + LaTeX Workshop / TeXstudio

## ♡ 主要负责人

[@绿青馆的猫猫本人](https://github.com/Ekans233)

感谢 GitHub Copilot、Claude Code、Codex、Mimo 等 AI 工具的辅助 (ﾉ>ω<)ﾉ

## ♡ 建议与反馈

有建议可以直接 [提 issue](https://github.com/Ekans233/BIGC-Master-Thesis-LaTeX-Template/issues)，看见就会回复的说~

---

```
  ∧＿∧
（｡･ω･｡）つ━☆・*。
 ⊂　　 ノ 　　　・゜+.
　しーＪ　　　°。+ *
　　　　　　　　　.・゜
  クリスマスおめでとう... って、まだ早い？
```
