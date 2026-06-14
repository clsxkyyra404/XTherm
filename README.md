<div align="center">
  <h1>🔥 XTherm Module</h1>
  <p><strong>Advanced Granular Thermal Controller for Android (Root)</strong></p>
  
  [![Magisk](https://img.shields.io/badge/Magisk-Supported-00BFA5?style=for-the-badge&logo=magisk)](https://github.com/topjohnwu/Magisk)
  [![KernelSU](https://img.shields.io/badge/KernelSU-Supported-FF5722?style=for-the-badge&logo=android)](https://kernelsu.org/)
  [![App Manager](https://img.shields.io/badge/App_Manager-Required-8A2BE2?style=for-the-badge&logo=android)](https://github.com/clsxkyyra404/XTherm_AppManager)
  [![License](https://img.shields.io/badge/License-Open_Source-blue?style=for-the-badge)](LICENSE)
</div>

<br>

XTherm is an advanced Magisk/KernelSU module that provides granular control over Android's thermal throttling mechanisms. By allowing you to selectively disable specific thermal limits based on your device's SoC (Snapdragon or MediaTek), XTherm unlocks maximum gaming performance without boundaries.

> ⚠️ IMPORTANT: This module operates entirely in the background via .sh scripts. To actually control and toggle these limits, you MUST install the companion app manager: [XTherm App Manager](https://github.com/clsxkyyra404/XTherm_AppManager).

---

## ✨ Key Features

This module supports a massive array of thermal parameters and dynamically adapts based on your device's architecture:

### 🌍 Universal Thermal
- MIUI/HyperOS Thermal Daemon (mi_thermald)
- Android Thermal Processes (thermal_process)
- Kernel Thermal Zones (thermal_zones)
- Battery Thermal Control (Extreme Level)

### 🐉 Snapdragon Exclusive
- QTI Hardware Perf & Thermal Service
- Thermal Engine & Adreno GPU Standard Thermal
- Advanced Adreno Tuning: Granular toggles for kgsl_pwrlevel, adreno_throttling, bcl_thermal, adreno_preemption, qcom_lpm_prediction, and ufshc_throttling.

### ⚙️ MediaTek Exclusive
- MTK Thermal & Thermalservice
- Thermal Load Algod & Thermal Manager
- Mali GPU Standard Thermal
- Advanced Mali Tuning: Granular toggles for ged_dcs (Dynamic Clock Scaling), gpu_dvfs, gpu_always_on, and deep kernel-level control over 10 different MTK PPM Policies.

---

## 📥 Installation

As a systemless module, root access is strictly required (Magisk or KernelSU). Furthermore, the module alone will not do anything unless controlled by the App Manager.

1. Download the latest XTherm_Module-vX.X.X.zip from the [Releases](../../releases) tab.
2. Open the Magisk Manager or KernelSU app.
3. Navigate to the Modules tab.
4. Select Install from storage and choose the downloaded .zip file.
5. Wait for the flashing process to complete.
6. Reboot your device.
7. Once booted, you MUST download and install the [XTherm App Manager](https://github.com/clsxkyyra404/XTherm_AppManager) APK to start managing your thermals.

---

## ☠️ DWYOR (Do With Your Own Risk)

<details open>
<summary><b>🚨 READ BEFORE USING</b></summary>

Thermal throttling is an essential safety mechanism designed by manufacturers to prevent hardware damage caused by overheating. By disabling the parameters within this module (especially within the *Advanced Tuning* and *Battery Thermal* sections), you are forcing your CPU and GPU to sustain peak performance continuously, completely bypassing thermal safety thresholds.

Potential consequences if temperatures are not monitored:
1. Permanent damage to the Motherboard, CPU, or Power IC.
2. Battery swelling or severe battery degradation.
3. Screen burn-in or shadowing due to excessive heat.
4. Random reboots, bootloops, or sudden hardware death.

The developer (clsxkyyra404) is NOT RESPONSIBLE for any hardware damage, data loss, or other negative outcomes that occur to your device as a result of using this module. 

Use wisely. It is highly recommended to use an external Phone Cooler if you plan to play competitive games for extended periods.
</details>

---

## 🤝 Contributing

Made with ❤️ by clsxkyyra404. 
If you have suggestions for new thermal parameters or have found a bug, feel free to open an *Issue* or submit a *Pull Request*.
> ⚠️ IMPORTANT: This module operates entirely in the background via .sh scripts. To actually control and toggle these limits, you MUST install the companion app manager: [XTherm App Manager](https://github.com/clsxkyyra404/XTherm_App).

---

## ✨ Key Features

This module supports a massive array of thermal parameters and dynamically adapts based on your device's architecture:

### 🌍 Universal Thermal
- MIUI/HyperOS Thermal Daemon (mi_thermald)
- Android Thermal Processes (thermal_process)
- Kernel Thermal Zones (thermal_zones)
- Battery Thermal Control (Extreme Level)

### 🐉 Snapdragon Exclusive
- QTI Hardware Perf & Thermal Service
- Thermal Engine & Adreno GPU Standard Thermal
- Advanced Adreno Tuning: Granular toggles for kgsl_pwrlevel, adreno_throttling, bcl_thermal, adreno_preemption, qcom_lpm_prediction, and ufshc_throttling.

### ⚙️ MediaTek Exclusive
- MTK Thermal & Thermalservice
- Thermal Load Algod & Thermal Manager
- Mali GPU Standard Thermal
- Advanced Mali Tuning: Granular toggles for ged_dcs (Dynamic Clock Scaling), gpu_dvfs, gpu_always_on, and deep kernel-level control over 10 different MTK PPM Policies.

---

## 📥 Installation

As a systemless module, root access is strictly required.

1. Download the latest XTherm_Module-vX.X.X.zip from the [Releases](../../releases) tab.
2. Open the Magisk Manager or KernelSU app.
3. Navigate to the Modules tab.
4. Select Install from storage and choose the downloaded .zip file.
5. Wait for the flashing process to complete.
6. Reboot your device.
7. Once booted, ensure you install the XTherm App Manager APK to start managing your thermals.

---

## ☠️ DWYOR (Do With Your Own Risk)

<details open>
<summary><b>🚨 READ BEFORE USING</b></summary>

Thermal throttling is an essential safety mechanism designed by manufacturers to prevent hardware damage caused by overheating. By disabling the parameters within this module (especially within the *Advanced Tuning* and *Battery Thermal* sections), you are forcing your CPU and GPU to sustain peak performance continuously, completely bypassing thermal safety thresholds.

Potential consequences if temperatures are not monitored:
1. Permanent damage to the Motherboard, CPU, or Power IC.
2. Battery swelling or severe battery degradation.
3. Screen burn-in or shadowing due to excessive heat.
4. Random reboots, bootloops, or sudden hardware death.

The developer (clsxkyyra404) is NOT RESPONSIBLE for any hardware damage, data loss, or other negative outcomes that occur to your device as a result of using this module. 

Use wisely. It is highly recommended to use an external Phone Cooler if you plan to play competitive games for extended periods.
</details>

---

## 🤝 Contributing

Made with ❤️ by clsxkyyra404. 
If you have suggestions for new thermal parameters or have found a bug, feel free to open an *Issue* or submit a *Pull Request*. 

<div align="center">
  <p>🔥 <b>Keep Your Frame Rates High, but Watch Your Temps!</b> 🔥</p>
</div>
