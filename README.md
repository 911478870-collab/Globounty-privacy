# Globounty Privacy Policy (GitHub Pages)

Public URL: https://911478870-collab.github.io/Globounty-privacy/

## Update & publish

1. Edit `privacy.html` (or copy from `bounty_app/docs/privacy.html` after changes there).
2. Commit and push to `main` on GitHub repo `911478870-collab/Globounty-privacy`.
3. GitHub Pages → Settings → deploy from `main` / root.
4. Confirm `Last Updated` date on the live page.

## Sync from main app repo

```powershell
Copy-Item "..\bounty_app\docs\privacy.html" ".\privacy.html" -Force
git add privacy.html index.html
git commit -m "Update privacy policy"
git push
```

Contact on policy: houbaibai688@gmail.com
