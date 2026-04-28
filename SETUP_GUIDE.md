# 習慣養成島 - App 上架完整指南

## 一、申請帳號（先做）

### Apple Developer（iOS 上架必須）
1. 前往 https://developer.apple.com/programs/
2. 點「Enroll」→ 用 Apple ID 登入
3. 選「Individual」→ 付款 $99 USD/年
4. 等待審核 24-48 小時

### Google Play（Android 上架必須）
1. 前往 https://play.google.com/console
2. 付款 $25 USD（一次性）
3. 填寫開發者資料

---

## 二、上傳程式碼到 GitHub

### 在你的 GitHub Repo 新增這些檔案：
把 habit-island.zip 裡的所有檔案上傳到：
`github.com/angel-lin0210/21-days-habit-formation`

特別是這兩個 workflow 檔案：
- `.github/workflows/build-ios.yml`
- `.github/workflows/build-android.yml`

---

## 三、執行 GitHub Actions 打包

1. 前往 `github.com/angel-lin0210/21-days-habit-formation`
2. 點上方 **Actions** 分頁
3. 選 **Build iOS App** → 點 **Run workflow**
4. 同樣執行 **Build Android App**
5. 等待約 10-20 分鐘
6. 完成後點 **Artifacts** 下載打包好的檔案

---

## 四、iOS 上架 App Store

帳號審核通過後：

1. 前往 https://appstoreconnect.apple.com
2. 點「我的 App」→「+」→「新增 App」
3. 填寫：
   - 名稱：習慣養成島
   - Bundle ID：com.habitisland.app
   - SKU：habitisland2025
4. 填寫 App 描述（中英文各一份）
5. 上傳截圖（用 iPhone 模擬器截圖）
6. 上傳打包好的 .ipa 檔案
7. 送審

---

## 五、Android 上架 Google Play

1. 前往 https://play.google.com/console
2. 建立新應用程式
3. 填寫資料、上傳截圖
4. 上傳 APK 檔案
5. 送審（通常 1-3 天）

---

## App 資訊（建議）

| 項目 | 內容 |
|------|------|
| 名稱（中）| 習慣養成島 |
| 名稱（英）| Habit Island |
| 分類 | 教育 / 生活 |
| 年齡 | 4+ |
| 價格 | 免費 |

### 描述（中文）
幫助孩子建立良好習慣的家庭遊戲化 App。用打怪、升級、獎勵的方式，讓孩子每天主動完成習慣挑戰！

### 描述（英文）
A gamified habit-building app for families. Help your children build good habits through monster battles, XP systems, and rewards!

---

## 所需截圖尺寸

### iOS
- iPhone 6.7"：1290 × 2796 px
- iPhone 6.5"：1242 × 2688 px
- iPad Pro 12.9"：2048 × 2732 px

### Android
- 手機：1080 × 1920 px 以上

