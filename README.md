### 1. Jelaskan secara singkat apa itu JavaScript dan kegunaannya! [5 Poin]
JavaScript adalah bahasa pemrograman yang berjalan di browser (dan juga di server lewat Node.js) untuk membuat halaman web menjadi dinamis dan interaktif.

Kegunaannya antara lain:
- Memanipulasi elemen HTML/CSS (DOM)
- Memvalidasi form
- Menangani event seperti klik dan input
- Menampilkan dialog seperti `prompt` dan `alert`
- Mengambil data dari server tanpa reload halaman (AJAX/fetch)

### 2. Jelaskan secara singkat apa itu jQuery dan kegunaannya! [5 Poin]
jQuery adalah library JavaScript yang ringan dan dibuat untuk menyederhanakan penulisan kode JavaScript. Dengan semboyan "write less, do more", jQuery mempermudah:
- Pemilihan elemen HTML
- Manipulasi DOM
- Penanganan event
- Animasi (hide, show, fade)
- AJAX
- Kompatibilitas di berbagai browser

### 3.	Jelaskan perbedaan JavaScript dan jQuery! [10 Poin]

| Aspek | JavaScript | jQuery |
|---|---|---|
| Jenis | Bahasa pemrograman | Library yang dibangun di atas JavaScript |
| Instalasi | Langsung didukung browser | Harus dimuat dulu (CDN atau file lokal) |
| Penulisan kode | Lebih panjang, contoh: `document.getElementById("kotak").style.display = "none";` | Lebih ringkas, contoh: `$("#kotak").hide();` |
| Kompatibilitas browser | Perlu penyesuaian manual untuk browser lama | Sudah menangani perbedaan antar-browser |
| Cakupan | Bisa dipakai di client dan server (Node.js) | Hanya untuk sisi client (browser) |
| Kecepatan | Sedikit lebih cepat karena tanpa lapisan tambahan | Sedikit lebih lambat karena ada overhead library |
