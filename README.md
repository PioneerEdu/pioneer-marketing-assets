# Pioneer Education Marketing Assets

先鋒教育對外行銷素材庫 — Brand logos 與素材檔。

## 用途

這個 repo 託管所有對外行銷材料(EDM、社群圖、報價單、Landing Page、合作網站)會引用的品牌 logo 與素材。

**所有檔案皆為公開可引用之對外品牌資產,不含商業機密。**

## 檔案結構

```
logos/
├── padlet-logo.jpg              # Padlet 官方 logo
├── wordwall-logo.png            # Wordwall 官方 logo
├── pioneer-mark-h.png           # 先鋒教育 logo · navy 底白字 horizontal
├── pioneer-mark-square.jpg      # 先鋒教育 logo · navy 底白字方形
└── pioneer-mark-vertical.jpg    # 先鋒教育 logo · 白底 navy 直式
```

## 如何引用

HTML / Markdown / EDM 直接引用 raw URL:

```html
<img src="https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/logos/padlet-logo.jpg" alt="Padlet">
<img src="https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/logos/wordwall-logo.png" alt="Wordwall">
<img src="https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/logos/pioneer-mark-h.png" alt="Pioneer Education">
```

Markdown:

```markdown
![Pioneer](https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/logos/pioneer-mark-h.png)
```

## 維護規則

- 新增 / 更新 logo 直接 commit 即可
- **Filename 一旦 commit 後不要改名**(會破壞既有引用)
- 如需新版本,加 suffix(例如 `-v2`、`-2026`)
- 移除舊檔請先確認沒有現役 EDM / Landing Page 還在引用

## 第三方 logo 使用聲明

- Padlet logo © Padlet — 經授權使用於先鋒教育代理推廣
- Wordwall logo © Wordwall — 經授權使用於先鋒教育代理推廣
- Pioneer Education logo © Pioneer Education Group Taiwan
