# Changelog

## v1.0.1 (2020-02-29)

次の誤りを修正しました。ご報告ありがとうございました。

| ページ数 | 修正内容 | issue |
| --- | --- | --- |
| 34, 61 など | コラムの注釈において番号がずれているのを修正しました。 | [#2](https://github.com/github-actions-up-and-running/contact/issues/2), [#4](https://github.com/github-actions-up-and-running/contact/issues/4) |
| 40 | 誤: ```- run: echo "${{ secrets.SECRET_TEXT }}"```<br />正: ```- run: echo "${{ secrets.SECRET_TOKEN }}"``` | [#1](https://github.com/github-actions-up-and-running/contact/issues/1) |
| 48 | 誤: ```ですが、 ワークフローを特定のスケジュールで定期実行したいとうケースもあります。```<br />正: ```ですが、 ワークフローを特定のスケジュールで定期実行したいケースもあります。``` | [#3](https://github.com/github-actions-up-and-running/contact/issues/3) |

## v1.0.0 (2020-02-27)

『GitHub Actions 実践入門』を公開しました。
