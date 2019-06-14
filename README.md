# ゲームプログラミング1年生
2019年度 デジタルアーツ東京 ゲームプログラミング1年生用リポジトリー。

- [シラバス](syllabus.md)

# 参考URL
- [日本語から変数や関数名の候補を示してくれるサービス](https://codic.jp/)

# 9回目(6/21)
## 前回の復習の提出結果

## 予定
- 状態遷移　続き
  - なぜクリアしてしまうか？から
  - クリアの作成
  - ゲームオーバーの作成
  - 種類を増やす


# 8回目(6/14)
## 前回の復習の提出結果(出席16名)
- 提出(13名)
- パーフェクト(〇が5個以上ならOK) (4名)

## 前回の振り返りと復習(前回と全く同じ)
- fukusyu0614の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
  - **2つ目のプロジェクトフォルダーを選択すると提出失敗になるので注意！！**
- 以下を設定
  - ラベル(Label)を1つ
  - タイマー(Timer)を設定して、動くようにする
  - classの宣言の直下に、以下を追加

```cs
int vx = -10;
int vy = -10;
```

  - timer1をダブルクリックして、以下のプログラムを追加

```cs
			label1.Left += vx;
			label1.Top += vy;
```

- ラベルが、ウィンドウの端で跳ね返るようにする
- ラベルにマウスカーソルが重なったら、タイマーを停止(`timer1.Enabled = False;`)にする
- 完成したらPush

## 予定
- [コントロールをプログラムで追加する](https://github.com/dat19/csharp-manual/blob/master/15.md)
  - 新規にensyu0614を作って、ラベルをスクリプトから作成
- たくさん動かす仕上げ
- すべてをfor文に対応させる
- たくさんオブジェクトを出してみる
  - [作業手順](https://docs.google.com/document/d/1tLiMFh_ptiwREACelAh5jdesD7nUNs88EbSazum6q68/)
- 状態遷移 / 総合復習：沢山のラベルを表示して全て取るゲームの開発


# 7回目(6/7)

## 前回の課題
- 講義の開始までに、前回のfukusyu0531の最新版を、GitHubにCommitして、Pushしてください

## 前回の復習の提出結果(出席10名)
- 提出(9名)
- パーフェクト(5名)

## 前回の振り返りと復習
- fukusyu0607の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
  - **2つ目のプロジェクトフォルダーを選択すると提出失敗になるので注意！！**
- 以下を設定
  - ラベル(Label)を1つ
  - タイマー(Timer)を設定して、動くようにする
  - classの宣言の直下に、以下を追加

```cs
int vx = -10;
int vy = -10;
```

  - timer1をダブルクリックして、以下のプログラムを追加

```cs
			label1.Left += vx;
			label1.Top += vy;
```

- ラベルが、ウィンドウの端で跳ね返るようにする
- ラベルにマウスカーソルが重なったら、タイマーを停止(`timer1.Enabled = False;`)にする
- 完成したらPush

## 内容
- ラベルとマウスカーソルが重なる条件の作り方
- [乱数](https://github.com/dat19/csharp-manual/blob/master/12.md)
- [配列](https://github.com/dat19/csharp-manual/blob/master/13.md)
  - [開始プロジェクト](https://github.com/tanakaedu/fukusyu0607)
- [繰り返し](https://github.com/dat19/csharp-manual/blob/master/14.md)

# 6回目(5/31)
## 前回の提出結果(出席15名)
- 提出(15名)
- パーフェクト(10名)

## 前回の復習
- fukusyu0531の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
  - **2つ目のプロジェクトフォルダーを選択すると提出失敗になるので注意！！**
- 以下を設定
  - ラベル(Label)を1つ
  - タイマー(Timer)を設定して、動くようにする
  - classの宣言の直下に、以下を追加

```cs
int vx = -10;
int vy = -10;
```

  - timer1をダブルクリックして、以下のプログラムを追加

```cs
			label1.Left += vx;
			label1.Top += vy;
```

- ラベルが、ウィンドウの端で跳ね返るようにする
- 完成したらPush

## 予定
- [分岐 続きから](https://github.com/dat19/csharp-manual/blob/master/08.md)
  - [おまけ switch文](https://github.com/dat19/csharp-manual/blob/master/09.md)
- [マウス入力](https://github.com/dat19/csharp-manual/blob/master/10.md)
- [分岐2](https://github.com/dat19/csharp-manual/blob/master/11.md)


# 5回目(5/24)
## 前回の提出結果(出席17名)
- 提出(11名)
- 1カ所間違い(2名)
- パーフェクト(0名)

## 前回の復習
- fukusyu0524の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
  - **2つ目のプロジェクトフォルダーを選択すると提出失敗になるので注意！！**
- 以下を設定
  - ラベル(Label)を1つ
  - ボタン(Button)を4つ作って十字に配置
  - タイマー(Timer)を設定して、動くようにする
  - classの宣言の直下に、以下を追加

```cs
int vx = 0;
int vy = 0;
```

  - timer1をダブルクリックして、以下のプログラムを追加

```cs
			label1.Left += vx;
			label1.Top += vy;
```

- ボタンを押すと、ラベルが動くようにする
- 完成したらPush

## 予定
- [分岐(1) 跳ね返り処理](https://github.com/dat19/csharp-manual/blob/master/08.md)
- [マウス操作](https://github.com/dat19/csharp-manual/blob/master/10.md)
- [ベクトルについて 続き](https://docs.google.com/document/d/1bptMOCYRdX4_IP8uhToeYloXgRh7C9v-nC1yLI8EFSE/)

# 4回目(5/17)
## Google Chromeの拡張機能Click&Cleanを削除する
- Chromeアイコンを右クリックして、Google Chromeを選択して、通常のChromeを起動
- アドレスバーに chrome://extensions/ を入力
- Click&Cleanの削除ボタンをクリック(なければすでに削除済みなので何もしなくてOK)
- Chromeを閉じる

## 前回の復習
- fukusyu0517の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
- 以下を設定
  - ラベル(Label)を1つ
  - ボタン(Button)を4つ作って十字に配置
  - テキストボックス(TextBox)を2つ作って、両方とも`Text`プロパティーに`0`を設定
  - タイマー(Timer)を設定して、動くようにする
  - timer1をダブルクリックして、以下のプログラムを追加

```cs
			label1.Left += int.Parse(textBox1.Text);
			label1.Top += int.Parse(textBox2.Text);
```

- ボタンを押すと、ラベルが動くようにする
- 完成したらPush

## 今回の内容
- [変数](https://github.com/dat19/csharp-manual/blob/master/07.md)
  - TextBoxを不要にする
- 同様のことをUnityでやってみる
  - [ベクトルについて](https://docs.google.com/document/d/1bptMOCYRdX4_IP8uhToeYloXgRh7C9v-nC1yLI8EFSE/)

## その他
- 時間が余ったらタイピング練習。以下にスコアを報告せよ
  - [報告用のスプレッドシート](https://docs.google.com/spreadsheets/d/13IyWguSAEqxOa6fkID_B7BcLyzoe_1Lc3lRZKlJbXLk/edit?usp=sharing)


# 3回目(5/10)
## 水曜日のensyu0508リポジトリーの共有リンクを教えてください
- [書き込み先](https://docs.google.com/spreadsheets/d/1Ky6bU27vJy_jl4-Yu3UiaHj-ZuHUPcQHXOVgjsRn-Mc/)

## 前回の課題の総評
- パーフェクト：二人
- ボタン2つ：一人
- ボタン1つ：二人
- 未提出：四人
- 提出はできていて、ボタンの実装なし：上記以外


## 前回の復習
- 調べ方：実演
- fukusyu0510の名前でプロジェクト作成
- [GitHubに登録](https://github.com/dat19/gp1/blob/master/vs-github-entry.md)して、Publish
- ボタンを3つ作って、それぞれ違う動きをさせる
- 完成したらPush
- **パーフェクトやボタン2つの人は、担当列の人のサポートをしてください**

## 講義ノート
- [書く教科書 5から](https://github.com/dat19/csharp-manual/blob/master/05.md)、進められれば6まで
- [Unityでの物の動かし方](https://docs.google.com/document/d/1Su0trfKxB2iLfGdxt1s7pJr76NFwqwdw-pbDhaCrtvE/)

# 2回目(4/26)
## 講義ノート
- [書く教科書](https://github.com/dat19/csharp-manual)

## プロパティを調べる
- BackColor
- Enabled
- Font
- ForeColor
- Location
- Size
- Text
- TextAlign
- Visible

## 予定
- Visual Studioの基本操作
- プロパティの確認
- [タイピング練習](https://www.e-typing.ne.jp/)
  - 結果をこちらに報告

## 演習
- 新規にプロジェクト`ensyu0426`を作成して、以下について実装せよ
  - Gitでの管理を開始して、GitHubにPublishする
    - GitHub Desktop をダブルクリックして起動
    - Fileメニューから、Optionsをクリック
    - GitHub.comがサインイン済みの時は、Sign outをクリックする
    - Sign in ボタンをクリックして、GitHubアカウントでサインイン
    - FileメニューからNew Repository(リポジトリー)
    - Local pathのChooseボタンをクリック
    - ドキュメント > 名前のフォルダー > ensyu0426を開いて、フォルダーの選択をクリック
    - Local pathの最後のフォルダー名を選択して、切り取って、Name欄に貼り付け
    - Initialize this repository with a README にチェック
    - Git ignore欄をクリックして、`vi`と入力して、VisualStudioを選択
    - Create repositoryボタンをクリック
    - 右上のPublish repositoryボタンをクリック
    - Keep this code private のチェックを外す
    - Publish repositoryボタンをクリック
  - ボタンを3つ作成する
  - 作成した3つのボタンそれぞれに、押すと「文字が変わる」「場所が移動する」「消える」以外の変化をさせるプログラムを作成せよ
  - プロジェクトをGitHubに登録する
  - コミット＆プッシュ(これで提出になる)

# 1回目(4/19)
## 講義ノート
- https://docs.google.com/document/d/1WEDoUQOGek-jf9WwRDZmWhnGAj3DT1KxGFj6GRGQpkU/

## 予定
- ガイダンス - [シラバス](syllabus.md)の確認
- Visual Studioを試す
  - 起動 / プロジェクト作成 / ボタンの配置 / メッセージの表示
- Unityを試す
  - アカウント作成 / 起動 / プロジェクト作成 / オブジェクトの作成 / 着色 / メッセージの表示 / マウス操作
- 独習
  - [Paizaラーニング C#](https://paiza.jp/works/cs/primer)
    - アカウントをGitHubで登録する
  - [ドットインストール Unity入門(2018.3.4f1)](https://dotinstall.com/lessons/basic_unity_v2)
とUnityを触る / 学習サイトについて
- [タイピング練習](https://www.e-typing.ne.jp/)

## 演習
- タイピングの結果を報告する
  - [報告用のスプレッドシート](https://docs.google.com/spreadsheets/d/13IyWguSAEqxOa6fkID_B7BcLyzoe_1Lc3lRZKlJbXLk/edit?usp=sharing)
