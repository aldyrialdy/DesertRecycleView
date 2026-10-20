# 🍩 Droid Desserts

> Aplikasi mobile sederhana berbasis Android yang menampilkan daftar hidangan penutup (dessert) populer beserta deskripsi singkatnya. Dari hasil praktikum

## 📸 Tampilan Aplikasi (Preview)

| Halaman Utama |
| :---: |
| ![Droid Desserts UI](https://raw.githubusercontent.com/aldyrialdy/DesertRecycleView/d46ce676294e25fec4fb1c16fe8abbc17d697496/Screenshot_20261020_171039.png) |

## ✨ Fitur Utama

* 🍩 **Daftar Dessert:** Menampilkan berbagai macam menu pencuci mulut seperti Donut, Ice Cream Sandwich, dan Froyo.
* 🎨 **Clean & Pastel UI:** Tampilan antarmuka yang bersih, minimalis, dengan aksen warna pastel yang nyaman dilihat.
* 📱 **Layout Responsif:** Menggunakan komponen list view/recycler view untuk pengalaman navigasi yang mulus.

## 🛠️ Teknologi yang Digunakan

| Kategori | Teknologi |
| --- | --- |
| **Platform** | Android |
| **Bahasa Pemrograman** | Kotlin / Java |
| **UI Framework** | Jetpack Compose / XML Layouts |
| **Architecture** | MVVM (Model-View-ViewModel) |

## 🚀 Panduan Memulai (Getting Started)

### Prasyarat

* [Android Studio](https://developer.android.com/studio) versi terbaru (Hedgehog / Jellyfish / Ladybug atau yang lebih baru).
* JDK 17 atau yang direkomendasikan oleh Android Studio.
* Emulator Android atau Perangkat Fisik (dengan mode USB Debugging aktif).

### Instalasi & Pengaturan

1. **Clone repositori ini:**
   ```bash
   git clone https://github.com/username/droid-desserts.git
   cd droid-desserts
   ```

2. **Buka Proyek:**
    * Buka **Android Studio**.
    * Pilih **Open** dan arahkan ke folder proyek yang baru saja di-clone.

3. **Sync Gradle:**
    * Tunggu hingga Android Studio selesai mengunduh dependensi dan melakukan *Gradle Sync*.

4. **Jalankan Aplikasi:**
    * Pilih emulator atau perangkat Android Anda.
    * Klik tombol **Run (Shift + F10)**.

## 📁 Struktur Proyek

```text
app/src/main/
├── java/com/example/droiddesserts/
│   ├── data/          # Model data pencuci mulut (Donut, Ice Cream, Froyo)
│   ├── ui/            # Komponen tampilan / Activity / Composable
│   └── theme/         # Warna, Tipografi, dan Tema Pastel
└── res/
    ├── drawable/      # Aset gambar dessert
    └── values/        # String & warna dasar
```

## 📝 Lisensi

Proyek ini dibuat untuk tujuan pembelajaran dan dilindungi di bawah lisensi [MIT](LICENSE).