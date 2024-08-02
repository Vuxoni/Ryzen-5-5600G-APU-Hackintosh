# Ryzen 5 5600G APU EFI
EFI made for Ryzen 5 5600G CPU and Vega 7 iGPU on Asus Prime B450M-A II motherboard
# 🖥️ - Hardware
| Type  | Model |
| ------------- | ------------- |
| **CPU**  | Ryzen 5 5600G  |
| **GPU**  | Vega 7 (iGPU)  |
| **Motherboard**  | Asus Prime B450M-A II  |
| **RAM**  | Kingston Fury 2x8GB at 3200Mhz  |
| **Storage #1**  | SP 512GB SATA 3  |
| **Storage #2**  | Lexar NM620 512GB NVMe  |
| **Audio Codec**  | ALC892 (alcid=11)  |
| **Ethernet**  | RTL8111  |
| **OC Version**  | OC 1.0.0  |
| **OS**  | macOS Sonoma/Sequoia - Windows 11  |

> DISCLAIMER: I made this EFI for me and my hardware and I can't guarantee that it will work work for you. You can make your own EFI by following [Dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html). <br>
> All kinds of errors, problems, nuclear wars, explosions etc. are beyond my responsibility. <br>
> I don't recommend using pre-built EFIs, using one makes the whole process harder... You should use my EFI just for reference.

# 📖 - Tutorials
- **DIY:** https://dortania.github.io/OpenCore-Install-Guide/
- **USB Installer:** https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
- **SMBIOS**: https://github.com/corpnewt/GenSMBIOS
> SMBIOS infos are empty, use [genSMBIOS](https://github.com/corpnewt/GenSMBIOS) to generate your SMBIOS.

# 🖼️ - Results
![image](https://github.com/user-attachments/assets/ecfa9e42-4a6c-401d-8d29-324e78f7ed33)

# ❗- Works in Sequoia too (*kinda*)
![image](https://github.com/user-attachments/assets/33013886-c744-48ea-bf02-6b24ebea52ea)
- Why kinda ? Cause AppleALC is broken for AMD CPUs on Sequoia currently. Use USB headphones instead.
> CPU name is wrong, I'm lazzy to patch it.
