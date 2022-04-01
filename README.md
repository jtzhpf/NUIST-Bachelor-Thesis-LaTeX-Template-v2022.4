# 南京信息工程大学本科生毕业论文 LaTeX 模板2022年4月修订版，本次修订兼容Windows、macOS和Overleaf

版本：2022.4

这是一份南京信息工程大学本科生毕业论文 LaTeX 模板，请使用 XeLaTeX 编译。**提醒：本文档是非官方版**

本 Repository 是对 [NUIST_Bachelor_Thesis_LaTeX_Template](https://github.com/sakronos/NUIST_Bachelor_Thesis_LaTeX_Template.git) 进行修订。

非常感谢前辈们做出的工作！

本人是LaTeX小白，如有问题欢迎各位大佬们指出。

## 推荐使用环境
### Windows
1. Windows 10
2. TeX Live 2021
3. Visual Studio Code
4. package `gbt7714` v2.0 (2020-03-04) 以上 [GB/T 7714 BibTeX style 版本 v2.0 的重要修改](https://mirrors.concertpass.com/tex-archive/biblio/bibtex/contrib/gbt7714/gbt7714.pdf)

### macOS
1. macOS 10.13 ~ macOS 12
2. MacTeX
3. TeXStudio
4. package `gbt7714` v2.0 (2020-03-04) 以上 [GB/T 7714 BibTeX style 版本 v2.0 的重要修改](https://mirrors.concertpass.com/tex-archive/biblio/bibtex/contrib/gbt7714/gbt7714.pdf)

### Overleaf（强烈推荐）
[Overleaf](https://www.overleaf.com/) 是一个使用LaTeX进行多人协同编辑的平台，可以免费注册和使用，不用下载LaTeX软件，是最为著名的LaTeX在线协作系统。主要特色是有LaTeX插件，编辑功能十分完善，有实时预览（即编即看，无需手动编译）的功能。

使用方式：New Project -> Upload Project -> 上传.zip文件 -> 左上角Menu -> Settings -> Compiler 选择 XeLaTeX -> 直接编译就好啦


## 文件目录

```bash
├── NUIST本科毕业论文模版2022.4修订（Mac OS or Windows）  
│   ├── bibliography.bib                                # 使用 BibTeX 格式化的参考列表
│   ├── gbt7714-2005-numerical.bst                      # BibTeX 样式
│   ├── NUIST_thesis.pdf                                # 输出
│   ├── NUIST_thesis.tex                                # 使用范例
│   ├── nuist.cls                                       # 样式文件
│   ├── SimHei.ttf                                      # “黑体”字体文件
│   ├── SimSun.ttc                                      # “宋体”字体文件
│   ├── kaitiGB2312.ttf                                 # ”楷体“字体文件
│   ├── body                                            # 章节文件
│   ├── figs                                            # 图片文件夹
│   └── nuist_logo                                      # 封面所需图片
├── NUIST本科毕业论文模版2022.4修订（不用解压，overleaf直接导入）.zip
├── 南京信息工程大学本科生毕业论文（设计）撰写排版规范.doc
└── 毕业论文自查要求.docx
```

## 更新日志

> - version 2021.6
>
> > 1. 调整了几处字体大小
> > 2. 将图片、表格、公式设置为按章编号
> > 3. 添加了声明页
> > 4. 设置了页码
> > 5. 使用 GB/T 7714—2015 BibTeX Style 排版参考文献
> > 6. 限定模板使用的字体为 SimSun、SimHei、SimKai 和 Times New Roman
> > 7. 替换已弃用的宏包和命令
> > 8. 更新\thanking 命令，添加\forthsection 命令
> > 9. 将\linespread 设置为 1.335，以得到更接近 MS Word 下多倍行距 1.25 的效果
> > 10. 图片编号与图片标题间的分隔符设置为空格
>
> - version 2021.6.1
>
> > 1. 尝试修复参考文献和致谢页的跳转问题
>
> - 2021/10/28
>
> > 1. 修改 TODO，并补充使用 bibliography 的注意事项
> > 2. （被导师要求重新检查文档格式了……好久没用 LaTeX，有改出问题来的预感＞﹏＜）
>
> - 2022/01/10
>
> > 1. 修改 BibTeX 样式，参考文献中作者姓氏仅首字母大写
> > 2. 允许封面信息换行
> > 
> - 2022/04/01
> 
> > 1. 将字体打包进来，避免在 Mac OS 上出现缺失字体的问题
> > 2. 移植到 Overleaf 平台上

## 致谢

1. [南京信息工程大学本科学位论文模板](https://github.com/LirenW/NUIST_thesis_template_V2.0)
2. [南京信息工程大学 LaTeX 毕业论文模板 V3.1](https://latexstudio.net/index/details/index/mid/1524.html)
3. [NUIST_Bachelor_Thesis_LaTeX_Template](https://github.com/sakronos/NUIST_Bachelor_Thesis_LaTeX_Template.git)
