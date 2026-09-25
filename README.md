# 🎬 Vidio Belajar — Frontend Mockup

Project ini adalah **frontend mockup** untuk platform video belajar, dibangun dengan **Vite + Tailwind CSS v4**.

---

## ⚙️ Setup Project (Setelah Clone / Pull)

### Prasyarat
Pastikan sudah terinstall di device:
- [Node.js](https://nodejs.org/) versi **18+**
- npm (sudah ikut serta saat install Node.js)

### Langkah-langkah

```bash
# 1. Clone repository (skip jika sudah di-pull)
git clone <url-repository>
cd vidio-belajar

# 2. Install semua dependencies
npm install

# 3. Jalankan dev server
npm run dev
```

Setelah `npm run dev`, terminal akan menampilkan URL lokal seperti:

```
  VITE v8.x.x  ready in xxx ms

  ➜  Local:   http://localhost:5173/
```

Buka URL tersebut di browser. ✅

---

## 🗺️ Navigasi Halaman (via URL)

Karena ini adalah **frontend mockup** (tanpa routing library), navigasi antar halaman dilakukan langsung melalui URL di browser.

| Halaman | URL |
|---|---|
| 🏠 Beranda (Landing Page) | `http://localhost:5173/src/beranda.html` |
| 📝 Register | `http://localhost:5173/src/register.html` |
| 🗂️ Root / Index | `http://localhost:5173/` |

> **Tip:** Cukup ganti bagian nama file di URL untuk berpindah halaman.  
> Contoh: dari `.../beranda.html` → `.../register.html`

---

## 📁 Struktur Project

```
vidio-belajar/
├── index.html           # Entry point utama
├── src/
│   ├── beranda.html     # Halaman beranda / landing page
│   ├── register.html    # Halaman registrasi
│   ├── style.css        # Stylesheet utama (Tailwind)
│   └── assets/          # Gambar, icon, dan aset lainnya
├── public/              # File statis (langsung diakses)
├── package.json
└── vite.config.ts
```

---

## 🛠️ Scripts yang Tersedia

| Command | Fungsi |
|---|---|
| `npm install` | Install semua dependencies |
| `npm run dev` | Jalankan dev server (mode development) |
| `npm run build` | Build untuk production |
| `npm run preview` | Preview hasil build production |

---

## 🧰 Tech Stack

- **Vite** `^8.3` — Build tool & dev server
- **Tailwind CSS** `^4.3` — Utility-first CSS framework
- **HTML** murni — Tanpa framework JS
