# tex_tutorial

## 生成方法
### ex1について
texファイル→dviファイル
```bash
platex ex1.tex
```

dviファイル→pdfファイル
```bash
dvipdfmx ex1.dvi
```

### ex2について
texファイル→pdfファイル
```bash
ptex2pdf -l ex1.tex
```
