CARA PAKAI
==========
1. Upload SELURUH isi folder ini (bukan foldernya, tapi isinya) ke hosting kamu
   (misalnya lewat cPanel File Manager, FTP, atau layanan hosting my.id kamu),
   ke dalam folder public_html / root domain septiantelin.my.id.

2. Pastikan struktur di server persis seperti ini (semua sejajar, satu folder):
   - index.html
   - style.css
   - script.js
   - logo.svg
   - sitemap.xml
   - robots.txt

3. Setelah online, submit sitemap ke Google Search Console:
   https://search.google.com/search-console
   -> Tambahkan properti septiantelin.my.id -> menu "Sitemaps"
   -> masukkan: sitemap.xml -> Submit

4. Ganti nomor WhatsApp / link sosial media langsung di index.html
   kalau suatu saat berubah (cari bagian <section id="kontak"> atau <section id="sosial">).

CATATAN SEO
===========
- Judul & deskripsi halaman sudah diisi (tag <title> dan <meta name="description">)
  di bagian <head> index.html. Sesuaikan lagi kalau kontennya berkembang.
- File sitemap.xml & robots.txt sudah disiapkan dengan domain septiantelin.my.id.
  Kalau domain berubah, cari-ganti domain di kedua file itu + index.html.
- Data terstruktur (JSON-LD schema Person) sudah ditanam di index.html supaya
  Google bisa mengenali profil kamu lebih baik di hasil pencarian.
