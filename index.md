## Alex Wang's Main Page

You can use the [editor on GitHub](https://github.com/AlexWang0296/Pages-Demo/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
### Latex 文件比较
工具： latexdiff
命令： 不对数学公式进行标注，不对 ection 和 subsection 进行比较，可以消除绝大多编译数错误
```latex
latexdiff  --math-markup=0  --exclude-textcmd="section,subsection"  origin.tex new.tex > diff2.tex
```
### Publishing 发表

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/AlexWang0296/Pages-Demo/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
