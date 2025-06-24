# Pimisha PowerPoint Add-in

This PowerPoint Add-in embeds [Pimisha](https://pimisha.tandadesign.com) inside a task pane, allowing you to use interactive word clouds and polls during presentations.

## 💡 Features
- Embed Pimisha web app in taskpane
- Real-time audience interaction
- Simple to deploy, works on Mac/Windows/Web

## 🛠 Installation (Manual Sideload)
1. Place `manifest.xml` in your Office sideload folder:
   - **Mac**: `~/Library/Containers/com.microsoft.Powerpoint/Data/Documents/wef/`
2. Restart PowerPoint
3. Open `Tools → Add-ins` and add the add-in

## 🌐 Hosting Requirements
Ensure your site allows embedding via iframe. Remove `X-Frame-Options` headers or use:
```
Content-Security-Policy: frame-ancestors 'self' https://*.officeapps.live.com;
```

## 📸 Screenshots
See `/assets/screenshots/` folder for AppSource or documentation usage.
