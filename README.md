# TaniSense

**AI drone network for precision rice farming**

![Status](https://img.shields.io/badge/Status-Prototype%20to%20MVP-2F855A?style=flat-square)
![Registration](https://img.shields.io/badge/Registration-Unregistered-E2E8F0?style=flat-square&logo=shield&logoColor=4A5568&labelColor=EDF2F7&color=CBD5E0)
![Focus](https://img.shields.io/badge/Focus-Precision%20Agriculture-0EA5E9?style=flat-square)

- **Founder:** Ayu Lestari
- **Location:** Yogyakarta
- **Founded:** 2023
- **Initial Stage:** Prototype menuju MVP

## Product Overview

TaniSense adalah platform pertanian presisi berbasis drone dan AI untuk membantu petani padi memantau kesehatan lahan, kelembapan, dan risiko hama secara lebih cepat dan akurat. Solusi ini menggabungkan pemetaan udara, analitik visual, dan data historis untuk menghasilkan insight yang dapat ditindaklanjuti sehingga keputusan pemupukan, penyemprotan, dan irigasi menjadi lebih tepat.

## Problem Statement

Petani dan koperasi masih menghadapi beberapa kendala utama dalam operasional sawah padi:

- Monitoring lahan masih dilakukan secara manual dan memakan waktu.
- Deteksi hama, penyakit, dan kekurangan nutrisi sering terlambat.
- Penggunaan pestisida dan pupuk cenderung berlebih karena kurangnya data lapangan.
- Data lahan tersebar dan tidak terdokumentasi secara konsisten.
- Koperasi dan gapoktan kesulitan memantau banyak petak sawah sekaligus.

## Core Solution

TaniSense dirancang untuk menjawab kendala tersebut melalui alur kerja berikut:

1. Drone memetakan area sawah secara berkala.
2. AI menganalisis citra untuk mendeteksi anomali tanaman.
3. Dashboard menampilkan kondisi lahan per petak secara visual.
4. Sistem memberikan rekomendasi tindakan awal untuk pengguna lapangan.
5. Data historis digunakan untuk membaca tren, risiko, dan potensi hasil panen.

## MVP Features

### 1. Pemetaan Drone
- Pengambilan foto dan video udara per petak sawah.
- Penandaan koordinat lokasi untuk setiap misi.
- Riwayat penerbangan dan dokumentasi inspeksi.

### 2. Analisis AI
- Deteksi area berisiko secara otomatis.
- Identifikasi indikasi kekurangan nutrisi.
- Deteksi awal tekanan hama atau penyakit tanaman.
- Skor kesehatan tanaman untuk membantu prioritas tindakan.

### 3. Dashboard Monitoring
- Peta sawah interaktif berbasis blok atau petak.
- Ringkasan status lahan per area.
- Grafik tren kelembapan dan kesehatan tanaman.
- Notifikasi untuk area yang membutuhkan perhatian cepat.

### 4. Manajemen Pengguna
- Admin platform.
- Operator drone.
- Koperasi atau gapoktan.
- Petani individu.

### 5. Laporan
- Laporan inspeksi berkala.
- Ringkasan area bermasalah.
- Rekomendasi tindakan lapangan yang dapat ditindaklanjuti.

## Target Users

- Petani padi skala kecil hingga menengah.
- Koperasi tani.
- Gapoktan.
- Dinas pertanian.
- Mitra agritech dan offtaker.

## Value Proposition

TaniSense memberikan nilai utama berupa:

- Deteksi masalah lahan lebih cepat.
- Efisiensi biaya input pertanian.
- Akurasi keputusan lapangan yang lebih tinggi.
- Visibilitas kondisi lahan lintas petak dan lintas musim.
- Fondasi data pertanian yang siap diskalakan.

## Tech Stack

- **Python** untuk backend AI dan data pipeline.
- **PyTorch** untuk model computer vision.
- **DJI SDK** untuk integrasi drone.
- **PostGIS** untuk penyimpanan data geospasial.
- **React** untuk dashboard web.
- **LoRaWAN** atau sensor IoT untuk data lapangan tambahan.

## Initial Architecture

1. Drone mengambil citra lapangan.
2. Data dikirim ke server atau cloud.
3. Pipeline preprocessing membersihkan dan menyusun data citra.
4. Model AI melakukan inferensi terhadap citra.
5. Hasil analisis disimpan di database geospasial.
6. Dashboard menampilkan insight, histori, dan rekomendasi tindakan.

## Technical Pitch Deck

TaniSense dapat dipresentasikan ke mitra, investor, atau pemangku kepentingan melalui deck teknis yang mencakup:

- System architecture dan data pipeline.
- Validation results dan pilot metrics.
- Cost structure dan scaling plan.
- AI model scope dan detection capability.
- Operational workflow dari flight sampai recommendation.

## Development Roadmap

### Fase 1 — Validasi Masalah
- Identifikasi kebutuhan petani dan koperasi.
- Menentukan indikator utama yang paling bernilai.
- Memilih lokasi pilot awal.

### Fase 2 — MVP Teknis
- Integrasi drone dan alur upload data.
- Dashboard dasar untuk monitoring lahan.
- Deteksi awal anomali tanaman.
- Pemetaan lahan per petak.

### Fase 3 — Pilot Lapangan
- Uji coba pada area sawah terbatas.
- Perbandingan hasil AI dengan observasi lapangan.
- Pengumpulan umpan balik dari pengguna.

### Fase 4 — Optimasi Produk
- Peningkatan akurasi model.
- Penambahan notifikasi dan laporan otomatis.
- Penyempurnaan alur operasional operator drone.

### Fase 5 — Go-to-Market
- Skema langganan per hektare atau per musim.
- Kerja sama dengan koperasi dan pemerintah daerah.
- Perluasan wilayah pilot.

## Initial Business Model

- Subscription per hektare.
- Paket monitoring musiman.
- Biaya layanan scanning drone.
- Paket enterprise untuk koperasi dan dinas.

## Early Success Metrics

- Akurasi deteksi anomali lahan.
- Waktu respon dari pemetaan ke insight.
- Penurunan penggunaan pestisida dan pupuk.
- Peningkatan hasil panen.
- Jumlah lahan aktif yang dimonitor.

## Short Product Narrative

TaniSense adalah platform pertanian presisi berbasis drone dan AI untuk membantu petani padi memantau kesehatan lahan, kelembapan, dan risiko hama secara lebih cepat dan akurat. Dengan pemetaan udara dan analitik visual, TaniSense memberikan insight yang dapat langsung ditindaklanjuti agar penggunaan input pertanian lebih efisien dan hasil panen meningkat.
