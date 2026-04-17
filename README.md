# Digital Sanctuary — APK Builder

## Sirf Phone Se APK Kaise Banayein (5 Steps)

### Step 1 — GitHub Account Banao
- Phone mein **github.com** kholo
- "Sign up" karo (free hai)

### Step 2 — New Repository Banao
- Login ke baad "+" icon → "New repository"
- Name: `digital-sanctuary`
- **Public** select karo
- "Create repository" tap karo

### Step 3 — Files Upload Karo
- Repository mein "uploading an existing file" tap karo
- Is ZIP ki saari files upload karo (ek ek karke ya folder se)
- Structure aisi honi chahiye:
  ```
  .github/workflows/build.yml
  www/index.html
  package.json
  capacitor.config.json
  ```
- "Commit changes" tap karo

### Step 4 — APK Build Hoga Automatically
- Commit karte hi GitHub Actions **automatically** APK banana shuru kar dega
- "Actions" tab mein dekho — green tick aane ka wait karo (~5-8 min)

### Step 5 — APK Download Karo
- Actions → Latest run → "Artifacts" section
- **"DigitalSanctuary-APK"** download karo
- Phone mein install karo ✅

---
Data localStorage mein save hota hai — refresh/close se nahi jaata!
