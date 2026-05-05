# Koi Innovations Ecosystem

Complete documentation hub for Koi Innovations LLC. Twelve ventures. Thirty documents. One architectural vision.

**Live Site:** https://koiinnovations.com

---

## 📁 Folder Structure

```
koi-innovations-ecosystem/
│
├── index.html                          # Main hub (Three Doors gateway)
├── README.md                           # This file
├── .gitignore                          # Git ignore rules
│
├── governance/
│   ├── KOI_Innovations_Master.html
│   ├── KOI_Portfolio.html
│   ├── KOI_Codex.html
│   ├── KOI_Brand_Kits.html
│   └── KOI_Document_Registry.html
│
├── ventures/
│   ├── image-tier/
│   │   ├── Priauratize.html
│   │   ├── Priaura.html
│   │   └── Homes_of_Aura.html
│   ├── operations-tier/
│   │   ├── Clean_Check.html
│   │   ├── Fast_Freddy.html
│   │   ├── Hopson_Logistics.html
│   │   └── Virtechz.html
│   └── culture-tier/
│       ├── Filet_Me_On.html
│       ├── TipsyTAB.html
│       ├── The_Groove.html
│       ├── INDIGO.html
│       └── Black_Alumni_Gala.html
│
├── library/
│   ├── Library_Module_00.html
│   └── Library_Module_01.html
│
└── tier2-assets/
    ├── guides/
    │   ├── Priaura_Mascot_Guide.html
    │   ├── Priauratize_Wardrobe_Guide.html
    │   ├── Clean_Check_Window_Pricing_Guide.html
    │   ├── Ray_Approved_Affiliate_Platform_Guide.html
    │   ├── Clean_Check_EVS_Framework.html
    │   └── Priaura_Brand_Story_Heritage.html
    ├── testimonies/
    │   └── Priauratize_Client_Testimonies.html
    └── flyers/
        ├── Priaura_Flyer_01_Barkley_Speed_Thrills.html
        ├── Priaura_Flyer_02_Seasonal_Collection.html
        ├── Priaura_Flyer_03_Polos_and_Shorts.html
        └── Priaura_Flyer_04_Limited_Edition_VIP.html
```

---

## 🚀 Setup Instructions

### Step 1: Create GitHub Repository

1. Go to https://github.com/koiinnovations1-stack
2. Click **"New"** (top left)
3. Repository name: `koi-innovations-ecosystem`
4. Description: `Complete documentation ecosystem for Koi Innovations LLC`
5. Set to **Public** (so Netlify can access it)
6. Check **"Add a README file"**
7. Click **"Create repository"**

### Step 2: Upload Files to GitHub

1. In your new repo, click **"Add file"** → **"Upload files"**
2. Download the `koi-innovations-ecosystem` folder from this package
3. Drag all folders and files into the GitHub upload area
4. Commit message: `Initial ecosystem build — 30 documents, complete structure`
5. Click **"Commit changes"**

### Step 3: Connect to Netlify

1. Go to https://netlify.com
2. Sign up (or log in)
3. Click **"Add new site"** → **"Import an existing project"**
4. Select **GitHub** as your Git provider
5. Authorize Netlify to access your GitHub account
6. Select repository: `koiinnovations1-stack / koi-innovations-ecosystem`
7. Leave build settings as default (Netlify detects static site automatically)
8. Click **"Deploy site"**
9. Netlify generates a temporary URL (something like `xyz-123.netlify.app`)

### Step 4: Connect Custom Domain

1. In Netlify dashboard, go to **Domain settings**
2. Click **"Add custom domain"**
3. Enter: `koiinnovations.com`
4. Netlify provides DNS records
5. Go to your domain registrar (GoDaddy, Namecheap, etc.)
6. Update DNS records to point to Netlify
7. Wait 24–48 hours for DNS propagation (usually faster)
8. Site is now live at https://koiinnovations.com

### Step 5: Enable Google Analytics

1. In `index.html`, find this line:
   ```html
   <script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
   ```

2. Go to https://analytics.google.com
3. Set up a new property for koiinnovations.com
4. Copy your Measurement ID (looks like `G-XXXXXXXXXX`)
5. Replace both instances of `G-XXXXXXXXXX` in index.html with your ID
6. Commit change to GitHub
7. Netlify auto-deploys within 30 seconds
8. Analytics starts tracking immediately

