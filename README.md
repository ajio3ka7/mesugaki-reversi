# メスガキリバーシ

ブラウザで遊べるリバーシです。`index.html` 1ファイルで動きます(サーバー・ビルド不要)。

## GitHub Pages で公開する手順
1. GitHub で新しいリポジトリを作る(例: `mesugaki-reversi`、Public)。
2. このフォルダの `index.html` と `README.md` をリポジトリにアップロードする。
   - ブラウザから: リポジトリのページで「Add file」→「Upload files」→ ドラッグして「Commit changes」。
3. リポジトリの「Settings」→「Pages」を開く。
4. 「Build and deployment」の Source を **Deploy from a branch** にし、Branch を **main** / **(root)** にして Save。
5. 1〜数分待つと、次のURLで公開される。
   `https://<ユーザー名>.github.io/<リポジトリ名>/`

## 更新するとき
`index.html` を上書きアップロード(commit)すれば、数分で反映されます。

## ゲームの内容を変えるとき
- セリフ: `index.html` 内の `L`(通常)と `END`(勝敗)のオブジェクト
- 顔: `FACE_PIX`(ドット絵画像をbase64で埋め込み)
- 強さ・判定の基準: `READ`、`react()`、`onPlayer()`

## 注意
- 顔の画像はAI生成です。公開前に、使った画像生成サービスの利用規約(公開・商用利用の可否、表記)を確認してください。
