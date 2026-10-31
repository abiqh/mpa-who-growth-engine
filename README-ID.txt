PAKET PROTOTIPE MESIN WHO MPA DAYCARE (USIA 0-5 TAHUN)

Isi:
- mpa-who-0-5-engine.js : data referensi dan fungsi kalkulasi awal.
- LICENSE-GPL-3.0.md : lisensi paket sumber anthro.
- WHO-ANTHRO-LICENSE-NOTICE.txt : pemberitahuan sumber dan kewajiban distribusi.

Status: PROTOTIPE UNTUK PENGUJIAN, BELUM UNTUK PENGGUNAAN PUBLIK.

Pemakaian uji di browser:
1. Muat file JavaScript ini di halaman HTML setelah file diunggah ke hosting HTTPS.
2. Sertakan: <script src="URL-FILE-JS"></script>
3. Panggil MPAWHO0to5.calculate({
   birth: '2024-01-01',
   measureDate: '2026-10-29',
   sex: 'M',
   weight: 12,
   height: 85,
   position: 'standing'
   });
4. Hasil berupa objek dengan ageDays, bmi, dan empat indikator Z-score.

Catatan penting:
- Sex: M = laki-laki; F = perempuan.
- position: lying = telentang; standing = berdiri.
- Mesin ini memakai referensi WHO Child Growth Standards 2006 dari paket R WHO anthro.
- Sebelum dipublikasikan, harus divalidasi silang dengan WHO Anthro, termasuk kasus batas, koreksi panjang/tinggi, dan klasifikasi.
- Karena sumber/algoritma anthro berlisensi GPL-3, distribusi turunan harus mematuhi GPL-3, termasuk menyediakan kode sumber terkait dan pemberitahuan lisensi.
- Jangan gunakan hasil sebagai diagnosis medis.
