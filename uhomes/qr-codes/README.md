# Uhomes Referral QR Codes

> Campaign: `uhomes-launch-may2026` · xcode: `000a083c9b90ced49118`
> 自動產出時間:每次跑 `python generate_qrcodes.py` 重產

## 各平台 QR PNG 對應

| 平台 | QR 檔名 | 對應 URL | 描述 |
|:--|:--|:--|:--|
| linkedin | `linkedin.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=linkedin&utm_medium=social&utm_campaign=uhomes-launch-may2026&utm_content=announcement-may05 | LinkedIn 公司頁公告(5/5)+ 解析(5/27) |
| line | `line.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=line&utm_medium=social&utm_campaign=uhomes-launch-may2026&utm_content=broadcast-may13 | LINE Official 廣播(5/13) |
| instagram | `instagram.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=instagram&utm_medium=social&utm_campaign=uhomes-launch-may2026&utm_content=carousel-may20 | IG carousel 訂房地雷(5/20)+ 教學(5/9) |
| blog | `blog.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=blog&utm_medium=organic&utm_campaign=uhomes-launch-may2026&utm_content=article-may11 | 部落格主文(5/11 pioneeredu.com.tw) |
| medium | `medium.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=medium&utm_medium=organic&utm_campaign=uhomes-launch-may2026&utm_content=article-may11 | Medium 衍生(5/12) |
| vocus | `vocus.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=vocus&utm_medium=organic&utm_campaign=uhomes-launch-may2026&utm_content=article-may11 | Vocus 衍生(5/12) |
| facebook | `facebook.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=facebook&utm_medium=social&utm_campaign=uhomes-launch-may2026&utm_content=post-may20 | FB 粉專(5/20 同步 IG) |
| line-direct | `line-direct.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=line-direct&utm_medium=cs&utm_campaign=uhomes-launch-may2026&utm_content=ec-ih-may16 | LINE 1:1 私訊(EC/IH 5/16 / ESCP 5/23) |
| hero-image | `hero-image.png` | https://en.uhomes.com/referral/partnerShare?xcode=000a083c9b90ced49118&utm_source=hero-image&utm_medium=visual&utm_campaign=uhomes-launch-may2026&utm_content=shared-asset | Hero 16:9 圖被截圖分享 / 印製品共用 |

## hotlink 用法

raw URL pattern:

```
https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/uhomes/qr-codes/{platform}.png
```

範例:LinkedIn QR

```html
<img src="https://raw.githubusercontent.com/PioneerEdu/pioneer-marketing-assets/main/uhomes/qr-codes/linkedin.png" alt="Uhomes LinkedIn QR" width="240" />
```

## 重產

新一波 campaign 開始時,改 `generate_qrcodes.py` 內的 `CAMPAIGN` 與 `PLATFORMS` 中的 `utm_content`,然後跑:

```bash
python generate_qrcodes.py
```

## 整合進 uhomes-promo skill

本 skill 在每次跑時自動讀取此資料夾 + 補 QR 進素材包(Phase B+ 5/15 後啟用)。
