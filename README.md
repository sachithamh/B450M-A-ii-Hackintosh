# B450M-A-ii-Hackintosh
Hackintosh Monterey on Ryzen 5 -3600 ASRock B450M-A-ii

OpenCore EFI

## System Information

| Name     |                     Model |
| :------- | ------------------------: |
| CPU      |             Ryzen 5 3600 |
| GPU      |               NVIDIA GeForce GT 1030 2 GB |
| HD      | 1TB PCI Disk |
| Board    |            PRIME B450M-A II |
| Ethernet |      Realtek® RTL8111H-CG |

- OpenCore: v0.8.3
- MacOS: v12.6 Monterey



## Guide
### 1.) * Press spacebar to open recovery 
### 2.) for run the opencore patcher apend  NVRAM > Add > 7C436110-AB2A-4BBB-A880-FE41995C9F82 > boot-args ``amfi_get_out_of_my_way=1`` and remove this after running patcher and restart otherwise VS-code , atom editors not work 
### 3.) after all if all works fine remove ``-v`` from  boot-args (NVRAM > Add > 7C436110-AB2A-4BBB-A880-FE41995C9F82 > boot-args) it will show the apple logo when os booting

<https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html>

<https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html>

PS: If you're using same specs as above just copy EFI folder to your EFI partition

### SMBIOS

Don't forget to change your device uuid.
Go to <https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo> For information on setting up SMBIOS platform info
  