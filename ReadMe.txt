修改setup/package.tex文件
把最后一行 \usepackage[dvipdfm, unicode, 
修改成 \usepackage[unicode,

把hnumain.tex文件中
第二行 \def\usewhat{dvipdfmx} 删除。
在第一行前增加一行 % !TEX program = pdflatex