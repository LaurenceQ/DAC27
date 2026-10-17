# DAC27 — IEEE LaTeX Template

基于本地 `conference-latex-template.zip` 中的 IEEE conference 模板。

## 文件

- `main.tex`：论文主文件，保留原始示例内容。
- `IEEEtran.cls`：原始 IEEE 排版类。
- `fig1.png`：示例图片。
- `docs/original-template.pdf`：压缩包中的原始示例 PDF，并非本项目重新编译的结果。
- `docs/IEEEtran_HOWTO.pdf`：IEEEtran 使用指南。

## 编译

安装 TeX Live 或 MiKTeX 后，在项目根目录运行：

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

也可将 `main.tex`、`IEEEtran.cls` 和 `fig1.png` 导入 Overleaf，并将主文件设为 `main.tex`。

## 使用

修改标题、作者、摘要和正文，提交前移除示例与指导文字。模板格式是否符合目标会议要求，应以该会议提供的模板和投稿说明为准。

IEEE 原始文件中的版权和许可声明予以保留；本项目未为第三方文件另行授予许可。

## GitHub

本地已使用 Git 管理。远程仓库创建并首次推送后，可在 GitHub 仓库的 Settings → General 中启用 **Template repository**，以便通过 **Use this template** 创建其他项目。
