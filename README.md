Quasar Flash Games
Direktori game SWF dibangun dengan Kerangka Quasar
Motivasi
Dengan Adobe Flash Player EOL diumumkan pada akhir tahun 2020, sejumlah besar permainan SWF dan sumber daya pendidikan mungkin tidak dapat dimainkan di hampir semua browser web. Browser web utama sudah semakin menonaktifkan dukungan plugin Adobe Flash Player, membuat penggunaan game ini semakin sulit.
Untuk menyediakan cara untuk memastikan permainan akan tetap dapat dimainkan untuk beberapa waktu setelah Flash Player EOL, kami sedang mengembangkan peramban permainan SWF berbasis Electron ini dengan Quasar Framework. Kami terus memperbarui, dan kami akan menempelnya di plugin Flash Player terbaru dan rilis Electron setelah EOL itu. Ini mendukung game online dan offline.
Instruksi
1. Kloning repositori ini.
2. Pergi ke direktori quasar-electron-flash-games.
3. Jalankan instal npm.
4. Unduh Adobe Flash Player untuk OS dan arsitektur Anda, dan ekstrak plugin dengan manifes.json ke direktori yang sesuai di bawah src-electron / ppapi-flash-plugin:
o darwin / x64 untuk 64-bit macOS
 Tidak ada MacOS 32-bit sejak rilis "Lion".
o linux / x64 untuk Linux 64-bit
o linux / ia32 untuk Linux 32-bit
o win32 / x64 untuk Windows 64-bit
o win32 / ia32 untuk Windows 32-bit
5. Tambahkan game baru ke direktori src / statika / game. Lihat Struktur File Game untuk info lebih lanjut.
6. Jalankan npx quasar dev -m electron untuk dijalankan dalam mode pengembangan.
o Anda dapat menghilangkan npx jika Anda memiliki @ quasar / cli diinstal secara global di sistem Anda.
7. Setelah selesai, jalankan npx quasar build -m electron untuk membangun paket final.
o Anda dapat menghilangkan npx jika Anda memiliki @ quasar / cli diinstal secara global di sistem Anda.
