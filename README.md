# Wanderlust — 日本旅遊探險網站

兩個完整的首頁設計，展示不同的設計哲學。

## 📂 檔案結構

```
.
├── index.html           # 版本選擇頁面
├── official.html        # 官方樣板版本
├── my-version.html      # 我的簡潔版本
└── README.md           # 本檔案
```

## 🌐 版本說明

### 官方版本 (official.html)
- **設計風格**: 現代動感，視覺導向
- **配色**: 深藍 + 金色 + 紅色
- **互動**: Hero 背景圖輪換、互動地圖、新聞 Carousel
- **特色**: Swiper.js 輪播庫、SVG 互動地圖

### 我的版本 (my-version.html)
- **設計風格**: 極簡優雅，內容導向
- **配色**: 深藍綠 + 焦糖色
- **互動**: 卡片懸停動畫、平滑滾動、新聞訂閱
- **特色**: 零依賴、原生 JavaScript、快速加載

## 🚀 部署

### 用 GitHub Pages 部署

1. 在 GitHub 上建立新倉庫 `wanderlust-web`
2. Clone 到本地
3. 複製所有 HTML 檔案
4. Commit 並 Push

```bash
git add .
git commit -m "Initial commit: Wanderlust homepage"
git push -u origin main
```

4. 在 GitHub 倉庫設定中，啟用 GitHub Pages：
   - Settings → Pages
   - Source: `main` 分支
   - 保存

5. 你的網站將在以下地址可用：
   ```
   https://[your-username].github.io/wanderlust-web
   ```

### 用 Vercel 部署

1. 在 Vercel 連接你的 GitHub 倉庫
2. 自動部署
3. 獲得免費的 URL

### 本地測試

```bash
python3 -m http.server 8080
# 打開 http://localhost:8080
```

## 📱 響應式設計

兩個版本都完全適配：
- 桌面 (1024px+)
- 平板 (768-1024px)
- 手機 (<768px)

## 🎨 自訂指南

### 改變色彩

在 HTML 的 `<style>` 區塊中編輯 CSS 變量或顏色值。

### 添加更多城市

編輯 HTML 中的城市卡片 / 地圖標記 / 城市網格。

### 編輯內容

所有文本都在 HTML 中清楚標記，易於編輯。

## 📞 技術細節

### 官方版本依賴
- Swiper.js (v10) — 用於新聞 Carousel
- Google Fonts — 日文和中文字體

### 我的版本依賴
- 零外部依賴
- 原生 JavaScript（Intersection Observer）
- Google Fonts

## 🎯 下一步

- [ ] 添加真實的日本旅遊內容
- [ ] 集成後端（預訂、聯絡表單）
- [ ] 添加 SEO 元標籤
- [ ] 性能優化（圖片懶加載）
- [ ] 國際化（英文、日文）

---

**版本**: 1.0  
**最後更新**: 2026-04-13  
**作者**: Wanderlust Team
