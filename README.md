# midterm-sty
修士論文中間発表要旨のための.styファイル

# 動作条件
+ TeXLive 2018 + LuaLaTeX
+ Noto Sans/Serif CJK JP

Noto Sans CJK JP および Noto Serif CJK JPは、
https://www.google.com/get/noto/
からダウンロードできます。

# 使いかた
本.styファイルはLuaLaTeXで動作することを想定しています。

```latexmk -pdflua my-midterm-paper.tex```

でPDFが生成されます。

TeXLive 2018以前での動作は確認できておりません。

2018/10/18追記
TexLive2018以前ではlatexmkにpdfluaのオプションがありません。
BasicTexなどの簡易版ではパッケージ不足でエラーとなります。


