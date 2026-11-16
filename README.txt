開運出目 v0.3 — GitHub Pages公開手順（Android向け）

【今回の変更】
・ホーム画面アイコンを🎯デザインに統一
・スマホでアップロードしやすいよう、画像を含む全ファイルを同じ階層に配置
・アプリの表示バージョンを v0.3 に更新
・PWA用マニフェストとオフラインキャッシュを同梱

【GitHubへアップロード】
1. GitHubで kaiun-deme リポジトリを開く
2. 「ファイルを追加」→「ファイルをアップロード」
3. このフォルダ内のファイル6個を選択してアップロード
   index.html / manifest.webmanifest / sw.js / icon-192.png / icon-512.png / README.txt
4. 「変更をコミット」を押す
※ ZIP自体ではなく、解凍後の6ファイルをアップロードします。
※ 今回は全ファイルを同じ階層にしたため、iconsフォルダを別に作る必要はありません。

【GitHub Pagesを有効にする】
1. リポジトリの「設定」→「Pages」
2. 「ソース」または「Build and deployment」で「Deploy from a branch」を選択
3. Branchを「main」、フォルダを「/(root)」にして保存
4. 公開URLが表示されたらChromeで開く
   URLの形： https://GitHubのユーザー名.github.io/kaiun-deme/
5. Chrome右上の「︙」→「アプリをインストール」または「ホーム画面に追加」

【注意】
・GitHub PagesはHTTPSで配信されます。PWAインストールは公開後に利用できます。
・アップロードとPages設定はGitHubアカウントへのログインが必要です。
・誕生日はブラウザ内に保存され、サーバーへ送信しません。端末・ブラウザ間では同期しません。
・このアプリは娯楽用の数字選び支援であり、レース結果の予測、的中、利益を保証しません。
