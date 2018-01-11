# はじめに

slisの日本語の修論のテンプレです．
背表紙，表紙，抄録も含まれます．
2018年1月に提出したときはOKだったのですが，それ以降に正しいかは保証できませんが，おそらく正しいと思います．
Macでしか動作確認していません．

---

# ファイルの概要

- `.latexmkrc`: Latexmk の設定ファイル．
- `title.tex`: ファイルにはる表紙．これは別に印刷することになる．
- `binding.tex`: 表題紙
- `paper.tex`: 修論の本体．`title.tex`の扱いに注意すること
- `paper.pdf`: `paper.tex`から生成されるPDF
- `reference.bib`: 文献情報をここにいれる
- `spine.docx`: 背表紙
- `template_abstract.docx`: 抄録のテンプレ．フォーマットは中に書いてあります．

---

# 変換コマンド

```sh
$ latexmk -pvc paper.tex
```

日本語文献引くときはよしなに変えて下さい．
