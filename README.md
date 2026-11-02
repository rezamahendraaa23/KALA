# KALA

**Sakiceup, sagala katempo.** Sekedip mata, semua kelihatan.

[Lihat halaman KALA](https://rezamahendraaa23.github.io/KALA/)

KALA adalah notch di tepi atas layar Windows, dengan aplikasi pendamping di Android. Jadwal sholat, lirik lagu, meeting, dan izin Claude Code terlihat tanpa pindah jendela.

![Panel Home KALA](screens/home.png)

## Pasang

| Perangkat | Unduh | Catatan |
| --- | --- | --- |
| Windows | `KALA_x.y.z_x64-setup.exe` dari [Releases](https://github.com/rezamahendraaa23/KALA/releases/latest) | Belum memakai sertifikat code signing. Kalau SmartScreen muncul, pilih **More info**, lalu **Run anyway**. |
| Android 10+ | [`KALA-android.apk`](https://github.com/rezamahendraaa23/KALA/releases/latest/download/KALA-android.apk) | Dipasang di luar Play Store, jadi Android bisa memperingatkan. |

Keduanya memberi tahu saat ada versi baru. Di laptop, pembaruan dipasang dari Pengaturan > Sistem. Di HP, lewat bar **Perbarui** atau tombol **Cek pembaruan** di tab Laptop.

**Cara pakai:** arahkan kursor atau klik notch untuk membuka panel. Pindah tab dengan scroll mouse, swipe dua jari, dock di bawah panel, atau tombol kiri-kanan. `Ctrl + Alt + K` menyembunyikan dan memunculkan notch.

## Di laptop

### Sholat

Jadwal harian per kota dari MyQuran, termasuk Imsak dan Terbit, dengan pengingat 5 sampai 30 menit sebelumnya. Langitnya mengikuti cuaca dari Open-Meteo, di kota pilihanmu atau di kecamatan yang kamu isi sendiri: matahari, awan, hujan, atau petir, lalu bulan dan bintang saat malam.

![Tab Sholat](screens/sholat.png)

### Musik

Mengikuti pemutar yang terdaftar di Windows, seperti Spotify dan browser. Lagu dari Spotify memakai sampulnya dan aksen hijau Spotify. Lirik sinkron dicari dari LRCLIB, QQ Music, NetEase, KuGou, dan lyrics.ovh. Tombol komentar menampilkan lirik di panel dan notch; kalau dimatikan, notch hanya menampilkan equalizer.

![Tab Musik](screens/musik.png)

### Agenda

Membaca kalender Lark lewat CalDAV, tanpa membuat aplikasi di Developer Console, dan tidak mengubah jadwal. Password didapat dari Lark: Settings > Calendar > CalDAV sync. CalDAV hanya mengirim kode ruangan, jadi nama lengkapnya bisa diisi di Pengaturan > Jadwal Lark.

![Tab Agenda](screens/agenda.png)

### Fokus

Pomodoro dengan mode fokus, rehat, dan rehat panjang. Selama sesi fokus, notifikasi ditahan dan tetap masuk riwayat, sedangkan izin Claude Code tetap muncul.

![Tab Fokus](screens/fokus.png)

### Kirim file

Kalau HP tersambung lewat aplikasi, tab ini langsung siap. Perangkat lain cukup memindai QR di Wi-Fi yang sama. File dari HP masuk ke `Downloads\KALA`.

![Tab Kirim](screens/kirim.png)

### Pusat Kontrol

Wi-Fi, Bluetooth, hotspot, mikrofon, kecerahan, dan volume di satu tempat, ditambah kunci layar, tidur, matikan atau mulai ulang (dengan konfirmasi), tangkap layar, folder Unduhan, dan mode hening. Panah di kartu Wi-Fi membuka daftar jaringan untuk disambungkan atau diputus. Panah di kartu Bluetooth menampilkan perangkat yang sudah disandingkan beserta statusnya.

### Modul lain

- **Claude:** daftar sesi Claude Code di laptop ini, yang sedang bekerja atau sudah selesai, dengan tombol untuk membuka foldernya di VS Code.
- **Catatan & Tugas:** catatan cepat dan daftar tugas dengan tanggal, disaring Hari ini, Mendatang, atau Semua.
- **Monitor:** CPU, GPU, RAM, dan kecepatan internet dengan grafik kecil.
- **Clipboard:** teks dan gambar yang disalin, bisa dicari dan disematkan. Mati sampai dinyalakan. Riwayat hanya di memori, sematan disimpan terenkripsi.
- **Air:** target minum harian, gelas yang bisa diatur, dan pengingat tiap 90 menit antara 08.00 dan 21.00.
- **Rak Berkas:** jemuran untuk menaruh sampai 8 file sebentar, lalu ditarik lagi ke WhatsApp, Discord, atau folder lain. Klik untuk memilih beberapa file dan tarik semuanya sekaligus, atau tekan **Kirim ke HP** supaya file siap diambil di tab Berkas pada aplikasi HP. Menyeret file ke notch langsung membuka tab ini.

Clipboard, Air, dan Rak Berkas disembunyikan dulu. Munculkan di Pengaturan > Tab & Navigasi.

### Yang lain

- **Izin Claude Code:** permintaan izin di VS Code bisa dijawab dari notch. Mati sampai dinyalakan di Pengaturan > Sistem.
- **Notifikasi:** notifikasi Windows tampil di notch dan tersimpan sebagai riwayat, dengan filter belum dibaca, bisukan per aplikasi, dan jangan ganggu. Klik notifikasi untuk membuka aplikasinya; Windows tidak memberi tautan ke chat tertentu, jadi yang terbuka aplikasinya saja. Tab-nya bisa dimunculkan di Pengaturan > Tab & Navigasi.
- **Penanda singkat:** animasi saat Caps Lock atau mode hening berubah, dan peringatan kalau CPU atau RAM di atas 90% selama satu menit.
- **Isi notch:** kiri, tengah, dan kanan bisa diisi maskot, sholat, cuaca, status Claude, meeting, fokus, lagu, hitung mundur, jam pulang, tanggal Hijriah, atau info sistem. Ada enam maskot untuk dipilih.
- **Earphone:** notch memberi tahu saat TWS atau headset tersambung dan terputus.
- **Tampilan:** bentuk, posisi, ukuran, warna, transparansi, dan urutan tab bisa diatur.

![Pengaturan Tampilan](screens/pengaturan.png)

## Di HP

Di laptop, buka Pengaturan > Sistem > **Hubungkan HP**, lalu pindai QR dari aplikasi. HP dan laptop harus di Wi-Fi yang sama.

<p>
  <img src="screens/android-izin.png" width="240" alt="Izin Claude Code di HP">
  <img src="screens/android-jadwal.png" width="240" alt="Jadwal dan langit di HP">
  <img src="screens/android-musik.png" width="240" alt="Musik dan lirik di HP">
</p>

- **Izin Claude Code:** perintah tampil utuh dan harus digeser untuk mengizinkan. Bisa juga dijawab dari notifikasi setelah HP dibuka.
- **Izinkan otomatis:** aktif 8 jam selama HP tersambung. Perintah yang dikenali berisiko, seperti hapus file dan `git push`, tetap ditanya, tapi daftar itu tidak menangkap semuanya.
- **Baca dan balas Claude:** mati sampai dinyalakan di laptop. Sesi dibuka dengan sidik jari. Balasan dari HP tampil di HP, tidak di panel VS Code yang sedang terbuka. Tiap perintah yang bisa mengubah sesuatu harus diizinkan dulu, dan tidak dijawab berarti ditolak.
- **Jadwal dan musik:** waktu sholat, cuaca, meeting hari ini, pengingat meeting, kontrol lagu, dan lirik sinkron.
- **Berkas dan clipboard:** kirim dua arah, termasuk lewat menu Bagikan di Android. File yang sudah diunduh tinggal dibuka, dan **Buka folder** membawa ke folder Download.
- **Kendali laptop:** kunci layar, mode hening, dan volume dari tab Laptop. Menidurkan laptop harus digeser lalu dibuka dengan sidik jari.
- **Sambung lagi:** setelah diputus, tekan Sambung lagi di HP lalu izinkan di notch, tanpa pindai ulang.

## Data

Pengaturan, riwayat notifikasi, dan jadwal tersimpan di laptop. Password CalDAV dan kunci HP disimpan terenkripsi dengan akun Windows. Data yang keluar dari laptop hanya:

| Data | Ke mana |
| --- | --- |
| Kota yang dipilih | MyQuran dan Open-Meteo |
| Lokasi cuaca, kalau kamu mengisinya | Open-Meteo |
| Judul, artis, album, dan durasi lagu | Penyedia lirik |
| Permintaan kalender | Server CalDAV Lark, kalau dihubungkan |
| Pemeriksaan versi baru | GitHub |
| Jadwal, lagu, clipboard, izin, dan transkrip Claude yang dinyalakan | HP yang kamu hubungkan, lewat Wi-Fi lokal dan terenkripsi |
| Isi berkas yang dikirim | Perangkat tujuan, lewat Wi-Fi lokal dan **tidak terenkripsi** |

## Batasan

- Dikembangkan dan diuji di Windows 11. Windows 10 belum diuji.
- Fitur HP hanya jalan di Wi-Fi yang sama, dan laptop harus menyala.
- Notifikasi hanya tertangkap dari aplikasi yang memakai notifikasi Windows.
- Nama ruangan dari Lark hanya berupa kode sampai kamu melengkapinya.
- QQ Music, NetEase, dan KuGou bukan API resmi, jadi sewaktu-waktu bisa berhenti bekerja.
- Windows Firewall akan meminta izin saat Kirim file atau HP pertama kali dipakai.
- Daftar Wi-Fi butuh izin Lokasi Windows untuk aplikasi desktop. Perangkat Bluetooth hanya ditampilkan; menyambungkannya tetap lewat Pengaturan Windows.
- Kalau lagu diputar dari browser, sampul tidak ditampilkan karena browser hanya mengirim logonya sendiri.

Tangkapan layar memakai jadwal dan lagu contoh.

Dibuat oleh Reza Mahendra.
