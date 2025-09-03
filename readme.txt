# ⚡ SEMS Portal Scraper – Gedung 3 Teknik Elektro

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Selenium](https://img.shields.io/badge/selenium-latest-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

> 🚀 **Scraping otomatis dari SEMS Portal** untuk Gedung 3 Teknik Elektro.  
> Data energi diambil secara periodik, kemudian dikirim ke API `iotlab-uns.com`.

---

## ✨ Fitur Utama
- 🔑 **Login otomatis** ke SEMS Portal
- 🏢 Klik otomatis **Gedung 3 Teknik** dan pindah ke tab monitoring
- 🔄 Refresh halaman acak setiap **40–60 menit**
- 📊 Ambil data real-time:
  - PV Generation Today
  - Income Today
  - Total Generation
  - Total Income
  - Power (Daya)
- ☁️ Kirim data otomatis ke API
- ♻️ **Auto-relogin** jika sesi login kadaluarsa

---

## 📦 Persyaratan
- Python **3.8+**
- Browser: **Firefox**
- Paket Python:
  - `selenium`
  - `webdriver-manager`
  - `requests`
- (Opsional) **xvfb** → jika dijalankan di server Linux tanpa GUI

---

## ⚙️ Instalasi

1. **Clone repository**
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
