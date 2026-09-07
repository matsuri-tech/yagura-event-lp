# yagura-event-lp

YAGURAワークベンチが公開するイベントLPの集約リポジトリ。

イベントごとに `<slug>/index.html` を追加する形で運用する。公開URLは
`https://matsuri-tech.github.io/yagura-event-lp/<slug>/`。

GitHub Pages は main ブランチ / ルート（legacy）で有効化済み。`<slug>` ディレクトリを
追加・更新すると自動でビルドされる。

書き込みは YAGURA のサーバーが `Contents: write` 権限のトークンで行う。リポジトリ作成や
Pages の有効化は行わない設計。
