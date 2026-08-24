# Modul 1: Fondasi Arsitektur Web dan Semantik HTML5

Repositori kerja praktikum mata kuliah Pemrograman Website, Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.

| Keterangan | Rincian |
| --- | --- |
| Mata Kuliah | Pemrograman Website |
| Modul | 1 dari 11 |
| Topik | Fondasi Arsitektur Web dan Semantik HTML5 |
| Program Studi | Teknik Informatika |
| Institusi | Fakultas Teknik, Universitas Hasanuddin |

## Deskripsi Modul

Modul ini menjadi gerbang utama mata kuliah. Pembahasan dimulai dari cara kerja ekosistem web, perjalanan permintaan dan tanggapan pada protokol HTTP, hingga penyusunan dokumen HTML5 yang semantis dan valid menurut standar W3C. Struktur dokumen yang dibangun pada modul ini menjadi fondasi bagi seluruh modul berikutnya.

## Capaian Pembelajaran

Setelah menyelesaikan modul ini, mahasiswa diharapkan mampu:

1. **Menjelaskan ekosistem web**
   - Memahami komponen utama World Wide Web.
   - Menguraikan siklus hidup request dan response pada HTTP serta HTTPS.
2. **Menganalisis peran klien dan server**
   - Membedakan tanggung jawab sisi klien dan sisi server.
   - Memetakan pembagian kerja pada arsitektur aplikasi web modern.
3. **Menyusun dokumen HTML5 semantik**
   - Memilih elemen semantik yang tepat sesuai peran kontennya.
   - Mengoptimalkan aksesibilitas dan penjelajahan mesin pencari.
4. **Memvalidasi dokumen HTML**
   - Menggunakan validator standar W3C.
   - Memastikan kepatuhan terhadap spesifikasi sintaksis web global.

## Cakupan Materi

- Ekosistem internet dan World Wide Web beserta komponen pengenal sumber daya.
- Protokol HTTP dan HTTPS, dari DNS lookup hingga penutupan koneksi.
- Arsitektur client-server dan pembagian peran front-end serta back-end.
- Critical rendering path: parsing, DOM Tree, CSSOM Tree, Render Tree, layout, dan painting.
- Elemen semantik utama HTML5 beserta perannya dalam tata letak halaman.
- Validasi W3C, aksesibilitas WCAG 2.1 dan ARIA, serta markup ramah mesin pencari.

## Hands-on Lab

Membangun halaman profil portofolio akademik mahasiswa yang tersusun dari elemen semantik dan lolos validasi W3C.

Kode hasil praktikum terbimbing pada sesi kelas disimpan di dalam repositori ini. Ikuti langkah demonstrasi yang dipandu dosen atau asisten, lalu bandingkan hasil pekerjaan Anda dengan berkas rujukan yang tersedia.

## Struktur Berkas

```
MK-Pemrograman-Website-Modul-01/
  index.html
```

## Petunjuk Penggunaan

### Kebutuhan Perangkat
1. Peramban modern seperti Google Chrome, Mozilla Firefox, atau Microsoft Edge.
2. Editor kode seperti Visual Studio Code.

### Langkah Menjalankan
1. Klon repositori ini ke komputer lokal Anda.
2. Buka direktori proyek melalui editor kode.
3. Jalankan berkas HTML utama melalui ekstensi Live Server agar halaman dilayani melalui protokol HTTP.
4. Amati hasil render pada peramban dan gunakan Developer Tools untuk menelusuri struktur maupun keluaran konsol.

Menjalankan berkas langsung dari sistem berkas dengan skema `file://` tidak dianjurkan karena sebagian fitur peramban, termasuk pengambilan data melalui jaringan, hanya bekerja pada protokol HTTP.

## Tugas Mandiri

### Portal Artikel Ilmiah Berstandar W3C

**Skenario**

- Membuat berkas struktur halaman utama portal publikasi artikel ilmiah mahasiswa.
- Halaman harus kaya konten namun tetap terbaca oleh mesin pencari dan pengguna dengan keterbatasan visual.

**Spesifikasi Persyaratan**

1. Halaman harus valid menurut W3C HTML5 validator.
2. Gunakan minimal satu header, satu nav, satu main, serta tiga section yang masing-masing memuat minimal dua article.
3. Sertakan satu aside berisi daftar jurnal eksternal dan satu footer berisi lisensi Creative Commons serta kontak.
4. Gunakan kode entitas HTML secara tepat untuk karakter khusus.
5. Buat tautan ke portal eksternal dengan atribut keamanan rel yang tepat.

**Berkas yang Dikumpulkan**

- `01-tugas-arsitektur-dan-semantik.html`

Penamaan berkas wajib mengikuti ketentuan di atas. Berkas dengan penamaan yang tidak sesuai tidak akan diperiksa.

## Ketentuan Pengumpulan

1. Kerjakan tugas pada salinan lokal repositori ini.
2. Pastikan kode berjalan tanpa galat sebelum dikirim.
3. Simpan perubahan dengan pesan commit yang deskriptif.
4. Kirim hasil pekerjaan ke repositori daring sebelum tenggat yang ditetapkan.

```bash
git add .
git commit -m "Selesaikan tugas mandiri modul 1"
git push origin main
```

Riwayat commit menjadi bagian dari penilaian. Kerjakan secara bertahap dan hindari mengunggah seluruh pekerjaan dalam satu commit di akhir.

## Kriteria Penilaian

| Aspek | Bobot |
| --- | --- |
| Ketepatan pemenuhan spesifikasi | 40% |
| Kebenaran dan kerapian penulisan kode | 25% |
| Penerapan standar dan praktik terbaik | 20% |
| Kelengkapan dokumentasi dan riwayat commit | 15% |

## Integritas Akademik

Seluruh pekerjaan harus merupakan hasil karya sendiri. Pemanfaatan referensi dari sumber lain diperkenankan sepanjang dicantumkan sumbernya dan dipahami secara utuh. Penyalinan pekerjaan tanpa atribusi dikenai sanksi sesuai peraturan akademik yang berlaku.

## Lisensi

Materi pada repositori ini digunakan untuk keperluan pembelajaran di lingkungan Departemen Teknik Informatika, Fakultas Teknik, Universitas Hasanuddin.
