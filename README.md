# 🛍️ DealsHub India — GitHub Pages Setup Guide

This is your complete, production-ready, mobile-first Deals Landing Page built specifically for **100% free, unlimited hosting on GitHub Pages**.

---

## 🚀 How to Deploy on GitHub Pages in 3 Minutes

You have two simple ways to deploy this on GitHub:

### Method 1: Using the GitHub Website (No Coding / No Terminal)

1. Go to [github.com](https://github.com) and log in.
2. Click the **`+`** icon in the top-right corner and select **`New repository`**.
3. Name your repository (e.g., `dealshub` or `wristhub`).
   - Choose **Public**.
   - Do NOT initialize with a README (keep it empty).
   - Click **Create repository**.
4. On the next screen, click **"uploading an existing file"**.
5. Drag and drop the `index.html` file from:
   `C:\Users\chasi\.gemini\antigravity\scratch\dealshub-landing-page\index.html`
6. Click **Commit changes** (green button).
7. Now go to **Settings** (top tab) ➔ Click **Pages** (left sidebar).
8. Under **Build and deployment**:
   - Source: **Deploy from a branch**.
   - Branch: Select **`main`** and folder **`/(root)`**.
   - Click **Save**.
9. Wait 60 seconds — GitHub will give you your live URL:  
   👉 `https://your-username.github.io/dealshub/` 🎉

---

### Method 2: Using Git Terminal (PowerShell / Command Prompt)

```powershell
cd C:\Users\chasi\.gemini\antigravity\scratch\dealshub-landing-page
git init
git add .
git commit -m "Launch DealsHub India landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/dealshub.git
git push -u origin main
```
Then enable GitHub Pages under **Repository Settings > Pages** as shown in Method 1.

---

## 🔗 Pre-Configured Live Channel Links

Your `index.html` already has these live links configured:
- **WristHub Telegram**: `https://t.me/wristhubchasi`
- **WristHub WhatsApp**: `https://whatsapp.com/channel/0029Vb8LscABFLgZDQa3Fm3o`

### How to update or add your other channel links:
Open `index.html` in any text editor and find the other cards (Boys Fashion, Girls Fashion, GlowHub). Replace `https://t.me/wristhubchasi` with your specific new channel links whenever you create them.

---

## 🌐 How to Connect a Custom Domain (e.g., `dealshub.in` or `wristhub.in`)

1. Buy a domain from Namecheap, GoDaddy, or Hostinger (₹300–₹500/year).
2. In your GitHub repository, go to **Settings > Pages > Custom domain**.
3. Type your domain (e.g., `wristhub.in`) and click **Save**.
4. In your domain registrar DNS settings:
   - Add a `CNAME` record pointing to `YOUR_USERNAME.github.io`.
   - Check the **"Enforce HTTPS"** box on GitHub Pages.
5. Done! Your landing page is now live on your own branded domain with free SSL!
