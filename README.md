# Al Jaddaf Project Dashboard

Project performance dashboard for the proposed (2B+G+2P+H.C+21+R) residential and commercial building at Al Jaddaf Waterfront, Dubai.

**Live page:** https://waleedtammamwrwr-netizen.github.io/al-jaddaf-dashboard/

## Viewing
Anyone with the link can open the dashboard. No sign-in is needed.

## Editing (editors only)
1. Create a GitHub key: Settings › Developer settings › Personal access tokens › Fine-grained tokens › Generate new token.
   - Repository access: **Only select repositories** › `al-jaddaf-dashboard`
   - Permissions › Repository permissions › **Contents: Read and write**
2. On the dashboard, select **Editor sign in** and paste the key. It is stored only in your browser.
3. Open a table, select **Edit this table**, change the figures, then **Save changes**.
   You can also use **Upload Excel** with the monthly dashboard workbook.

Each save is a commit to `data.json`; the figures before it are kept in `data-previous.json`, and **Restore previous save** switches back. The full history is in the repository's commit list. The public page shows a save within about a minute.

## Files
- `index.html` – the dashboard
- `data.json` – all figures shown on the dashboard
- `photos/` – site photos and the render