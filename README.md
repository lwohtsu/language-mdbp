# language-mdbp
markdown grammer for MDBP with ATOM

Markdownのシンタックスハイライトを日本語文に合わせてカスタマイズしています。

## 変更点

- **太字**のときに、半角スペースを空けないと認識しない問題に対処しました。
- @div:～@divendの範囲の色が変わるよう指定（entity.name.section.gfm）。使用しているシンタックステーマによって変化します。

## スニペット
GiHub Markdownのスニペットの他に以下を追加しました。

| prefix | 意味|入るもの |
|--   |-- |-- |
| cov | 章扉 | @div:coverpage|
| sec | 節見出し |@div:secheader|
| fig | 図版領域 |@div:figure|
| col | コラム |@div:column|
| de  | @divの閉じタグ |@divend|
