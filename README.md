# PUNDI Web — Prototype 0.1

Web application responsif untuk UMKM. Identitas: Forest Green `#054F2E`, Soft Cream `#EBF1E6`, Mint `#D3E9DC`, Warm Yellow `#F4DE91`, Deep Green `#1E3929`.

## Jalankan di laptop
1. Instal Node.js LTS: https://nodejs.org/
2. Ekstrak proyek, buka terminal di folder ini.
3. Jalankan `npm install` lalu `npm run dev`.
4. Buka alamat lokal Vite, biasanya http://localhost:5173.

## Deploy online ke Vercel
1. Unggah isi folder ini ke repository GitHub.
2. Masuk Vercel, pilih Add New → Project, impor repository.
3. Framework preset: Vite; Build command: `npm run build`; Output directory: `dist`.
4. Klik Deploy. Dokumentasi: https://vercel.com/docs/deployments

## Fitur prototype
Dashboard, transaksi manual, laporan sederhana, manajemen stok demo, halaman Scan, Voice, dan Advisor demo. Transaksi disimpan di localStorage browser.

## Batasan sebelum dipakai sungguhan
Belum ada autentikasi, database online, sinkronisasi perangkat, backend, OCR, speech-to-text, atau AI API. Data transaksi tersimpan hanya di browser/perangkat ini. Scan, Voice, dan Advisor masih antarmuka/demo. Untuk produksi, tambahkan backend dan database (misalnya Supabase/PostgreSQL), autentikasi, kontrol akses per usaha, backup, validasi server, serta integrasi AI/OCR dari backend. Jangan menaruh API key di frontend.
