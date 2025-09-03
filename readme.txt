============================================================
   ⚡ SEMS PORTAL SCRAPER – GEDUNG 3 TEKNIK ELEKTRO ⚡
============================================================

   🔹 Scraper otomatis untuk SEMS Portal UNS
   🔹 Ambil data energi dari dashboard monitoring
   🔹 Kirim data langsung ke API iotlab-uns.com

============================================================
✨ Fitur Utama
============================================================
✅ Login otomatis ke SEMS Portal  
✅ Klik otomatis "Gedung 3 Teknik" → pindah ke tab monitoring  
✅ Refresh halaman setiap 40–60 menit (acak)  
✅ Ambil data energi:
   • PV Generation Today  
   • Income Today  
   • Total Generation  
   • Total Income  
   • Power (Daya)  
✅ Upload data ke API  
✅ Auto relogin jika sesi login kadaluarsa  

============================================================
🛠️ Persyaratan
============================================================
- Python 3.8+  
- Browser: Firefox  
- Paket Python:  
  • selenium  
  • webdriver-manager  
  • requests  
- (Opsional untuk server tanpa GUI) → xvfb  

============================================================
⚙️ Instalasi
============================================================
1️⃣ Clone repository  
   git clone https://github.com/username/repo-name.git  
   cd repo-name  

2️⃣ Buat virtual environment  
   python3 -m venv venv  
   source venv/bin/activate  

3️⃣ Install dependency  
   pip install --upgrade pip  
   pip install -r requirements.txt  

============================================================
▶️ Menjalankan Script
============================================================
💻 Dengan GUI (desktop/server dengan tampilan):  
   python scrapping.py  

🌐 Tanpa GUI (Linux headless server):  
   sudo apt install -y xvfb  
   xvfb-run -a python scrapping.py  

============================================================
📦 File requirements.txt
============================================================
selenium  
webdriver-manager  
requests  

============================================================
🛑 Stop Script
============================================================
Tekan CTRL + C di terminal untuk menghentikan.  

============================================================
📌 Catatan
============================================================
- Script berjalan selamanya sampai dihentikan manual.  
- Interval scraping: random 40–60 menit.  
- Pastikan koneksi internet stabil agar data berhasil dikirim.  

============================================================
📜 Lisensi
============================================================
Proyek ini dibuat untuk kebutuhan Smart ENMS UNS.  
Silakan gunakan sesuai kebutuhan dengan mencantumkan kredit.  
============================================================
