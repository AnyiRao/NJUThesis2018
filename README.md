# NJUThesis

南京大学本科生毕业论文LaTex模板 2018 新版

## 作者饶安逸 个人主页 http://anyirao.com

## 鸣谢

* 本模板由学长学姐的南京大学硕士博士学文论文模板改编而来。


## 声明

* 此模版用于生成符合南京大学学位论文排版要求和相应的国家规范、行业标准的学位论文；

* 本科毕业生毕业论文没找到相应的明文要求，宽容度较大，本模板应该能符合教务处的规范；

* 限于精力未提供详细使用说明。

## 下载与使用

github提供打包下载

使用的时候应该采用XeLaTex(sample.tex)-BibTex(sample.bib)-XeLaTex(sample.tex)-XeLaTex(sample.tex)的顺序编译，以生成正确的参考文献目录和编号。

## 特别提醒

* PDF中故意留出一些空白页，这是为了让大章的起始页为偶数页。

* Mac系统请使用为MacTex(TexLive+Texshop)-->XeLatex，Windows系统请使用TexLive(TeXworks)-->XeLatex，其他环境下还未测试。

* 点击这里下载TexLive：[TexLive下载地址][TexLive] 点击这里下载MacTex：[MacTex下载地址][MacTex]

* 不同的平台需要加载的字体不同，请根据tex文件中的提示使用不同的参数。如果遇到字体无法加载的问题请确认系统装有相应字体。不同平台下请反注释相应的代码，例如在windows下，应为：
```latex
%% 如需Adobe字体请用（默认）
%\documentclass[adobefonts]{njuthesis}
%% MacOS系统请用
%\documentclass[macfonts]{njuthesis}
%% Windows系统请用
\documentclass[winfonts]{njuthesis}
%% Linux系统请用
%\documentclass[linuxfonts]{njuthesis}
```

[TexLive]: https://www.tug.org/texlive/
[MacTex]:https://tug.org/mactex/


## 相关项目

* [南京大学科技报告XeLaTeX模板][nju-report]
* [符合国家标准《GB/T 7714-2005 文后参考文献著录规则》的BibTeX样式文件][gbt7714-2005-bst]
* [中文书刊排版相关标准和规范][typesetting-standard]
* 

