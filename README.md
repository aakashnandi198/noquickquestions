# noquickquestions

> **"Quick question" is the workplace equivalent of "I'm only having one drink."**  
> Everyone knows you're lying. Especially you.

A humorous, lightweight, and educational static website inspired by [nohello.net](https://nohello.net) and [dontasktoask.com](https://dontasktoask.com), dedicated to explaining why asking *"Can I ask a quick question?"* disrupts focus, delays resolution, and forces unnecessary context-switching.

---

## 🚀 Features

- **Zero dependencies:** Pure semantic HTML5, modern CSS, and minimal vanilla JavaScript.
- **Dark/Light Mode:** Automatically honors OS `prefers-color-scheme`.
- **Realistic Chat Simulation:** Visually captures the anxiety and wasted time of Slack/Teams "quick question" ambushes.
- **Copy Link Button:** One-click copy with toast notification for instant sharing in team chats.
- **Ready for Azure Static Web Apps:** Optimized for $0/mo free-tier global hosting with custom domains and SSL.

---

## 💻 Local Preview

You can open `index.html` directly in your browser, or spin up a local development server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then visit [http://localhost:8000](http://localhost:8000).

---

## ☁️ Deploying to Azure Static Web Apps

1. Push your repository to GitHub.
2. In the [Azure Portal](https://portal.azure.com), create a new **Static Web App** (Free Plan).
3. Connect your GitHub repository (`main` branch).
4. Select **Custom** build preset:
   - **App location:** `/`
   - **Api location:** *(leave empty)*
   - **Output location:** *(leave empty)*
5. Azure will generate a GitHub Actions workflow and deploy your site globally with free automatic SSL.

---

## 📄 License

MIT
