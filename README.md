# PemSpasial_GEE_V126241002-

# Judul Proyek : Sistem Analisis Geospasial [Surabaya]

## Informasi Mahasiswa
- **Nama**: [Nur Faatihah Ashar]
- **NIM** : [V126241002]
- **Mata Kuliah** : Praktek Pemograman Spasial (24V12632903)
- **Pengampu** : Tim Dosen (Agus Aris, Prof. Syamsu Arif, Ibu Dini, Zylsal)
- **Tahun** : 2026

## Deskripsi Proyek
Proyek ini membangun sistem analisis geospasial berbasis Google Earth Engine (GEE)
dan Google Colab untuk menganalisis [Urban Heat Island] di wilayah Kota Surabaya,
Jawa Timur, Indonesia.

## Area of Interest (AOI)
- **Lokasi**: [Kota Surabaya/Jawa Timur/Indonesia]
- **Koordinat**: [112.24252647646517,-7.805844136513645, 113.21481651552767, -6.90148870185857]
- **Luas**: [10782.62] km²
- **Alasan pemilihan**: [Surabaya dipilih karena memiliki kawasan terbangun yang padat serta variasi vegetasi dan perairan, sehingga menarik untuk menganalisis perbedaan suhu permukaan dan fenomena Urban Heat Island (UHI).]

## Platform dan Tools
- Google Earth Engine (GEE) — JavaScript API & Python API
- Google Colab — Python notebook environment
- Library: `earthengine-api`, `geemap`, `pandas`, `matplotlib`, `numpy`

## Struktur Folder
```
data_aoi/        ← File AOI (GeoJSON, Shapefile)
data_raw/        ← Citra GeoTIFF dari GEE
data_processed/  ← Citra preprocessed dan indeks
notebooks/       ← Jupyter notebooks per pertemuan
gee_scripts/     ← Script JavaScript GEE
outputs/         ← Peta, statistik, grafik
report/          ← Laporan teknis final
```

## Cara Menjalankan
1. Clone repository ini
2. Buka notebook di Google Colab
3. Jalankan Cell 1 untuk install library
4. Jalankan Cell 2 untuk autentikasi GEE
5. Jalankan cell-cell selanjutnya secara berurutan

## Progress Pertemuan
| Prt | Topik | Status |
|-----|-------|--------|
| 1   | Setup GEE & Colab, Definisi AOI | ✅ Selesai |
| 2   | Objek GEE | 🔄 Dalam Proses |
| ... | ... | ... 
