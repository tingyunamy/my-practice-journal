# 🪷 我的修行手帳 My Practice Journal

這是可直接放上 GitHub Pages 的靜態網頁版佛教定課手帳。  
風格走「無印良品 × MIDORI 手帳 × 禪修手冊」。

## 內容

- `index.html`：網頁主體
- `style.css`：禪風文具版樣式
- `script.js`：儲存、統計、CSV、熱力圖功能
- `README.md`：部署教學

## 功能

- 📿 念佛累積與 10 萬佛號進度
- 🧘 禪修分鐘與時數統計
- ✅ 一週定課打勾
- 🪷 蓮花進度條
- 🌙 月相完成度
- 🔥 年度修行熱力圖
- 📝 修行札記
- 🌸 感恩
- 🍂 覺察
- ⭐ 下週發願
- 📤 匯出 CSV
- 📥 匯入 CSV
- 💾 LocalStorage 自動儲存
- 📱 手機版 RWD

## 預設定課

- 📿 念佛
- 🧘 禪修
- 📖 讀經
- ✍️ 抄經
- 🌅 早課
- 🌙 晚課
- 🙏 八十八佛
- 🤝 義工服務
- 🏯 共修
- 💝 布施善行

已移除「放生護生」。

## GitHub Pages 部署

1. 到 GitHub 建立新 repository，例如：`my-practice-journal`
2. 上傳四個檔案到根目錄：
   - `index.html`
   - `style.css`
   - `script.js`
   - `README.md`
3. 進入 repository 的 **Settings**
4. 左側點 **Pages**
5. Source 選：
   - Branch：`main`
   - Folder：`/root`
6. 按 Save
7. 等待網址產生。

網址會像：

`https://你的帳號.github.io/my-practice-journal/`

## 使用提醒

資料存在瀏覽器 LocalStorage。  
換手機、換電腦、清除瀏覽器資料前，請先匯出 CSV 備份。

## 自訂項目

打開 `script.js`，找到：

```js
const defaultPractices = [
```

即可修改定課項目、圖示與單位。

## 核心提醒

Tracker 是鏡子，不是績效表。  
不是為了證明自己有修，而是提醒自己：今天有沒有回來看心。
