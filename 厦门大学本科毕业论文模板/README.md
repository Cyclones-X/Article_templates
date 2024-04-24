! 把原来的模板按照学校排版要求改了一下

！页眉的标题要在xmuthesis.cis文件里修改

! 文中使用了bibtex进行引用，如果在本地vscode内编辑需要在setting.json中配置好
  "pdflatex-bibtex-pdflatex\*2" (纯英文的文章)
  或
  "xelatex-bibtex-xelatex\*2" (带有中文的文章) 
  这两个编译链并且使用对应的编译链进行编译，否则会报错或引用无效。
