# Veo-promt-generator

Generator Prompt Gambar ke Veo AI
Selamat datang di Generator Prompt Gambar ke Veo AI! Aplikasi web ini membantu para content creator untuk dengan mudah menghasilkan prompt video yang detail dan profesional dari gambar yang diunggah. Dirancang untuk bekerja optimal dengan Google Veo dan platform AI generator video lainnya, alat ini mengubah visi Anda menjadi instruksi AI yang presisi.
Fitur Utama
 * AI-Powered Image Analysis: Secara otomatis menganalisis gambar Anda untuk menyarankan subjek utama dan elemen kunci, menghemat waktu Anda.
 * Kontrol Prompt Detail: Kustomisasi setiap aspek video Anda: Aksi, Emosi, Latar Belakang, Sudut Kamera, Gerakan Kamera, Pencahayaan, dan banyak lagi.
 * Pilihan Gaya Video Luas: Pilih dari gaya sinematik, animasi, drone, Ghibli, Pixar, hingga hyperrealistic dan timelapse.
 * Ekspresi & Aksen Bahasa Lokal: Tentukan ekspresi bicara dan aksen bahasa Indonesia spesifik (Jawa, Sunda, Batak, dll.) untuk dialog Anda.
 * Prompt Dwibahasa (ID & EN): Dapatkan prompt yang siap disalin dalam Bahasa Indonesia dan terjemahan profesional ke Bahasa Inggris.
 * Integrasi Mudah ke Gemini: Tombol langsung untuk membuka Gemini, memudahkan Anda menempel prompt dan memulai kreasi.
 * Akses Terbatas & Premium: Nikmati 15 prompt gratis, lalu dapatkan akses unlimited dengan pembelian sekali bayar.
Cara Menggunakan (Versi Web)
 * Unggah Gambar: Pilih gambar yang ingin Anda jadikan dasar prompt video.
 * Hasilkan Prompt Image: Klik tombol "Hasilkan Prompt Image" untuk mendapatkan saran subjek dari AI berdasarkan gambar Anda.
 * Sesuaikan Detail Prompt: Isi kolom-kolom detail seperti Aksi, Ekspresi, Latar Belakang, Waktu, Sudut Kamera, Gerakan Kamera, Pencahayaan, Gaya Video, Rasio Aspek, Suasana Video, Backsound, Kalimat yang Diucapkan, Ekspresi Bicara, Aksen Bahasa, dan Detail Tambahan.
 * Hasilkan Prompt: Klik tombol "Hasilkan Prompt" untuk mendapatkan prompt yang detail dalam Bahasa Indonesia dan Inggris.
 * Salin & Gunakan: Salin prompt yang dihasilkan, lalu klik "Buka Gemini" untuk menempelkannya ke platform AI favorit Anda.
 * Akses Unlimited: Setelah 15 kali penggunaan, Anda akan diminta kata sandi. Silakan order aplikasi untuk akses unlimited.
Instalasi (Untuk Developer)
Untuk menjalankan proyek ini secara lokal:
 * Clone Repositori:
   git clone https://github.com/USERNAME_ANDA/NAMA_REPOSITORI_ANDA.git
cd veo-prompt-generator

   (Ganti USERNAME_ANDA dan NAMA_REPOSITORI_ANDA dengan detail GitHub Anda.)
 * Instal Dependensi:
   npm install
# atau
# yarn install

 * Konfigurasi Firebase & API Key Gemini:
   * Buat proyek baru di Firebase Console.
   * Tambahkan aplikasi web untuk mendapatkan konfigurasi Firebase Anda.
   * Untuk keamanan API Key Gemini: Sangat disarankan untuk membuat backend sederhana (misalnya dengan Node.js Express atau fungsi serverless) yang akan mem-proxy permintaan ke Google Gemini API. Ini akan menyembunyikan API Key Anda dari sisi klien.
   * Jika Anda tetap memanggil langsung dari frontend (tidak direkomendasikan untuk produksi): Buka src/App.js dan ganti const apiKey = ""; dengan API Key Gemini Anda.
   * Buka src/App.js dan ganti const firebaseConfig = { ... }; dengan konfigurasi Firebase Anda. Sesuaikan juga logika autentikasi jika Anda tidak ingin menggunakan autentikasi anonim default.
 * Jalankan Aplikasi:
   npm start
# atau
# yarn start

   Aplikasi akan berjalan di http://localhost:3000.
Deployment
Proyek ini dibuat dengan Create React App. Untuk deployment ke produksi:
 * Build Aplikasi:
   npm run build
# atau
# yarn build

   Ini akan membuat folder build dengan file-file statis yang siap di-deploy.
 * Deploy ke Hosting:
   * Vercel / Netlify: Sangat direkomendasikan karena kemudahan integrasi dengan GitHub, CDN bawaan, dan SSL gratis. Cukup hubungkan repositori GitHub Anda dan mereka akan otomatis mendeploy.
   * Firebase Hosting: Jika Anda menggunakan Firebase untuk backend, ini adalah pilihan yang baik.
   * Layanan Hosting Lain: Anda dapat mengunggah isi folder build ke layanan hosting web statis mana pun.
Kontak
Untuk pertanyaan, dukungan, atau order akses unlimited:
 * WhatsApp: <a href="[https://wa.me/6281389709847](https://wa.me/6281389709847)" target="_blank" rel="noopener noreferrer">0813 89709847</a>
 * TikTok: <a href="[https://www.tiktok.com/@smokervibes.id](https://www.tiktok.com/@smokervibes.id)" target="_blank" rel="noopener noreferrer">@smokerVibes.id</a>
Terima kasih telah menggunakan Generator Prompt Gambar ke Veo AI!
