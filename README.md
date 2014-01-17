tcemojifon パッケージ
=====================

LaTeX：ちょっと変わったVF

upLaTeX, dvipdfmx 専用。

インストール
------------

  * `*.sty` → `$TEXMF/tex/platex/tcemojifon`
  * `*.tfm` → `$TEXMF/fonts/tfm/public/tcemojifon`
  * `*.vf`  → `$TEXMF/fonts/vf/public/tcemojifon`
  * [Chromoji] の [GitHub レポジトリ] からアーカイブを入手し、
    その中の `images/` ディレクトリにある画像ファイルを
    `$TEXMF/tex/platex/tcemojifon/g` にコピーする。

[Chromoji]: (https://chrome.google.com/webstore/detail/chromoji-emoji-for-google/cahedbegdkagmcjfolhdlechbkeaieki)
[GitHub レポジトリ]: (https://github.com/RobJDavey/Chromoji)

使用法
------

    \usepackage{tcemojifon}

  * カラー絵文字のための和文ファミリ `tcemoj` が提供される。
  * `\tcemoji` 命令は和文ファミリを `tcemoj` に変更する。

--------------------
Takayuki YATO (aka. "ZR")
http://zrbabbler.sp.land.to/
