# Ecard
一個可讓人建立帳號發表文章的網站
## Demo
https://ecard-new.herokuapp.com/index

## 畫面功能截圖
### 開始畫面，點擊左側欄可選擇分類文章，在上方搜尋欄可用關鍵字搜尋文章標題
![](https://i.imgur.com/qUfW28o.png)

## 登入與註冊
登入

![](https://i.imgur.com/mUSfpqx.png)

註冊

![](https://i.imgur.com/ZlHIiCc.png)

## 個人資訊頁，可編輯和刪除文章
![](https://i.imgur.com/HzSwSxG.png)

## 單篇文章，包含留言板
![](https://i.imgur.com/cHpiRUQ.png)

## 編輯和發布文章(可上傳圖片)
![](https://i.imgur.com/oUirAap.png)

## 功能
1. 可註冊及登入帳號
2. 可發表/編輯/刪除自己的文章
3. 可對文章進行留言
4. 左側欄可以觀看特定類別文章
5. 可利用標題搜尋特定文章
6. 文章中能插入圖片

## 本作品使用主要技術
* Pug
* Sass
* Bootstrap
* Node.js
* JavaScript
* Express.js
* Firebase
* imgur Api

## 指令
啟動應用程式: npm start

啟動 gulp: gulp watch

## 解決 firebase 重複 register error:
"firebase": "^6.4.1",
"firebase-admin": "^8.1.0",

firebase 版本改成6.4.1
