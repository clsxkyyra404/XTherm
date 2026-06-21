# XTherm Pro - Advanced Disable Thermal for Root
[![Magisk](https://img.shields.io/badge/Magisk-Compatible-00B248?style=flat-square&logo=magisk)](#) [![KernelSU](https://img.shields.io/badge/KernelSU-Supported-109038?style=flat-square)](#)

[🇺🇸 English](#-english) | [🇮🇩 Indonesia](#-indonesia)

---

## 🇺🇸 English

**XTherm Pro** is an advanced thermal controller module for Android users with Root access (Magisk / KernelSU). This module is specifically designed to bypass vendor thermal throttling limits, allowing your device to unleash its maximum performance without being held back by temperature-based CPU/GPU throttling.

If you are looking for a way to stop your phone from lagging or dropping FPS during heavy gaming sessions, XTherm Pro is the ultimate solution. 

### 🌟 Key Features

*   **Universal Thermal Disable:** Supports disabling various built-in thermal services for both Snapdragon and MediaTek chipsets (e.g., `thermal-engine`, `thermalservice`, etc.).
*   **The Ultimate Xiaomi Bypass:** Features a specialized trick to **permanently disable mi_thermald**. The module uses a Magisk Overlay Dummy Script to overwrite the MIUI/HyperOS binary, completely preventing the Xiaomi Watchdog from auto-restarting the service.
*   **Disable Thermal-HAL:** Includes an interactive installation option to permanently lock down the `thermal_hal` security layer right from boot.
*   **Interactive Installer:** A smart installation process using Volume Keys to select the right configurations for your specific device brand.

### 🚀 How to Install

XTherm Pro is a **Magisk thermal module**, meaning you need Root access to use it.

1.  Download the latest XTherm ZIP file from the [Releases](../../releases) page.
2.  Open your preferred Root manager (**Magisk** or **KernelSU**).
3.  Go to the **Modules** tab and select **Install from Storage**.
4.  Choose the downloaded XTherm ZIP file.
5.  Pay attention to the installation screen:
    *   You will be asked if you want to disable `Thermal HAL`. Press **Volume Up (Yes)** or **Volume Down (Skip)**.
    *   **Exclusive for Xiaomi/Redmi/POCO users:** You will get an additional prompt to disable `mi_thermald`. It is highly recommended to select **Volume Up (Yes)** to permanently kill the MIUI thermal protections from the root.
6.  Done! Tap **Reboot** to apply changes.

### ⚠️ Disclaimer

This module **disables** factory thermal protections. This will cause your device to run much hotter than usual during heavy gaming. 
Any risks such as hardware damage (overheating, burnt ICs, battery degradation) or bootloops are entirely **at your own risk (Do With Your Own Risk)**. Using an external Cooler Fan is highly recommended when using this module.

---

## 🇮🇩 Indonesia

**XTherm Pro** adalah modul tingkat lanjut (Advanced Disable Thermal) untuk pengguna Android dengan akses Root (Magisk / KernelSU). Modul ini dirancang khusus untuk melewati (*bypass*) batasan performa dari pabrik agar perangkat dapat berjalan pada performa maksimalnya tanpa gangguan *thermal throttling*.

Jika kamu sering mencari **cara mengatasi hp panas saat main game** yang malah membuat FPS drop secara drastis, XTherm Pro adalah solusinya. Modul ini akan mematikan perlindungan termal bawaan sistem sehingga CPU dan GPU tidak akan dibatasi ketika sedang bekerja keras.

### 🌟 Fitur Utama

*   **Universal Thermal Disable:** Mendukung pemblokiran berbagai jenis layanan thermal bawaan dari Snapdragon maupun MediaTek (seperti `thermal-engine`, `thermalservice`, dll).
*   **The Ultimate Xiaomi Bypass:** Modul ini memiliki trik khusus untuk **disable mi_thermald** secara permanen. Modul akan menimpa binary bawaan MIUI/HyperOS menggunakan trik *Magisk Overlay Dummy Script* untuk menghentikan sistem *Watchdog* Xiaomi dari me-restart layanan secara otomatis.
*   **Disable Thermal-HAL:** Dilengkapi opsi instalasi interaktif untuk menonaktifkan lapisan keamanan `thermal_hal` sejak perangkat pertama kali *booting*.
*   **Interactive Installer:** Proses instalasi yang cerdas menggunakan tombol volume (Volume Keys) untuk memilih konfigurasi yang sesuai dengan merek *device* kamu.

### 🚀 Cara Instalasi

XTherm Pro adalah **magisk thermal module**, sehingga kamu memerlukan akses *Root* untuk menggunakannya.

1.  Unduh file ZIP XTherm terbaru dari halaman [Releases](../../releases).
2.  Buka aplikasi pengelola Root pilihanmu (**Magisk** atau **KernelSU**).
3.  Masuk ke menu **Modules** dan pilih **Install from Storage**.
4.  Pilih file ZIP XTherm yang baru saja diunduh.
5.  Perhatikan layar instalasi:
    *   Kamu akan ditanya apakah ingin menonaktifkan `Thermal HAL`. Tekan **Volume Atas (Yes)** atau **Volume Bawah (Skip)**.
    *   **Khusus pengguna Xiaomi/Redmi/POCO:** Kamu akan mendapat pertanyaan tambahan untuk menonaktifkan `mi_thermald`. Sangat disarankan untuk memilih **Volume Atas (Yes)** agar perlindungan termal MIUI mati total hingga ke akarnya.
6.  Selesai! Tekan **Reboot** untuk menerapkan perubahan.

### ⚠️ Peringatan

Modul ini **menonaktifkan** fitur keamanan suhu bawaan pabrik. Hal ini akan menyebabkan perangkat menjadi jauh lebih panas dari biasanya saat bermain game berat. 
Segala risiko seperti kerusakan komponen *hardware* (*overheat*, IC gosong, baterai rusak) atau *bootloop* sepenuhnya adalah **tanggung jawab pengguna (Do With Your Own Risk)**. Sangat disarankan menggunakan pendingin eksternal (*Cooler Fan*) saat menggunakan modul ini.

---
**Developed by:** [@clsxkyyra404](https://github.com/clsxkyyra404)
