Aetherlight — FF14 SS加工スタジオ（ブルーム / ソフトフォーカス修正版）

GitHub Pages で公開する方法

1. このZIPを解凍してください。ZIPそのものをGitHubに置いてもWebサイトにはなりません。
2. GitHubでリポジトリを開き、直下（トップ階層）の index.html を今回の index.html に置き換えてください。
   Add file → Upload files → Commit changes
3. Settings → Pages → Build and deployment で Source を Deploy from a branch にします。
4. Branch を main、フォルダを / (root) に設定して Save します。
5. 公開URL（通常 https://ユーザー名.github.io/リポジトリ名/ ）で開きます。
   公開に数分かかる場合があります。
6. 古い画面が出る場合は、URLの末尾に ?v=3 を付けて再読込してください。

更新内容
- ブルーム：明るい部分の周囲に光が広がる処理を改修しました。
- ソフトフォーカス：画像全体が滑らかにぼける処理を改修しました。
- 一部環境で対応状況が異なる Canvas filter を使わない実装にしました。
- フィルター名は、オリジナル / ナチュラル / ブルー / ピンク / ダーク / ウォーム / レトロのままです。

※ FF14公式とは提携していません。
※ 写真はサーバーにアップロードせず、ブラウザ内で処理します。
