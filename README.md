# Myanmar Casino Landing Page

This is a static Vercel site. It does not need Express, Railway, or an npm install step.

Production deploys should follow the root `DEPLOYMENT_RUNBOOK.md`: align the Git branch first, then deploy through the approved Vercel workflow.

## 🔗 更換連結

請參考 `連結說明.md` 文件來了解如何更換連結。

## 📁 檔案結構

- `index.html` - 主頁面文件
- `vercel.json` - Vercel rewrites, headers, and affiliate redirect routes
- `api/go.js` - Serverless affiliate redirect handler
- `links-config.js` - 連結配置文件（可選）
- `連結說明.md` - 連結更換說明

## 🛠️ 本地開發

```bash
python3 -m http.server 3000
```

靜態頁面將在 http://localhost:3000 運行。Vercel rewrites should still be verified through a Vercel preview or production deployment before release.
