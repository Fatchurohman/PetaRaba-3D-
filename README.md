# TactileMap 3D - Generator Peta Raba & Plakat Braille Tunanetra

Aplikasi web interaktif untuk merancang plakat peta raba taktil (*tactile map*) dan teks timbul Braille bagi penyandang disabilitas netra/tunanetra. Menghasilkan model 3D parametrik siap cetak langsung di browser ke format biner `.STL` untuk 3D printer tanpa perlu software CAD eksternal.

Aplikasi ini 100% *client-side*, tanpa backend server atau database, dan siap di-deploy secara instan ke **GitHub Pages**.

---

## 🌟 Fitur Utama

1. **Konverter Braille Otomatis**:
   * Mengetik teks biasa (alfabet A–Z dan angka 0–9) otomatis dikonversi ke matriks 6-titik Braille standar internasional.
   * Kubah titik (*dots*) dibentuk dengan elevasi timbul yang nyaman diraba ujung jari.
2. **Editor Denah Raba Interaktif (Grid 8x8)**:
   * Menggambar dinding koridor, sekat ruangan, dan titik lokasi (*"Anda di Sini"*) cukup dengan mengeklik kotak grid.
3. **Standar Aksesibilitas Visual Rendah (*Low Vision*)**:
   * Tampilan kontras tinggi (kuning cerah di atas pelat dasar gelap) untuk memudahkan pengguna dengan sisa penglihatan parsial.
4. **Ekspor Biner .STL Multi-Mesh**:
   * Menggabungkan pelat dasar, dinding denah, dan kubah Braille menjadi satu berkas padat siap potong di aplikasi slicer 3D (Cura, Bambu Studio, PrusaSlicer).
5. **Estimasi Produksi FDM**:
   * Menampilkan perhitungan bobot gram filamen dan estimasi tarif cetak jasa lokal (rata-rata Rp 15.000 – Rp 25.000 per plakat).

---

## 🖨️ Rekomendasi Cetak 3D Printer

| Parameter | Pengaturan Rekomendasi |
| :--- | :--- |
| **Material** | PLA+ / PETG |
| **Layer Height** | 0.16 mm – 0.20 mm (agar kubah titik Braille halus) |
| **Infill** | 20% Gyroid |
| **Pewarnaan Manual** | Cetak pelat warna hitam/biru gelap, lakukan jeda (*pause at height*) pada lapisan timbul untuk mengganti filamen ke warna kuning terang. |

---

## 👨‍💻 Pengembang

* **Developer**: fatur62
* **Lisensi**: MIT License
