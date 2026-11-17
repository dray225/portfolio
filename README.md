# Yeareed Mahmud &mdash; Professional Developer & Data Analyst ePortfolio (Iteration 4)

A clean, polished, and corporate-sharp **Modern Tech & Developer ePortfolio** built with semantic **HTML5**, modern **CSS3**, and vanilla **JavaScript**.

---

## 🚀 What's New in Iteration 4

1. **Toolbar Brand Logo Updated:**
   - Redesigned the top-left navigation logo to the tech URI protocol format:
     ```text
     portfolio://
     YEAREED
     ```
   - Features `portfolio://` in accent cyan and `YEAREED` in bold geometric display typography with clean line-height.

2. **Education (IGCSE Part Updated):**
   - Updated badge to: **`EDEXCEL & CAMBRIDGE CURRICULUM`**
   - Updated description to explicitly mention both curricula:
     > *"15 years of structured education under Edexcel and Cambridge international curricula with a strong emphasis on Computer Science, algorithm design, data structures, and mathematics."*

3. **Browser Tab Icon (Favicon):**
   - Configured the browser tab icon to use your circular profile picture (`assets/circle-pfp.png`).

---

## 📁 Project Structure

```text
iteration 4/
│
├── index.html                   # Production-ready single-page HTML
├── style.css                    # Modern tech & developer design system (Dark & Light mode)
├── script.js                    # Theme toggle, scroll-spy, copy-to-clipboard, contact form
├── VIDEO_INSTRUCTIONS.txt       # Instructions for editing YouTube video embed
├── README.md                    # Setup, customization & GitHub Pages deployment guide
│
└── assets/
    ├── circle-pfp.png           # Transparent circular profile picture (Browser Favicon)
    ├── profile-picture.jpg      # High-resolution focused portrait crop
    ├── Yeareed_Mahmud_Resume.pdf # Printable PDF Resume
    └── Yeareed_Mahmud_CoverLetter.pdf # General Cover Letter
```

---

## 💻 How to Run Locally

### Option 1: Direct File Open
Double-click `index.html` inside the `iteration 4` folder in your file explorer to open it in Chrome, Edge, or Firefox.

### Option 2: Live Server in VS Code
1. Open the `iteration 4` folder in VS Code (`File` > `Open Folder...`).
2. Right-click `index.html` and click **"Open with Live Server"**.
3. It will open at `http://127.0.0.1:5500/index.html`.

### Option 3: Python Local Server
Open PowerShell or your terminal inside the `iteration 4` folder and run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 🌐 Deploying to GitHub Pages (Step-by-Step)

1. Open your terminal inside the `iteration 4` directory:
   ```bash
   cd "iteration 4"
   git init
   git add .
   git commit -m "Release iteration 4: Perfected Developer ePortfolio"
   git branch -M main
   ```

2. Connect to your GitHub repository and push:
   ```bash
   git remote add origin https://github.com/dray225/eportfolio.git
   git push -u origin main --force
   ```

3. Enable GitHub Pages:
   - On GitHub, go to **Settings > Pages**.
   - Under **Build and deployment > Source**, select **Deploy from a branch**.
   - Choose branch **`main`** and folder **`/ (root)`**, then click **Save**.
   - Your site will be live at: `https://dray225.github.io/eportfolio/`

---

## 📄 License & Credits
- **Candidate:** Yeareed Mahmud
- **Location:** Uttara, Dhaka, Bangladesh
- **Target Roles:** Data Analyst &bull; Software Specialist &bull; BI Developer
- Previous iterations (`iteration 1/`, `iteration 2/`, `iteration 3/`) remain safely preserved.
