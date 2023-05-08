# Chat-GPT Web 拡張機能

OpenAI チャット拡張機能は、ユーザーが OpenAI のチャット API を使用して AI を利用した応答を生成できるようにするブラウザー拡張機能です。任意の Web ページでテキストを選択し、右クリックしてコンテキスト メニューから \[OpenAI で応答を生成] を選択すると、アクティブ化できます。次に、拡張機能は、選択されたテキストを OpenAI チャット API に送信します。これにより、ポップアップ ウィンドウに表示される応答が生成されます。

## 翻訳

| 🇺🇸            | 🇨🇳                      | 🇹🇼                    | 🇮🇳                   | 🇫🇷                  | 🇦🇪                | 🇩🇪                 | 🇯🇵                | 🇪🇸                  |
| --------------- | ------------------------- | ----------------------- | ---------------------- | --------------------- | ------------------- | -------------------- | ------------------- | --------------------- |
| [英語](README.md) | [簡体字中国語](README.zh-CN.md) | [繁体中文](README.zh-TW.md) | [ヒンディー語](README.hi.md) | [フランス語](README.fr.md) | [アラブ](README.ar.md) | [ドイツ人](README.de.md) | [日本語](README.ja.md) | [スペイン語](README.es.md) |

## スクリーンショット

![App Screenshot](https://cdn.discordapp.com/attachments/1008195045960204349/1099103637608878090/New_Website_Blue_Mockup_Instagram_-_Laptop.gif)

## 特徴

-   OpenAI のチャット API を使用して応答を生成します
-   簡単にアクセスできるように Chrome コンテキスト メニューと統合
-   生成されたレスポンスをクリップボードにコピーしてすばやく貼り付け
-   簡単なインストールプロセス
-   詳細なドキュメントと FAQ
-   GitHub でのオープンソース

## ドキュメンテーション

-   の OpenAI API ページに移動します。[RapidAPI](https://rapidapi.com/openai-api-openai-api-default/api/openai80/)。
-   「サブスクライブしてテスト」ボタンをクリックします。
-   無料の「Free」プランを選択し、「Subscribe」をクリック。
-   指示に従って RapidAPI にサインアップするか、すでにアカウントを持っている場合はログインします。
-   OpenAI API サービス ページで、必要な要求ヘッダーのリストで -- 「X-RapidAPI-Key」セクションを探します。
-   Chrome 拡張機能の background.js ファイルの「X-RapidAPI-Key」セクションに RapidAPI API キーをコピーします。

## インストール

-   Github リポジトリから拡張機能のソース コードをダウンロードします。
-   ダウンロードしたフォルダを解凍します。
-   Google Chrome を開き、\[拡張機能] ページに移動します。これを行うには、アドレス バーに「chrome://extensions/」と入力するか、Chrome の右上隅にある 3 つのドットをクリックして、\[その他のツール]、\[拡張機能] の順に選択します。
-   「拡張機能」ページに移動したら、右上隅にあるスイッチを切り替えて、開発者モードを有効にします。
-   「Load unpacked」ボタンをクリックし、拡張機能のソースコードを含む展開されたフォルダーを選択します。
-   拡張機能が読み込まれると、ブラウザのツールバーに表示されます。
    それでおしまい！ GPT チャット拡張機能がインストールされ、使用できるようになりました。

## よくある質問

#### GPT-3とは？

GPT-3 は、Generative Pre-trained Transformer 3 の略です。OpenAI によって開発された、自然言語処理と生成が可能な高度な AI 言語モデルです。

#### この OpenAI チャット拡張機能とは何ですか?

これは、GPT-3 を使用して任意の Web ページで選択されたテキストの応答を生成する Chrome 拡張機能です。任意のテキストを選択してコンテキスト メニューをクリックすることで、GPT-3 と会話することができます。

#### この拡張機能はどのように機能しますか?

ウェブページ上の任意のテキストを選択してコンテキスト メニューをクリックすると、拡張機能は選択したテキストを入力として OpenAI API にリクエストを送信します。 API は生成された応答で応答し、アラート ボックスに表示されます。

#### 拡張機能は安全ですか?

はい、拡張機能は安全です。選択したテキストに対してのみ機能し、個人情報にアクセスしたり保存したりすることはありません。ただし、サードパーティの拡張機能をインストールするときは常に注意することをお勧めします。

#### Web サイトの所有者は、生成された応答を見ることができますか?

いいえ、生成された応答は警告ボックスに表示されるだけで、Web サイトまたはその所有者に送り返されることはありません。

## 著者

-   [@qzxtu](https://www.github.com/qzxtu)

## サポート

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/nova355killer)  
[![Ko-Fi](https://img.shields.io/badge/kofi-00457C?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/nova355)