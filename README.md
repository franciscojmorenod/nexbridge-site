# NexBridge Solutions — Website

Static landing page for NexBridge Solutions.

## Deploy to Vercel

### Option A: Drag & Drop (Easiest — no account setup needed)
1. Go to https://vercel.com/new
2. Log in or create a free account
3. Click **"Deploy from your computer"** or drag this entire folder onto the page
4. Vercel auto-detects it as a static site and deploys instantly
5. You get a live URL like `nexbridge-solutions.vercel.app` in ~30 seconds

### Option B: Vercel CLI
```bash
npm install -g vercel
cd nexbridge-site
vercel
```
Follow the prompts — it will ask you to log in and confirm the project name.

### Option C: GitHub + Vercel (Best for ongoing updates)
1. Create a GitHub repo (github.com/new)
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Initial site"
   git remote add origin https://github.com/YOUR_USERNAME/nexbridge-site.git
   git push -u origin main
   ```
3. Go to https://vercel.com/new → Import Git Repository
4. Select your repo → Deploy
5. Every future `git push` auto-redeploys the site ✅

## Custom Domain (nexbridgesolutions.com)
Once deployed on Vercel:
1. Go to your project dashboard → Settings → Domains
2. Add `nexbridgesolutions.com`
3. Vercel gives you DNS records to add at your domain registrar (GoDaddy, Namecheap, etc.)
4. HTTPS is automatic and free

## Local Preview
Just open `index.html` in your browser — no build step needed.
