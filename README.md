# AI Agency Control Center

A single-file, browser-based dashboard for organizing website client requests and tracking delivery.

## Live preview

After GitHub Pages deployment completes, open the Pages URL shown in **Settings → Pages** or in the deployment workflow run.

## Included

- Client request intake and project tracker
- Quote and preview URL fields
- Delivery checklist
- Build-brief generator
- JSON backup export
- GitHub Actions workflow to publish the static site to GitHub Pages

## Publish

1. Open **Settings → Pages** and select **GitHub Actions** as the build/deployment source if prompted.
2. Open **Actions** and check the workflow named **Deploy AI Agency Control Center to GitHub Pages**.
3. After a successful run, open the Pages URL displayed by GitHub.

## Important limitations

This is a starter dashboard, not an autonomous AI agent. Project data is stored in the current browser's local storage; it is not synchronized across devices and is not automatically emailed. AI APIs, client email, phone calling, automated website generation, browser tests, and automatic repairs need separate integrations, permissions, and sometimes paid services. Do not put API keys or private client information into public frontend code.

## Local use

Open `index.html` in a modern browser. Use **Export JSON backup** regularly because clearing browser data can remove locally saved projects.
