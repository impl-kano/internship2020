# 株式会社インプル インターンシップ2020


## 実施項目（予定）

- 会社説明
- インターンシップ概要説明
- 自己紹介
- ツール類の導入（VSCode, チャットワーク...etc）
- Gitの基本操作学習

- JS基礎学習課題
  - HTML&CSS （Flexboxを使用したスタイリング）
  - JavaScriptのArrayメソッドを用いたプログラミング問題
  - Arrayメソッドを応用したDOMの操作

- React入門
  - 目標: JS基礎課題で行ったDOM操作と同じ物をReactで実装することで、仮想DOMを理解する

- Reactについて概要説明
  - コンポーネント指向について
  - 仮想DOMについて
  - Reactシンタックスについて
  - モジュールのインポート・エクスポート

- React プロジェクトの作成
  - `npx create react app`

- JSXのレンダリングと更新
  - useStateを使った状態管理
  - Propsを使ったコンポーネント同士のやり取り
  - 配列をmapしてリストをレンダリングする
  - オブジェクト配列をマップしてレンダリングする
  - フォームに入力される値をStateにバインドする

- useEffectとライフサイクル
  - コールバック関数について
  - コンポーネントのライフサイクル

- コンポーネントの切り出しと再利用
  - ファイル分割
  - propsを受け取る

- 条件付きレンダリングを用いた擬似ログイン
  - Stateの状態によってDOMを出しわける
  - 三項演算子による場合わけ
  - ショートサーキットによる場合わけ
  
- 通信・同期処理・非同期処理について
  - APIからデータをフェッチして画面に表示させる
  - コールスタックとイベントループについて
  - Promiseについて
  - Async/ Awaitについて

- ReactNative入門: Git操作とともに~
  - 環境構築（つまりやすいので必ず公式ドキュメント通り行う）

- JSXでtouchable なボタンを作成して、developブランチにpushする
- ボタンをクリックしたらモーダルウィンドウが表示されるように修正して、developブランチにpushする

- 画面遷移の実装
  - ReactNavigationを使用して画面遷移を実装する
  
- Reduxの導入
  - Reduxとは
  - actionの概要
  - Reducerの概要
  - StoreとProviderを作る
  
- ログイン状態をReduxで管理する
  - ログイン状態でしか見られない画面（NavigationStack）を作成する

- UIの模写
  - https://dribbble.com/ から好きなモバイルデザインを選択し、似たような画面をReactNativeで作ってみる
  - コンポーネントを分ける
  - RNのウィジェットを色々使って慣れる
  - インラインCSS
  - 画像のインポート-> 表示
  - FontAwesomeを読み込んでアイコン表示
  - 水平スクロール  ...など

  


---

## ウォーミングアップ: HTML CSS JavaScript のキホン


### 🍼 準備

- VSCodeをインストール https://azure.microsoft.com/ja-jp/products/visual-studio-code/
- VSCodeの拡張機能（Live Server）をインストール https://www.mitsue.co.jp/knowledge/blog/frontend/201810/02_1329.html
- Chromeをインストール https://www.google.com/intl/ja_jp/chrome/
  


### 🦒 ウォーミングアップ1 HTML&CSS


Flexboxを使用したレイアウトを、それぞれ作って見てください。

Flexboxは「React Native」のデザインに必須である他、Webアプリケーションのレスポンシブ対応に広く用いられています。

- デザインが６枚あります。1人1枚選び、Flexboxで再現してください。
- 画像を最低１枚使用してください。（どんな画像でもOK）
- 自分のデザインが終わったら、他の人を手伝ってください。


### 🐍 JavaScriptの配列操作

配列に入ったデータを画面に描画したり、APIから取得したデータから必要な内容を取り出したりなど、配列の操作は非常に重要です。

いくつか問題を用意しましたので、解いてください。


### 🐘 ウォーミングアップ3 JavaScriptのDOM操作

JavaScriptを使用したDOM（HTMLの構造）の操作をしてみましょう。
ウォーミングアップ2の配列操作を応用してみてください。

- ボタンを押したら、画面上にリストが追加されるよう実装してください。
- リストは、`items`配列で管理してください。

💬ヒント: 
配列を`map`して、Element オブジェクトの`innerHTML`プロパティでDOMを挿入します。



## Git入門


## React入門: 仮想DOMに慣れる

https://qiita.com/impl_s/private/545a7725bfc4b35d74a1


##  １時間でuseStateからReduxまで理解する

https://qiita.com/impl_s/private/aefc6574d1262e6e67bf


## 非同期処理のチュートリアル

https://qiita.com/impl_s/items/8ffbe865b8c53a75cfe3
