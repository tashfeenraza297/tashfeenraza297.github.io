# ⚡ QUICK REFERENCE CARD

## 🎯 What You Need to Do RIGHT NOW:

### 1️⃣ Add Your Profile Photo
```
📂 Save to: assets/images/profile-photo.jpg
📏 Size: 400x400 pixels (square)
📸 Type: Professional headshot
```

### 2️⃣ Add ML Resume
```
📂 Save to: assets/resume/Tashfeen_Raza_ML_Resume.pdf
📄 Format: PDF only
💼 Focus: Machine Learning, Deep Learning, CV
```

### 3️⃣ Add Agentic AI Resume
```
📂 Save to: assets/resume/Tashfeen_Raza_Agentic_AI_Resume.pdf
📄 Format: PDF only
🤖 Focus: Agentic AI, LLM, RAG, LangChain
```

---

## 🎨 NEW FEATURES YOU GOT:

✨ **Loading Screen** - Shows when page loads  
🌓 **Dark/Light Mode** - Toggle button (bottom-right)  
📥 **2 CV Download Buttons** - In hero section  
📊 **Animated Stats Counter** - Below about section  
📧 **Contact Form** - In contact section  
🤖 **404 Error Page** - Custom not-found page  
🎯 **SEO Optimized** - Google-ready with sitemap  
♿ **Accessibility** - Keyboard navigation support  

---

## 🚀 HOW TO TEST:

1. **Open** `index.html` in browser
2. **Click** theme toggle (moon icon)
3. **Scroll** to stats section (watch animation)
4. **Try** contact form
5. **Refresh** page (see loading screen)

---

## 📞 CONTACT FORM SETUP (Optional):

**To make form actually send emails:**

1. Go to: https://formspree.io
2. Sign up (free)
3. Create form → Get endpoint URL
4. Edit `js/main.js` line ~130:
   ```javascript
   fetch('https://formspree.io/f/YOUR_FORM_ID', {
   ```
5. Replace `YOUR_FORM_ID` with your actual ID

**Without setup:** Form opens email client (works fine!)

---

## 🎨 CUSTOMIZE COLORS:

Edit `css/style.css` top section:
```css
:root {
    --primary: #8b5cf6;     /* Purple */
    --accent: #06b6d4;      /* Cyan */
    /* Change these! */
}
```

---

## 📱 FILES YOU GOT:

- ✅ index.html (UPDATED)
- ✅ style.css (UPDATED)
- ✅ main.js (UPDATED)
- ✅ 404.html (NEW)
- ✅ robots.txt (NEW)
- ✅ sitemap.xml (NEW)
- ✅ .gitignore (NEW)

---

## ⚠️ REMEMBER:

- **Exact filenames matter!** (case-sensitive)
- CV files max 5MB each
- Profile photo should be square
- Test all features before deploying

---

## 🐛 TROUBLESHOOTING:

**Photo not showing?**
→ Check filename: `profile-photo.jpg` (exact)
→ Check location: `assets/images/`

**CV download not working?**
→ Add PDF files to `assets/resume/`
→ Use exact filenames shown above

**Form not submitting?**
→ Expected! Set up FormSpree (see above)
→ Or it opens email client (that's fine)

---

## ✅ DEPLOY CHECKLIST:

- [ ] Add profile photo
- [ ] Add ML resume PDF
- [ ] Add Agentic AI resume PDF
- [ ] Test website locally
- [ ] Optional: Set up contact form backend
- [ ] Optional: Add custom favicon
- [ ] Push to GitHub
- [ ] Enable GitHub Pages

---

**Questions? Check `IMPLEMENTATION_SUMMARY.md` for full details!**
