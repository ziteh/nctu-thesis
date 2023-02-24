# 虎尾科大碩博士論文 XeLaTeX 模版

這個模版的前身是 [shaform](http://github.com/shaform) 的 [臺灣大學碩博士論文 XeLaTeX 模版](https://github.com/shaform/ntu-thesis) 與 [tzhuan](http://github.com/tzhuan) 的
[臺灣大學碩博士論文 XeLaTeX 模板](https://github.com/tzhuan/ntu-thesis)。
同時也整合了一些 [qcl](https://github.com/qcl) 針對
[qcl-master-thesis](https://github.com/qcl/qcl-master-thesis) 所做的修改。
其中，他也參考了[台大碩博士論文 LaTeX 範本](https://code.google.com/p/ntu-thesis-latex-template/)。
再來則由 [Po-haoHuang](https://github.com/Po-haoHuang) 在交通大學撰寫論文期間又做了些許更動，使其成為適合[交通大學的模板](https://github.com/Po-haoHuang/nctu-thesis)。
最後由 [ZiTe](https://github.com/ziteh) 撰寫碩士論文時修改成適合虎尾科大的格式。

## 用法

本模板可以使用 [Overleaf](https://www.overleaf.com) 線上服務進行編譯，對於不想自己處理 LaTeX 環境的人很方便。這也是我個人主要的使用方式。

想要在本機編譯的話，可以考慮 [TeX Live](https://www.tug.org/texlive/)+[TeX studio](https://www.texstudio.org/) 的組合，[VS Code](https://code.visualstudio.com/) 上也有一些 LaTeX 的相關插件，或使用 [`Makefile`](./Makefile)（未實際測試過）。

:heavy_exclamation_mark: 無論使用哪一種方式，編譯器記得要選用 ***XeLaTeX***。

## 檔案結構

大致說明一下各個檔案及資料夾的功能：

- [`thesis.tex`](./thesis.tex)：主編譯檔。
- `nfuthesis.cls`：LaTeX class 檔案。定義了此模板中的各種風格設定。
- `nfuvars.tex`：各資訊變數。
- `thesis.bib`：參考文獻資料。
- `abstract.tex`：摘要內容。
- `acknowledgements.tex`：誌謝內容。
- `extended_abstract.tex`：英文論文大綱內容。
- `chapers/`：各章節內容。
- `tables/`：表格。
- `figures/`：圖片。
- `images/`：圖片檔。
- `pdfs/`：PDF 檔。

### 下載

您可以用以下任一種方式下載此模板：
- 點擊右上角的「Code」後點擊「Download ZIP」。
- 使用 git clone 指令。

## 參考

這裡列出一些可以參考的文章或實用的工具，對於使用 LaTeX 時很有幫助。

### 符號清單
1. [常用 LaTeX 數學符號指令](https://hackmd.io/@CynthiaChuang/Basic-LaTeX-Commands)
1. [List of LaTeX mathematical symbols](https://oeis.org/wiki/List_of_LaTeX_mathematical_symbols)
1. [Symbol table](https://www.overleaf.com/latex/templates/symbol-table/fhqmttqvrnhk)

### 數學
1. [編寫數學公式](https://en.wikibooks.org/wiki/LaTeX/Mathematics)

### 視覺化公式編輯器
1. [公式編輯器](https://www.latexlive.com/##)
1. [方程式編輯器](https://editor.codecogs.com/)
1. [手寫辨識](https://webdemo.myscript.com/views/math/index.html)

### 參考文獻管理
1. [Mendeley](https://www.mendeley.com/search/)
1. [Zotero](https://www.zotero.org/)
1. [EndNote](https://endnote.com/)

## 備註

- shaform 版的 [wiki](https://github.com/shaform/ntu-thesis/wiki)
- 論文格式參考並根據「國立虎尾科技大學學位論文格式規範」（最後修訂為 110 年 10 月 19 日）之規定。
