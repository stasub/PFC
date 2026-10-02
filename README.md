# PFCノート

朝・昼・晩・間食ごとに食べたものとPFCを記録する個人用PWAです。

## GitHub Pagesで公開する

1. GitHubで新しいリポジトリを作る（例: `pfc-note`）
2. このフォルダ内のファイルをすべてリポジトリ直下にアップロードする
3. リポジトリの **Settings → Pages** を開く
4. **Build and deployment → Source** で **Deploy from a branch** を選ぶ
5. Branchを **main / (root)** にして保存する
6. 表示されたGitHub PagesのURLをSafariで開く
7. Safariの共有メニュー → **ホーム画面に追加** → **ウェブアプリとして開く** をオン → 追加

## データ

記録は端末のブラウザのlocalStorageに保存されます。
「目標」タブの「バックアップを書き出す」でJSONバックアップを保存できます。
「バックアップから復元」でそのJSONを読み戻せます。