---

## ✏️ How to Update Documents

### Option A: Edit in GitHub Web Editor (Easiest)

1. Go to your GitHub repo
2. Navigate to the file you want to edit (e.g., `ventures/image-tier/Priaura.html`)
3. Click the **pencil icon** (Edit this file)
4. Make changes directly in the browser
5. Scroll down, write a commit message (e.g., "Update Priaura pricing")
6. Click **"Commit changes"**
7. **Netlify automatically deploys within 30 seconds**
8. Changes are live

### Option B: Edit Locally & Push (For Advanced)

1. Clone the repo locally: `git clone https://github.com/koiinnovations1-stack/koi-innovations-ecosystem.git`
2. Make edits to files in your code editor
3. Commit: `git add . && git commit -m "Update message"`
4. Push: `git push origin main`
5. Netlify auto-deploys

### Option C: Request Updates (No GitHub Access)

Send me the changes you want made, I'll update the files and push to GitHub. You'll see changes live within 30 seconds.

---

## 📊 Analytics Setup

Once GA is connected, you can track:

- Page views by document
- User flow (which doors lead to which ventures)
- Time on page (engagement by document type)
- Geographic data
- Device breakdown

Access analytics at: https://analytics.google.com → Your Property

---

## 🔄 Version Control

GitHub keeps a complete history of every change:

- **See all changes:** Go to repo → **"Commits"**
- **Roll back to previous version:** Click commit → **"Browse the repository at this point in the history"**
- **Compare versions:** Use **"Compare"** tab to see what changed between dates

---

## 📝 Document Stats

- **Total Documents:** 30
- **Governance:** 5 documents
- **Ventures:** 12 documents (3 tiers)
- **Library Modules:** 2 documents
- **Tier 2 Assets:** 11 documents (guides, testimonies, flyers)

---

## 🎨 Design System

All documents follow the locked design language:

- **Typography:** Cormorant Garamond (headers) + Inter (body)
- **Colors:** Koi Black (#0A0A0A), Koi Gold (#C8A24B), Ivory (#F4EDE0)
- **Pattern:** Fixed nav, hero sections, fade-in animations, responsive grid layouts
- **Meta Tag:** `<meta name="color-scheme" content="light only">` (prevents dark mode)

---

## 🚨 Important Notes

1. **HTML Only:** All documents are self-contained HTML files. No database, no backend.
2. **Mobile First:** All documents are fully responsive (tested on mobile, tablet, desktop).
3. **Accessibility:** Semantic HTML, proper heading hierarchy, color contrast compliance.
4. **Performance:** Fast loading (no heavy assets, clean code, optimized structure).
5. **SEO Ready:** Meta tags, proper titles, structured headings for each document.

---

## 📞 Support & Questions

- **Add new documents?** Create new HTML file in appropriate folder, add link to index.html, commit to GitHub.
- **Change colors?** Update CSS variables in the `:root` selector of each file (or use search/replace in code editor).
- **Update navigation?** Edit the `nav` section in index.html and corresponding venture pages.
- **Deploy new version?** GitHub + Netlify auto-deploys on every commit (no manual steps).

---

## 🔐 GitHub Repository Settings

Recommended settings for your repo:

1. **Settings** → **Branch protection rules**
   - Protect main branch (require pull request reviews before merging)
   
2. **Settings** → **Pages**
   - Source: Deploy from a branch
   - Branch: main
   - (Netlify will override this, but good to have set)

3. **Settings** → **Secrets and variables** (if using automated deploys)
   - Store sensitive data here if needed

---

## 📅 Maintenance Cadence

Suggested update schedule:

- **Quarterly:** Review venture documents, update financial/operational data
- **Monthly:** Check analytics, monitor traffic patterns
- **Weekly:** Update Tier 2 assets (pricing, testimonies, flyers)
- **As Needed:** Governance updates, new ventures, new documents

---

## 🎯 Next Steps

1. Create GitHub repo
2. Upload all files
3. Connect to Netlify
4. Point domain to Netlify
5. Enable Google Analytics
6. Test all links work
7. Share koiinnovations.com with stakeholders

---

**Built:** May 2026  
**Architect:** Rayshun Hopson, Founder  
**System:** Koi Method — Architectural Visionary  
**Philosophy:** By Design — Everything, with intentionality.
