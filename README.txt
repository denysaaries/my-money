MY MONEY - PWA

Upload SEMUA file berikut ke root repository GitHub:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

GitHub Pages:
Settings > Pages > Deploy from a branch > main > /root

Install di HP:
Android/Chrome:
1. Buka URL GitHub Pages sekali.
2. Menu browser > Add to Home screen / Install app.
3. Ikon My Money akan muncul di Home Screen.

iPhone/Safari:
1. Buka URL GitHub Pages.
2. Share.
3. Add to Home Screen.

Catatan:
- Data disimpan lokal di browser/HP.
- Update file di GitHub tidak menghapus history selama localStorage key "myMoneyData" tetap sama.
- Versi ini otomatis membaca history pengeluaran lama dan mempertahankan nilai tabungan lama.


UPDATE v2 - SPACING IPHONE
- Header Home, Tabungan, History, dan Atur dibuat turun agar tidak mepet status bar/notch.
- Navbar bawah dibuat lebih ringkas.
- Semua halaman diberi ruang bawah agar konten tidak tertutup navbar.
- Service worker cache dinaikkan ke v5 agar update lebih mudah terbaca.

Jika tampilan lama masih muncul:
1. Buka web di Safari.
2. Refresh halaman.
3. Jika sudah dipasang ke Home Screen, tutup aplikasi My Money lalu buka lagi.
