# SFT21 Web Aplikacija - GitHub Pages Verzija

## 🚨 Važna Napomena o Video Datoteci

Ova verzija **NE SADRŽI** video datoteku `SFT21BusinessConcept.mp4` jer GitHub ima ograničenje od 25MB po datoteci, a video je 650MB.

## 📦 Sadržaj GitHub Verzije

```
sft21-github-version/
├── index.html              # Glavna stranica (bez video sekcije)
├── inpack.html             # Investicijski paketi
├── odluka.html             # Stranica za odluke
├── izbor.html              # Izbor opcija
├── prikaz_opcije.html      # Prikaz opcija
├── prva_kartica.html       # Prva kartica
├── druga_kartica.html      # Druga kartica
├── treca_kartica.html      # Treća kartica
├── cetvrta_kartica.html    # Četvrta kartica
├── peta_kartica.html       # Peta kartica
└── README.md               # Ove upute
```

## 🚀 GitHub Pages Deployment - Korak po Korak

### 1. Priprema GitHub Repository

1. **Idite na GitHub:**
   - Otvorite [github.com](https://github.com)
   - Prijavite se ili registrirajte novi račun

2. **Kreirajte novi repository:**
   - Kliknite zeleni gumb **"New"** ili **"New repository"**
   - **Repository name:** `sft21-website` (ili bilo koje ime)
   - **Važno:** Označite **"Public"** (obavezno za besplatno GitHub Pages)
   - Označite **"Add a README file"**
   - Kliknite **"Create repository"**

### 2. Upload Datoteka

1. **U novom repository:**
   - Kliknite **"uploading an existing file"**
   - Povucite **SVE HTML datoteke** iz ove mape
   - **NE upload-ajte** video datoteku (prevelika je)

2. **Commit promjene:**
   - Scroll dolje do "Commit changes"
   - Napišite poruku: "Dodavanje SFT21 web aplikacije"
   - Kliknite **"Commit changes"**

### 3. Aktiviranje GitHub Pages

1. **Idite na Settings:**
   - Kliknite **"Settings"** tab u vrhu repository

2. **Konfigurirajte Pages:**
   - U lijevom meniju kliknite **"Pages"**
   - Pod **"Source"** odaberite **"Deploy from a branch"**
   - **Branch:** odaberite **"main"**
   - **Folder:** odaberite **"/ (root)"**
   - Kliknite **"Save"**

3. **Pristup stranici:**
   - Stranica će biti dostupna na: `https://[vaše-korisničko-ime].github.io/[ime-repository]`
   - Primjer: `https://marko123.github.io/sft21-website`
   - **Napomena:** Može potrajati 5-10 minuta da se aktivira

## 🎥 Rješenja za Video Datoteku

### Opcija 1: YouTube Upload (Preporučeno)
1. Upload-ajte video na YouTube
2. Kopirajte embed kod
3. Zamijenite video sekciju u `index.html`:

```html
<div class="video-section">
    <h2><i class="fas fa-video"></i> SFT21 Business Concept</h2>
    <div class="video-container">
        <iframe width="100%" height="400" 
                src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
                frameborder="0" allowfullscreen></iframe>
    </div>
</div>
```

### Opcija 2: Vimeo Upload
1. Upload-ajte video na Vimeo
2. Kopirajte embed kod
3. Zamijenite u `index.html`

### Opcija 3: Google Drive
1. Upload-ajte video na Google Drive
2. Postavite na "Anyone with the link can view"
3. Kopirajte shareable link
4. Dodajte link u stranicu

### Opcija 4: Vanjski Hosting
- Koristite Netlify, Vercel ili Firebase za kompletnu verziju s video datotekom
- Ove platforme imaju veća ograničenja za datoteke

## 🔧 Ažuriranje Stranice

### Dodavanje Video Linka
Ako imate video na vanjskoj platformi, ažurirajte `index.html`:

1. Pronađite sekciju `.video-info-section`
2. Zamijenite s:

```html
<div class="video-section">
    <h2><i class="fas fa-video"></i> SFT21 Business Concept</h2>
    <div class="video-container">
        <!-- YouTube embed -->
        <iframe width="100%" height="400" 
                src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
                frameborder="0" allowfullscreen></iframe>
    </div>
</div>
```

### Ažuriranje Sadržaja
1. Uredite datoteke lokalno
2. Upload-ajte na GitHub (drag & drop)
3. Commit promjene
4. Stranica će se automatski ažurirati

## ✅ Prednosti GitHub Pages Verzije

- **Besplatno hostovanje**
- **Automatski HTTPS**
- **Globalna CDN mreža**
- **Jednostavno ažuriranje**
- **Pouzdanost 99.9%**
- **Custom domena podrška**

## ⚠️ Ograničenja

- **Maksimalno 25MB po datoteci**
- **Maksimalno 1GB ukupno**
- **Samo statične stranice**
- **Nema server-side procesiranja**

## 🆘 Rješavanje Problema

### Stranica se ne učitava
- Provjerite da je repository "Public"
- Provjerite da je Pages aktiviran
- Pričekajte 5-10 minuta za aktivaciju

### 404 Error
- Provjerite da je `index.html` u root direktoriju
- Provjerite imena datoteka (case sensitive)

### Stilovi se ne učitavaju
- Svi CSS stilovi su ugrađeni u HTML datoteke
- Nema vanjskih ovisnosti

## 📞 Podrška

- [GitHub Pages dokumentacija](https://docs.github.com/en/pages)
- [GitHub Community Forum](https://github.community/)

---

## 🎯 Sljedeći Koraci

1. **Upload-ajte datoteke na GitHub**
2. **Aktivirajte GitHub Pages**
3. **Upload-ajte video na YouTube/Vimeo**
4. **Ažurirajte index.html s video linkom**
5. **Testirajte stranicu**

**Vaša stranica će biti javno dostupna na GitHub Pages URL-u!** 🚀

