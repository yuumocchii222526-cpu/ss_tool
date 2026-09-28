FF14 SS Editor - シンプル版

このZIPは、フォルダ分けなしで使えるようにしています。
GitHubには ZIPそのものではなく、中のファイルをアップロードしてください。

入っているもの
- index.html  ← アプリ本体。CSSとJavaScriptも全部この1ファイル内です
- README.txt  ← この説明

GitHub Pagesで公開する手順
1. GitHubで新しいリポジトリを作る
2. Add file → Upload files
3. index.html と README.txt をそのままアップロード
4. Commit changes
5. Settings → Pages
6. Source を「Deploy from a branch」にする
7. Branch を main / (root) にして Save
8. 少し待つと公開URLが表示されます

注意
- 画像ファイルはブラウザ内で処理します。
- 「人物を自動保護」だけは MediaPipe のプログラムと人物分離モデルを外部配信元から読み込みます。
- そのため、人物自動保護の初回利用時にはインターネット接続が必要です。
- このシンプル版は GitHub Actions / npm / Vite / srcフォルダ / publicフォルダ不要です。
