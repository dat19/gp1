# UnityのプロジェクトをGitで管理するように設定して、GitHubにPublishする手順

- GitHub Desktop を起動する
- Fileメニューから、Optionsをクリック
- GitHub.comがサインイン済みの時は、Sign outをクリックする
- Sign in ボタンをクリックして、GitHubアカウントでサインイン
- FileメニューからNew Repository(リポジトリー)
- Local pathのChooseボタンをクリック
- ドキュメント > 名前のフォルダー から、登録したいUnityのプロジェクトフォルダーを開いて、フォルダーの選択をクリック
- Local pathの最後のフォルダー名を選択して、切り取って、Name欄に貼り付け
- Initialize this repository with a README にチェック
- Git ignore欄をクリックして、unityと入力して選択
- Create repositoryボタンをクリック
- 右上のPublish repositoryボタンをクリック
- Keep this code private はチェックしたままにする
- Publish repositoryボタンをクリック

## 提出用に、教員のアカウントをチームに入れておく
そのままだと提出しても教員から見えないので、以下の手順でリポジトリーに教員を追加する。

- Chromeのシークレットウィンドウを起動
- github.com を開く
- サインインする
- 作成したリポジトリーを開く
- 右の方にある*Settings*をクリック
- 左の方にある*Collaborators & teams*をクリック
- パスワードを入力
- Collaborators欄のテキストボックスに`tanakaedu`と入力して、表示される`tanakaedu Yu Tanaka*を選択したら、*Add collaborator*ボタンをクリック

以上で設定完了です。


