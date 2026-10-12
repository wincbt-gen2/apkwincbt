# WinCBT v4.0 Universal Release &mdash; Secure Exam Browser

Aplikasi Android Kiosk Client resmi untuk pelaksanaan Asesmen Berbasis Komputer SMK Pratiwi Prabumulih (**WinCBT**).

---

## 🚀 Tautan Unduh Langsung (Direct Download)

* **Berkas APK**: [`WinCBT_v4.0_Universal_Release.apk`](https://github.com/wincbt-gen2/apkwincbt/raw/refs/heads/main/WinCBT_v4.0_Universal_Release.apk)
* **Ukuran Berkas**: `5.443.083 bytes` (~5.44 MB)
* **Versi Rilis**: `v4.0 Universal Release`
* **Application ID**: `com.sekolah.wincbt`
* **Target Kompatibilitas**: Android 8.0 (Oreo / API 26) hingga Android 15+ (Vanilla Ice Cream / API 35)

---

## 🔐 Integritas & Verifikasi Berkas (Checksum)

Sebelum instalasi, integritas berkas biner dapat diverifikasi menggunakan algoritma SHA-256:

```text
SHA-256 Checksum:
420B59B21034B2BF76C49A4DACB46ECF0CDE8F120C3D76D3B2FFFFE6ED831687
```

Verifikasi di terminal/PowerShell:
```powershell
Get-FileHash -Path .\WinCBT_v4.0_Universal_Release.apk -Algorithm SHA256
```

---

## 🛡️ Fitur Keamanan Utama

1. **Hardware Kiosk Mode & Screen Pinning (Semat Layar)**:
   - Mengunci layar secara ketat selama sesi ujian berlangsung.
   - Memblokir tombol navigasi (*Back, Home, Recent Apps*), gesture swipe, dan status bar notification shade.
2. **Time-Lock Secure & Escalating Penalty Shield**:
   - Beroperasi dalam memori terisolasi.
   - Toleransi (*Gold Grace Period*) untuk gawai yang mengalami kendala teknis atau ketidaksengajaan.
   - Hukuman bertingkat otomatis jika terjadi pelepasan sematan layar saat ujian aktif.
3. **MultiGate Architecture**:
   - Mendukung integrasi mulus dengan Web CBT Siswa dan Google Workspace for Education.
   - Penanganan memori optimal untuk perangkat RAM terbatas (*zero-lag, anti-crash*).

---

## 📱 Petunjuk Instalasi untuk Siswa

1. Unduh berkas APK melalui tautan resmi di atas.
2. Buka berkas unduhan pada gawai Android Anda.
3. Jika muncul notifikasi perizinan, pilih **"Izinkan Penginstalan dari Sumber Ini"** (*Allow from this source*).
4. Selesaikan proses instalasi hingga tombol **Buka** (*Open*) aktif.
5. Jalankan aplikasi **WinCBT** dan ikuti arahan Proktor / Pengawas Ujian untuk memulai ujian.

---

&copy; Tim Pengembang WinCBT &mdash; SMK Pratiwi Prabumulih.
