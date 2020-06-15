# Changelog

## v1.2.0 (2020-06-15)

次の内容を更新しました。

| ページ数 | 更新内容 |
| --- | --- |
| 41 | organization 単位の秘密情報について追記 |
| 66〜 | actions/cache アクションを v2 に更新 |
| 141〜 | Docker 公式アクションを使うように修正 |

## v1.1.0 (2020-05-09)

次の内容を更新しました。

| ページ数 | 更新内容 |
| --- | --- |
| 28 | runs-on で指定できる値に `windows-2019`, `windows-2016`, `macos-10.15` を追記 |
| 34 | shell で python を指定したときの Python のバージョンを修正 |
| 35 | ジョブの `continue-on-error` を追記 |
| 36 | ワークフローやジョブのデフォルト設定を追記 |
| 39 | デフォルトの環境変数に `CI` を追記 |
| 46 | ジョブ間のアウトプットの受け渡しを追記 |
| 49 | `jobs.<job_id>.strategy.matrix.include` で新しい組み合わせを追加できるようになったことを追記 |
| 57 | `fromJson` 関数を追記 |
| 74〜 | `upload-artifact`, `download-artifact` アクションを v2 に更新 |
| 87〜 | セルフホストランナーが organization に追加できるようになったこと、カスタムラベルに対応したことを追記 |
| 96 | セルフホストランナーが 30 日以上 GitHub へ接続がないと削除されることを追記 |
| 97 | Enterprise Cloud で許可 IP アドレスを設定した場合を追記 |
| 99 | REST API が GA になったためベータの記述を削除 |
| 103 | 利用できるアクションの制御を追記 |

## v1.0.2 (2020-03-05)

次の誤りを修正しました。ご報告ありがとうございました。

| ページ数 | 修正内容 | issue |
| --- | --- | --- |
| 108 | 誤: `Ocktokit`<br />正: `Octokit` | [#6](https://github.com/github-actions-up-and-running/contact/issues/6) |
| 111〜 | TypeScript アクションの作成を書かれているとおりにすすめるとエラーとなるところを修正しました。 | [#7](https://github.com/github-actions-up-and-running/contact/issues/7) |

## v1.0.1 (2020-02-29)

次の誤りを修正しました。ご報告ありがとうございました。

| ページ数 | 修正内容 | issue |
| --- | --- | --- |
| 34, 61 など | コラムの注釈において番号がずれているのを修正しました。 | [#2](https://github.com/github-actions-up-and-running/contact/issues/2), [#4](https://github.com/github-actions-up-and-running/contact/issues/4) |
| 40 | 誤: ```- run: echo "${{ secrets.SECRET_TEXT }}"```<br />正: ```- run: echo "${{ secrets.SECRET_TOKEN }}"``` | [#1](https://github.com/github-actions-up-and-running/contact/issues/1) |
| 48 | 誤: ```ですが、 ワークフローを特定のスケジュールで定期実行したいとうケースもあります。```<br />正: ```ですが、 ワークフローを特定のスケジュールで定期実行したいケースもあります。``` | [#3](https://github.com/github-actions-up-and-running/contact/issues/3) |

## v1.0.0 (2020-02-27)

『GitHub Actions 実践入門』を公開しました。
