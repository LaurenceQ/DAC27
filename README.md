# DAC27 — IEEE LaTeX Template

基于 IEEE conference 模板的精简论文骨架。

## 文件

- `main.tex`：论文主文件，仅保留标题、作者、摘要、关键词与章节骨架。
- `IEEEtran.cls`：原始 IEEE 排版类。

## 编译

安装 TeX Live 或 MiKTeX 后，在项目根目录运行：

```sh
latexmk -pdf -interaction=nonstopmode -halt-on-error main.tex
```

也可将 `main.tex` 和 `IEEEtran.cls` 导入 Overleaf，并将主文件设为 `main.tex`。

## 使用

填写标题、作者、摘要和关键词，然后撰写 Introduction、Related Work、Methodology、Experimental Results 和 Conclusion。需要引用时，将末尾的 References 标题替换为实际参考文献环境或 BibTeX 命令。

模板格式是否符合目标会议要求，应以该会议提供的模板和投稿说明为准。

IEEE 原始文件中的版权和许可声明予以保留；本项目未为第三方文件另行授予许可。

## GitHub

仓库：https://github.com/LaurenceQ/DAC27
