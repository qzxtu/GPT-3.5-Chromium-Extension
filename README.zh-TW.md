# Chat-GPT Web 擴展

OpenAI Chat Extension 是一個瀏覽器擴展，允許用戶使用 OpenAI 的聊天 API 生成 AI 支持的響應。它可以通過選擇任何網頁上的文本並右鍵單擊以從上下文菜單中選擇“使用 OpenAI 生成響應”來激活。然後，該擴展將選定的文本發送到 OpenAI 聊天 API，後者生成一個顯示在彈出窗口中的響應。

## 翻譯

| 🇺🇸            | 🇨🇳                    | 🇹🇼                    | 🇮🇳                | 🇫🇷               | 🇦🇪                | 🇩🇪               | 🇯🇵                | 🇪🇸                 |
| --------------- | ----------------------- | ----------------------- | ------------------- | ------------------ | ------------------- | ------------------ | ------------------- | -------------------- |
| [英語](README.md) | [簡體中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [印地語](README.hi.md) | [法語](README.fr.md) | [阿拉伯](README.ar.md) | [德語](README.de.md) | [日本人](README.ja.md) | [西班牙語](README.es.md) |

## 截圖

![App Screenshot](https://cdn.discordapp.com/attachments/1008195045960204349/1099103637608878090/New_Website_Blue_Mockup_Instagram_-_Laptop.gif)

## 特徵

-   使用 OpenAI 的聊天 API 生成響應
-   與 Chrome 上下文菜單集成以便於訪問
-   將生成的響應複製到剪貼板以便快速粘貼
-   安裝過程簡單
-   詳細的文檔和常見問題解答
-   在 GitHub 上開源

## 文檔

-   轉到 OpenAI API 頁面[快速API](https://rapidapi.com/openai-api-openai-api-default/api/openai80/).
-   單擊“訂閱測試”按鈕。
-   選擇免費的“免費”計劃並單擊“訂閱”。
-   按照說明註冊 RapidAPI 或登錄（如果您已有帳戶）。
-   在 OpenAI API 服務頁面上，在所需請求標頭列表中查找 - - “X-RapidAPI-Key”部分。
-   將 RapidAPI API 密鑰複製到 Chrome 擴展中 background.js 文件的“X-RapidAPI-Key”部分。

## 安裝

-   從 Github 存儲庫下載擴展的源代碼。
-   提取下載的文件夾。
-   打開谷歌瀏覽器並導航到“擴展”頁面。您可以通過在地址欄中鍵入“chrome://extensions/”或單擊 Chrome 右上角的三個點，選擇“更多工具”，然後選擇“擴展程序”來執行此操作。
-   進入“擴展”頁面後，切換右上角的開關以啟用開發者模式。
-   單擊“加載解壓”按鈕並選擇包含擴展源代碼的解壓文件夾。
-   加載擴展後，它應該出現在瀏覽器的工具欄中。
    就是這樣！ GPT Chat Extension 現在應該已安裝並可以使用了。

## FAQ

#### 什麼是 GPT-3？

GPT-3全稱Generative Pre-trained Transformer 3，是OpenAI開發的具有自然語言處理和生成能力的高級AI語言模型。

#### 這個 OpenAI 聊天擴展是什麼？

這是一個 Chrome 擴展程序，它使用 GPT-3 為任何網頁上的選定文本生成響應。它允許您通過選擇任何文本並單擊上下文菜單來與 GPT-3 進行對話。

#### 這個擴展如何工作？

當您在網頁上選擇任何文本並單擊上下文菜單時，該擴展程序會向 OpenAI API 發送一個請求，並將所選文本作為輸入。 API 使用生成的響應進行響應，然後顯示在警告框中。

#### 擴展安全嗎？

是的，擴展是安全的。它僅適用於選定的文本，不會訪問或存儲任何個人信息。但是，始終建議在安裝任何第三方擴展時謹慎使用。

#### 網站所有者可以看到生成的響應嗎？

不，生成的響應僅顯示在警告框中，不會發送回網站或其所有者。

## 作者

-   [@qzxtu](https://www.github.com/qzxtu)

## 支持

[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/nova355killer)  
[![Ko-Fi](https://img.shields.io/badge/kofi-00457C?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/nova355)