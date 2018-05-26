How To Build Your First Website @ Purwadhika
============================================

Selamat datang ke repositori untuk workshop "How to build your first website" di Purwadhika Startup School 27 Mei 2018.
Repositori ini berisikan _file-file_ yang dibutuhkan selama workshop ini beserta beberapa petunjuk lain.
Silakan ikut petunjuk di bawah untuk dapat mengikuti workshop dengan baik.

Setup Tools
-----------
1. Download dan install SublimeText 3 di laman https://www.sublimetext.com/3
2. Daftar CodePen di laman https://www.codepen.io
3. Daftar Free Code Camp di https://www.freecodecamp.org


Setup Tambahan untuk SublimeText 3
----------------------------------
Prerequisites: Google Chrome telah terinstalasi di komputer. Jika belum install di laman https://www.google.com/chrome/

1. Pastikan jendela **Sublime Text** terbuka.
2. Pilih menu **Tools** --> **Build System** --> **New Build System...**.
3. Ketik di dalam kurung kurawal (antara karakter "{" dan "}") perintah berikut:

     	"cmd": ["<ALAMAT_DIREKTORI_CHROME>", "$file"]

   Note: Ganti **<ALAMAT_DIREKTORI_CHROME>** dengan alamat absolut _(aboslute path)_ ke aplikasi Google Chrome di komputer Anda.

4. Klik menu **File** --> **Save** (atau shortcut di keyboard `Ctrl+S`) untuk menyimpan build system tersebut.
5. Berikan nama `Chrome.sublime-build`.
6. Tutup jendela file `Chrome.sublime-build` tersebut.
