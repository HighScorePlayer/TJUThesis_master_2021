# TJUThesis_master_2021
天大博士/硕士学位论文LaTeX模板，根据2021年版要求修改。

# 主要贡献
- 参考[tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)和[TJUThesisLatexTemplate](https://github.com/twtstudio/TJUThesisLatexTemplate), 依照《天津大学关于博士、硕士学位论文统一格式的规定（2021年修订）》中要求进行格式修改。
- 此外，鉴于[tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)只能先由latex编译成dvi在转换成pdf的形式较为繁琐，现已修改为由xelatex直接编译并生成pdf。因此，本模板可直接在Overleaf或TeXstudio中同时编辑和预览。
- 

:star:使用该模板所写的论文已通过盲审、查重和答辩，成功提交天津大学图书馆存档！（2021.12.24）

# 更新同步声明 
1. 参考用户[a171232886](https://github.com/HikariTJU)的更新说明。
2. 参照[]

# 使用方式
## Overleaf(不推荐)
* 需要网络连接。
* Overleaf免费版对文件大小有限制，难以满足学位论文的编写需求。
* 使用方法参考用户[a171232886](https://github.com/HikariTJU)中[README]->[使用方式]-[Overleaf]。

## Win/Linux+Vscode+TeXstudio(推荐)
* 本地编辑。
* 参考[如何用VScode快乐书写LaTex - Anakin的文章 - 知乎](https://zhuanlan.zhihu.com/p/337813181)以及相关关键字"vscode"和"latex"，大致流程如下：
   1. 安装和TeXstudio和vscode。
   2. vscode是一个文档编辑器，和vim无区别，在vscode中下载各种扩展：LaTeX Workshop、Code Spell Checker、latex-count、Markdown All in One (Markdown Preview Enhanced、Markdown Preview Github Styling、Markdown Preview Mermaid Support)，括号中的扩展可能部分包含进Markdown All in One中了，请补充相关扩展。
   3. 在settings.json中添加各类编译器以及项目类型包括pdf、XeLaTeX、luna、BibTex...的编译指令，修改编译流程(build with recipe)为XeLaTeX-Bibtex-XeLaTeX，并设置默认编译为上次使用的编译方式。
   4. 熟悉vscode命令快捷键，以及tex有关的code和pdf互定位、编译、查看pdf文档等操作的快捷键。
   5. 如果你熟悉vim，vscode可以比较无脑地支持vim和copilot。

# 格式改动
参照《天津大学关于博士、硕士学位论文统一格式的规定（2021年修订）》、《天津大学关于博士、硕士学位论文统一格式的规定（2021年修订20250605更新扉页版）》。

1. 封面页修改格式，添加评审表格，添加“一级学科”。
2. 独创性声明，“天津大学”改为楷体_GB2312。
3. 中文摘要，中文关键词与内容摘要间隔一行，无缩进左对齐书写。“关键词：”采用宋体四号字加粗。
4. 英文摘要，英文关键词与内容摘要间隔一行。
5. 页眉：奇数页为相应的章标题或无编号章标题；偶数页为“天津大学硕士学位论文”。

注：**本模板样式要求为学硕。** 根据2021年版规定，博士（专业型和学术型）、专硕的要求区别于学硕如下：
1. 博士的页眉为“天津大学博士学位论文”
2. 博士的扉页，如“一级学科”等，需要改变
3. 专硕的扉页，如“企业导师”等，需要改变
已添加到相关文档的注释中。

# 免责声明
使用本模板带来的一切不利影响和损失，本人均不负责。

# 致谢

前辈们做出了不可磨灭的艰辛探索：

- [tjuthesis](https://code.google.com/archive/p/tjuthesis/)
- [TJUThesisLatexTemplate](https://github.com/twtstudio/TJUThesisLatexTemplate)
- [tjuthesis_master_2016](https://github.com/jiangqideng/tjuthesis_master_2016)
- [TJUThesis_master_2021](https://github.com/a171232886/TJUThesis_master_2021)

# 后记
- 希望大家能指正本模板的错误，特别是格式错误，请提交到本项目[issue](https://github.com/a171232886/TJUThesis_master_2021/issues)中。
- 如果本模板对你有帮助，请给王同学[a171232886](https://github.com/a171232886/TJUThesis_master_2021)宝贵的Star和Fork。
- 会完善关于“化工/材料/化学系常在表格中插入复杂化学式”的功能。
