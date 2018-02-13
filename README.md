# language-mdbp
markdown grammer for MDBP with ATOM

Markdownのシンタックスハイライトを日本語文に合わせてカスタマイズしています。
とりあえず**太字**のときに、半角スペースを空けないと認識しない問題に対処しました。

## スニペット
GiHub Markdownのスニペットの他に以下を追加しました。※@とdivの間は空きません

| prefix | 意味|入るもの
|--   |-- |--
| cov | 章扉 | @ div:coverpage
| sec | 節見出し |@ div:secheader
| fig | 図版領域 |@ div:figure
| col | コラム |@ div:column
| de  | @ divの閉じタグ |@ divend
