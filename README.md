# KALA

Sakiceup, Sagala Katempo.

KALA adalah notch di tepi atas layar Windows. Jadwal sholat, lagu yang sedang diputar, meeting, dan notifikasi terlihat tanpa pindah jendela.

![Notch KALA](screens/notch.png)

Arahkan kursor atau klik notch untuk membuka panel. Pindah tab dengan swipe dua jari di touchpad, dock di bawah panel, atau tombol kiri-kanan. Tekan `Ctrl + Alt + K` untuk menyembunyikan atau memunculkannya.

## Pasang

Unduh `KALA_x.y.z_x64-setup.exe` dari halaman [Releases](https://github.com/rezamahendraaa23/KALA/releases/latest), lalu jalankan.

Installer belum memakai sertifikat code signing, jadi Windows SmartScreen bisa menampilkan peringatan. Pilih **More info**, lalu **Run anyway**.

Setelah terpasang, KALA memberi tahu saat ada versi baru. Pembaruan dipasang dari Pengaturan > Sistem.

## Fitur

### Home

Jam, ringkasan sholat, meeting, dan lagu, plus satu garis waktu untuk hari ini.

![Home](screens/home.png)

### Sholat

Jadwal harian per kota dari MyQuran, termasuk Imsak dan Terbit. Waktu yang sudah lewat bisa ditandai sudah sholat. Pengingat muncul 5 sampai 30 menit sebelumnya dan saat waktunya masuk.

![Sholat](screens/sholat.png)

### Musik

Mengikuti pemutar yang terdaftar di Windows, seperti Spotify dan browser. Bisa putar, jeda, ganti lagu, geser posisi, dan atur volume. Lirik sinkron dicari dari LRCLIB, KuGou, dan NetEase, dan barisnya bisa ikut tampil di notch.

![Musik](screens/musik.png)

### Agenda

Membaca kalender Lark lewat CalDAV, tanpa membuat aplikasi di Developer Console. Hanya membaca, tidak mengubah jadwal. Password didapat dari Lark: Settings > Calendar > CalDAV sync.

### Notifikasi

Notifikasi Windows tampil di notch dan tersimpan sebagai riwayat per aplikasi. Ada mode Jangan Ganggu, dan aplikasi tertentu bisa dibisukan.

### Fokus

Pomodoro dengan mode fokus, rehat, dan rehat panjang. Timer tetap terlihat di notch saat panel tertutup.

![Fokus](screens/fokus.png)

### Kirim file

Scan QR dari HP di Wi-Fi yang sama untuk mengirim file dua arah. File dari HP masuk ke `Downloads\KALA`.

![Kirim file](screens/kirim.png)

### Izin Claude Code

Permintaan izin Claude Code di VS Code bisa dijawab dari notch. Fitur ini mati sampai dinyalakan di Pengaturan > Sistem.

![Izin Claude Code](screens/izin.png)

## Pengaturan

Bentuk menempel atau melayang, posisi, ukuran, warna, transparansi, blur, urutan tab, dan gaya ikon baterai bisa diubah. Isi kiri, tengah, dan kanan notch bisa dipilih: jam, tanggal, baterai, sholat, meeting, CPU, RAM, internet, atau maskot.

![Pengaturan isi notch](screens/pengaturan-isi.png)

![Pengaturan tampilan](screens/pengaturan-tampilan.png)

## Batasan

- Dikembangkan dan diuji di Windows 11. Windows 10 belum diuji.
- Notifikasi hanya tertangkap dari aplikasi yang memakai notifikasi Windows. Aplikasi dengan pop-up sendiri tidak ikut.
- Lokasi meeting mengikuti data CalDAV dari Lark, yang bisa lebih singkat dari nama di aplikasi Lark.
- KuGou dan NetEase bukan API resmi, jadi sewaktu-waktu bisa berhenti bekerja.
- Kirim file tidak terenkripsi. Pakai hanya di Wi-Fi yang dipercaya.
- Windows Firewall akan meminta izin saat Kirim file pertama kali dipakai.

## Data

Pengaturan, riwayat notifikasi, dan jadwal tersimpan di laptop. Password CalDAV disimpan terenkripsi dengan akun Windows. Data yang keluar hanya:

- Kota yang dipilih, ke MyQuran.
- Judul, artis, album, dan durasi lagu, ke penyedia lirik.
- Permintaan kalender, ke server CalDAV Lark, kalau dihubungkan.
- Pemeriksaan versi baru, ke GitHub.

Dibuat oleh Reza Mahendra.
