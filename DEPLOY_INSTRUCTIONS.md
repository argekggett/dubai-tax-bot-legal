# Quick Deploy - Legal Pages

## Option 1: GitHub Pages (Recommended, 3 minutes)

1. **Create GitHub Account** (if you don't have one):
   - Go to: https://github.com/signup
   - Use: viagogoticketim@gmail.com
   - Pick username (e.g., "dubaitaxbot")

2. **Create Repository:**
   ```bash
   # On GitHub.com:
   # Click "+" → "New repository"
   # Name: "dubai-tax-bot-legal"
   # Public: YES
   # Initialize: NO (we already have files)
   ```

3. **Push Files:**
   ```bash
   cd /Users/Admin/clawd/tiktok_dubai/legal
   
   # Replace YOUR_USERNAME with your GitHub username
   git remote add origin https://github.com/YOUR_USERNAME/dubai-tax-bot-legal.git
   git branch -M main
   git push -u origin main
   ```
   
   (Enter GitHub username + Personal Access Token when prompted)

4. **Enable GitHub Pages:**
   - Go to repo → Settings → Pages
   - Source: "main" branch
   - Click "Save"
   - Wait 2 minutes for deployment

5. **URLs will be:**
   ```
   https://YOUR_USERNAME.github.io/dubai-tax-bot-legal/terms_of_service.html
   https://YOUR_USERNAME.github.io/dubai-tax-bot-legal/privacy_policy.html
   ```

---

## Option 2: Netlify Drop (Fastest, 1 minute)

1. Go to: https://app.netlify.com/drop
2. Drag the `/Users/Admin/clawd/tiktok_dubai/legal/` folder into the upload area
3. Get instant URLs like:
   ```
   https://random-name-12345.netlify.app/terms_of_service.html
   https://random-name-12345.netlify.app/privacy_policy.html
   ```
4. Optional: Rename site in Netlify dashboard

---

## Option 3: Vercel (2 minutes)

1. Install: `npm install -g vercel`
2. Run:
   ```bash
   cd /Users/Admin/clawd/tiktok_dubai/legal
   vercel --prod
   ```
3. Follow prompts (use viagogoticketim@gmail.com)
4. Get URLs

---

## Which to use?

- **Fastest:** Netlify Drop (no CLI, just drag & drop)
- **Best long-term:** GitHub Pages (version control + free forever)
- **Easiest CLI:** Vercel (one command)

**Recommendation:** Use Netlify Drop NOW (1 minute), then migrate to GitHub Pages later if needed.
