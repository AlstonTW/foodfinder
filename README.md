# 附近美食探索 PWA

## 上傳到 GitHub Pages 步驟

### 第一步：建立 Repository
1. 登入 [github.com](https://github.com)
2. 右上角「+」→「New repository」
3. Repository name 填：**foodfinder**（或任意名稱）
4. 選「Public」
5. 按「Create repository」

### 第二步：上傳檔案
1. 在新建立的 repo 頁面，點「uploading an existing file」
2. 把以下所有檔案拖進去（**包含 icons 資料夾裡的兩個圖片**）：
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icons/icon-192.png`
   - `icons/icon-512.png`
3. 按「Commit changes」

### 第三步：啟用 GitHub Pages
1. 進入 repo → 上方「Settings」
2. 左側選單「Pages」
3. Source 選「Deploy from a branch」
4. Branch 選「main」，資料夾選「/ (root)」
5. 按「Save」

### 第四步：等待約 1-2 分鐘
網址會是：`https://你的GitHub帳號.github.io/foodfinder`

---

## 手機加入桌面（當成 App 使用）

### iPhone (Safari)
1. 用 Safari 打開網址
2. 下方工具列點「分享」圖示
3. 選「加入主畫面」→「新增」

### Android (Chrome)
1. 用 Chrome 打開網址
2. 右上角三個點選單
3. 選「新增到主畫面」或「安裝應用程式」

---

## API Key 設定
- 第一次打開 App 會自動彈出設定畫面
- 輸入你的 Google Maps API Key 後點「儲存並載入地圖」
- Key 會存在你的裝置上，下次打開不用再輸入
- 右上角齒輪可以隨時修改 API Key

## 需要啟用的 Google API
- Places API
- Geocoding API
- Maps JavaScript API
