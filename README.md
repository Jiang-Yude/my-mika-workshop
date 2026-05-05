# Agent 工作流零基礎課・招生頁

江江教練 × Mika 咪卡｜AI 辦公室系列工作坊招生頁。

實體課程招生頁，奶茶色系設計，左右雙欄佈局（仿 AI 落地師架構）。

## 對外網址

GitHub Pages: **https://jiang-yude.github.io/my-mika-workshop/**

決策顧問團評估頁: **https://jiang-yude.github.io/my-mika-workshop/decision-advisor.html**

## 本地源碼位置

```
~/code/my-mika-workshop/
```

按「程式專案與知識庫分層規則」——Git repo 不放主知識庫（避免 iCloud 同步衝突）。

## 對應的知識庫策略檔

文案策略、客戶圖像、產品定位都在主知識庫：

```
江昱德 主知識庫/01 AI 辦公室 & Agent 團隊/06 對外商業策略（短中長三階段）/01 短期 實體工作坊招生/
├── README.md（短期工作坊招生總說明）
├── 2026-05-01-0015 通用招生頁範本.md（MD 招生文案）
├── 2026-05-01-0018 棠凌客群版（已廢棄）.md（五要素反例）
└── 2026-05-01-1152 索引：工作坊網站源碼位置.md（本檔對應的索引）
```

**改網頁文案前**，先看上面的策略檔，確認文字策略後再改 HTML。

## 技術

- 純 HTML / CSS / vanilla JS
- 單頁式（single-page）
- 響應式設計（手機 / 桌面）

## 部署流程

```bash
cd ~/code/my-mika-workshop
git add .
git commit -m "改了什麼"
git push
# 1-3 分鐘後 GitHub Pages 自動 rebuild
```

## 校稿期間

`<meta name="robots" content="noindex, nofollow">` + `robots.txt` 雙防線禁收錄。
正式發布時要拿掉。
