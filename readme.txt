# Scraping SEMS Portal (Gedung 3 Teknik)

Script ini digunakan untuk **scraping data monitoring SEMS Portal** (Gedung 3 Teknik Elektro) secara otomatis menggunakan **Python + Selenium**.  
Data hasil scraping akan dikirim ke API `http://iotlab-uns.com/smart-enms/api/add-gwdata`.

---

## 🚀 Fitur
- Login otomatis ke SEMS Portal
- Klik otomatis `Gedung 3 Teknik` dan pindah ke tab monitoring
- Refresh halaman acak setiap **40–60 menit**
- Ambil data:
  - PV Generation Today
  - Income Today
  - Total Generation
  - Total Income
  - Power (Daya)
- Upload data ke API secara otomatis
- Auto-relogin jika sesi kadaluarsa

---

## 📦 Persyaratan
- Python **3.8+**
- Paket berikut:
  - `selenium`
  - `webdriver-manager`
  - `requests`

Jika server tanpa GUI (misalnya di Linux VPS), dibutuhkan:
- `xvfb`

---

## 🔧 Instalasi

1. Clone repo ini atau download script:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
