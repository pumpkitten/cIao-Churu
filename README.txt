キングダム覇道 親睦パズルソルバー v4
========================================

■ v4の変更
- 初回アクセス時に軍団員用パスコードを要求
- 正しいパスコードを入力すると、そのブラウザに認証状態を保存
- 2回目以降は自動でソルバーを表示
- 「この端末の認証を解除」ボタンを追加
- パスコード自体はHTMLへ平文保存せず、SHA-256ハッシュで照合
- v3までのパズル機能・C黄6修正・回転/反転禁止仕様を維持

■ 新しいGitHub Pages URL
https://pumpkitten.github.io/cIao-Churu/

■ GitHubでの変更手順
1. GitHubで現在の shinboku-puzzle-solver リポジトリを開く
2. Settings → General
3. Repository name を cIao-Churu に変更し、Rename を実行
4. リポジトリのトップへ戻る
5. 新しい index.html をアップロードして既存の index.html を置き換える
6. Commit changes
7. Settings → Pages で公開設定が main / (root) のままか確認
8. 数分待って新URLを開く

■ パスコード運用について
このロックはGitHub Pages上で動く「簡易ロック」です。
HTML/JavaScriptは利用者のブラウザへ配信されるため、本格的なサーバー認証の代わりにはなりません。
軍団内でURLを知っている一般利用者を制限する用途を想定しています。

■ 再認証
ブラウザのサイトデータを削除した場合、別ブラウザ・別端末で開いた場合、
または将来パスコードを変更した場合は再入力になります。
