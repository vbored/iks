+++
date = '2025-06-18T09:30:39+03:00'
draft = true
title = 'Hackintosh EFI Resources Opencore and Clover'
+++
**Supported Platforms:** EFI folders are available for a wide range of platforms, including:  Intel Platforms: Sandy Bridge, Ivy Bridge, Haswell, Broadwell, Skylake, Kaby Lake, Coffee Lake, Whiskey Lake, Comet Lake, Coffee Lake Plus, Rocket Lake, Ice Lake, Alder Lake, Raptor Lake, Sandy Bridge-E, Ivy Bridge-E, Haswell-E, Broadwell-E, Skylake-XW, Cascade Lake-XW. AMD Platforms: Bulldozer, Jaguar, Ryzen, Threadripper. Other Platforms: Tiger Lake.

**Key Links and Resources:**
OpenCore MOD EFI folders: Access here  
If you share these folders, remember to give proper credits.

**General Instructions:**

No Additional SSDTs Needed: Avoid adding SSDTs like SSDT-EC or SSDT-USBX.
SMBIOS Configuration: Generate a complete SMBIOS with a valid serial number for your machine.
Essentials Provided: EFI folders include kexts, configurations, and patches for Intel and AMD systems with both Clover and OpenCore bootloaders.Installation Tips:
Use a USB 2.0 port for easier installation without USB remapping.
If using only an integrated GPU, add the -igfxvesa boot argument for simplified installation.
Replace the old EFI folder completely. Do not merge files.
Avoid drag-and-drop; always use Copy/Paste when transferring files to the EFI partition.
Reset NVRAM after replacing EFI:
OpenCore: Use the “Reset Nvram” option in the boot menu.
Clover: Press the F11 key on the boot screen.BIOS/UEFI Configuration:
SATA Mode: Set to AHCI.
Secure Boot: Disable if necessary.
CSM: Disable, especially with AMD graphics cards.

**How to Copy the EFI Folder to the EFI Partition:**
Mount the EFI partition.
Delete the existing EFI folder.
Copy the new EFI folder to the partition.
Reset NVRAM as described above.
By following these steps and resources, you’ll set up your Hackintosh efficiently and effectively.

**Instructions and Recommendations**

SSDT vs. DSDT: If using SSDT instead of DSDT, ensure that the RebaseRegions option in the ACPI tab is unchecked.
Post-Installation Cleanup: After installation, remove unnecessary files such as unused LAN kexts.
GPU Boot Arguments: If your GPU does not require agdpmod=pikera, remove this boot argument.
LAN Boot Arguments: For LAN cards that do not need dk.e1000=0 or e1000=0, remove these boot arguments.
Generate Serial Numbers: Ensure you generate a valid serial number for your setup.
IGPU Users: Refer to THIS GUIDE for video patching information.  
**OpenCore Folders** Desktop Configurations
+ LGA 77x: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Sandy Bridge: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Ivy Bridge: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Haswell and Broadwell: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Skylake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Kaby Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Coffee Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Comet Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Rocket Lake: Download [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Alder Lake and Raptor Lake:[Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Intel Core Ultra: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ HEDT Sandy Bridge-E and Ivy Bridge-E (x79 Chipset): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ HEDT Haswell-E and Broadwell-E (x99 Chipset): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ HEDT Skylake-XW and Cascade Lake-XW (x299 Chipset): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ AMD Bulldozer, Jaguar, Ryzen, and Threadripper: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)

⚠️ AMD users: Review the new requirements in the screenshot below
![AMD](https://i.imgur.com/0IONHgO.png)

**Notebook Configuration**

+ Sandy Bridge: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Ivy Bridge: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Haswell: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Broadwell: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Skylake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ For macOS Ventura: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Kaby Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Coffee Lake and Whiskey Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Coffee Lake Plus and Comet Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Ice Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ 12th, 13th, and 14th Gen: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip) (Hyper-Threading must be disabled)
+ Tiger Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)

**Clover FoldersDesktop Configurations**

+ LGA 775 (ICH7, ICH8, ICH9, ICH10): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ LGA 1366 (x58): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 5–9: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 10, 20 (Skylake/Kaby Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 30, 40 (Coffee Lake/Comet Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 50 (Rocket Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 60 (Alder Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 70 (Raptor Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series x79: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series x99: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series x299: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 5–9: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 10, 20 (Skylake/Kaby Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Chipset Series 30 (Coffee Lake/Whiskey Lake/Comet Lake): [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
+ Ice Lake: [Download HERE](https://olarila.com/files/OPENCORE1/EFI.OpenCore.Desktop.Bulldozer.Jaguar.Ryzen.Threadripper.zip)
**Credits**
Special thanks to the Olarila.com, Clover Team, OpenCore Team, AMD Team, Mieze, and many others for their contributions!