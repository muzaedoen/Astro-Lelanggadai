---
# =========================================================================
# FRONTMATTER (METADATA ARTIKEL)
# Bagian ini digunakan oleh Astro untuk mengatur SEO halaman, judul, 
# dan otomatis dipakai menjadi meta tag OG Image untuk share ke Facebook.
# =========================================================================
title: 'Info Lelang Rumah Perum Dinar Asri Semarang: Peluang Investasi & Analisis Risiko'
description: 'Simak detail lelang properti Bank Mandiri di Tembalang, Semarang dengan nilai limit Rp 201 Juta. Baca analisis lokasi dan tips aman ikut lelang KPKNL di sini.'
pubDate: '2026-06-06T01:22:34.123Z'
heroImage: '../../assets/lelang/rumah-dinar-asri.jpg' # Jalur gambar lokal untuk thumbnail sistem & Facebook
categories: ['Lelang Semarang']
---

# =========================================================================
# IMPORT KOMPONEN ASTRO
# Wajib di-import di atas agar fitur kompresi gambar otomatis berjalan.
# =========================================================================
import { Image } from 'astro:assets';
import fotoRumah from '../../assets/lelang/rumah-dinar-asri.jpg'; # Mengubah file gambar menjadi variabel JavaScript

{/* FOTO UTAMA ARTIKEL 
  - Menggunakan komponen <Image /> bawaan Astro.
  - format="webp" memastikan gambar otomatis dikompres menjadi sangat ringan untuk SEO.
*/}
<div style={{ textAlign: 'center', marginBottom: '20px' }}>
  <Image 
    src={fotoRumah} 
    alt="Kondisi Fisik Rumah Lelang Perum Dinar Asri Meteseh Tembalang Semarang" 
    format="webp"
    style={{ maxWidth: '100%', height: 'auto', borderRadius: '8px', boxShadow: '0 4px 8px rgba(0,0,0,0.1)' }} 
  />
</div>

### Informasi Lelang

{/* TABEL INFORMASI UTAMA 
  - class="tabel-lelang" akan otomatis mengambil gaya desain dari file layout blog Anda.
  - class="bg-info-muda" menghasilkan warna baris biru muda cerah.
  - class="bg-sukses-muda" menghasilkan warna baris hijau muda cerah.
*/}
<table class="tabel-lelang">
<thead style={{ backgroundColor: '#F0F4F8', color: '#1E1E1E' }}>
  <tr>
    <th>INFORMASI</th>
    <th>KETERANGAN</th>
  </tr>
</thead>
<tbody>
  <tr class="bg-info-muda">
    <td>Jenis Barang Lelang</td>
    <td>Tidak Bergerak<br /><b>Tanah Berikut Bangunan</b></td>
  </tr>
  <tr class="bg-sukses-muda">
    <td>Bukti Kepemilikan</td>
    <td>SHM No: 8027 (13 Des 2019)</td>
  </tr>
  <tr class="bg-info-muda">
    <td>Uang Jaminan</td>
    <td class="text-danger-bold">Rp 42.000.000</td> {/* Kelas warna merah tebal */}
  </tr>
  <tr class="bg-sukses-muda">
    <td>Nilai Limit</td>
    <td class="text-success-bold">Rp 201.000.000</td> {/* Kelas warna hijau tebal */}
  </tr>
  <tr class="bg-info-muda">
    <td>Batas Akhir Uang Jaminan</td>
    <td class="text-warning-muda-bold">23 Juni 2026</td> {/* Kelas warna jingga tebal */}
  </tr>
  <tr class="bg-sukses-muda">
    <td>Batas Akhir Penawaran</td>
    <td class="text-warning-tua-bold">24 Juni 2026</td> {/* Kelas warna cokelat-merah tebal */}
  </tr>
  <tr class="bg-info-muda">
    <td>Uraian</td>
    <td><b>Luas:</b> 103 M²<br /><b>Alamat:</b> Perum Dinar Asri N 8 11, Kelurahan Meteseh, Kecamatan Tembalang, Kota Semarang, Provinsi Jawa Tengah</td>
  </tr>
  <tr class="bg-sukses-muda">
    <td>Analisis Jaminan</td>
    <td>Uang jaminan sebesar <b>Rp 42.000.000</b> wajib dibayarkan untuk mengikuti lelang. Jaminan akan dikembalikan penuh apabila peserta tidak memenangkan lelang.</td>
  </tr>
  <tr class="bg-info-muda">
    <td>Catatan Penting</td>
    <td class="text-catatan">Disarankan untuk <b>berpikir matang dan teliti</b> sebelum memutuskan berinvestasi di tanah lelang. Lakukan survei lokasi, cek dokumen asli, dan pertimbangkan risiko investasi properti dengan seksama.</td>
  </tr>
  <tr class="bg-sukses-muda">
    <td>Keterangan Informasi</td>
    <td>Informasi ini hanya bertujuan untuk mempermudah proses pencairan dan sebagai bahan referensi. Segala keputusan akhir berada di tangan peserta lelang.</td>
  </tr>
  <tr class="bg-info-muda">
    <td>Info Penjual</td>
    <td class="text-redup"> {/* Kelas huruf sedikit mengecil & warna abu-abu gelap */}
      <b>PT Bank Mandiri (Persero), Tbk</b><br />
      Retail Asset Management VII / Jawa 2<br />
      Jl. Kepodang No 32-34 Lantai 2, Kota Semarang<br />
      📞 Telepon: 14000
    </td>
  </tr>
  <tr class="bg-sukses-muda">
    <td>Info Penyelenggara</td>
    <td class="text-redup">
      <b>KPKNL Semarang</b> (Rekening BNI)<br />
      Gedung Keuangan Negara Semarang II Lantai 4, Jl. Imam Bonjol No. 1D, Semarang - 50142<br />
      📞 Telepon: (024) 3542272
    </td>
  </tr>
  <tr class="bg-info-muda">
    <td>Sumber</td>
    {/* Link Dofollow eksternal yang dioptimalkan untuk keamanan pembukaan tab baru */}
    <td><a href="https://lelang.go.id" class="link-sumber" target="_blank">lelang.go.id ↗</a></td>
  </tr>
</tbody>
</table>

---

{/* KONTEN NARASI UTAMA (MENDUKUNG SEO & GOOGLE HELPFUL CONTENT)
  Bagian bawah ini wajib ditulis menggunakan format paragraf biasa agar 
  kata kunci terindeks alami dan layout responsif di layar ponsel (
