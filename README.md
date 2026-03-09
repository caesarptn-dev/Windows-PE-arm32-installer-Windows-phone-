# Windows PE ARM32 Installer

**Bring your Lumia back to life with Windows PE** ⚗️

An experimental installer that allows you to install Windows PE ARM32 on your Lumia device, transforming it into a portable diagnostic and recovery tool.

## ⚠️ DISCLAIMER

**THIS IS EXPERIMENTAL SOFTWARE - USE AT YOUR OWN RISK**

- This installer WILL modify your device's partitions
- You may BRICK YOUR DEVICE if something goes wrong
- The developers are NOT RESPONSIBLE for any damage
- You MUST backup ALL your data before proceeding
- This will ERASE data on the selected partition

**Only proceed if you understand the risks and have proper backups!**

## 📋 Prerequisites

Before using this installer, you need:

1. ✅ **Administrator privileges** on your Windows PC
2. ✅ **Windows PE ARM32 ISO file** downloaded
3. ✅ **Complete backup** of all device partitions
4. ✅ **Lumia device** connected via USB
5. ✅ **USB debugging** or mass storage mode enabled
6. ✅ **Knowledge** of your device's partition layout

## 🚀 Installation Steps

### 1. Run as Administrator
- Right-click on `WindowsPE_ARM32_Installer.bat`
- Select **"Run as administrator"**
- The installer will verify admin privileges

### 2. Accept Disclaimer
- Read the full disclaimer carefully
- Type `YES` to accept the risks
- Type `NO` to cancel installation

### 3. Select ISO File
- Enter the full path to your Windows PE ARM32 ISO
- Example: `C:\Downloads\WinPE_ARM32.iso`
- The installer will verify the file exists

### 4. Confirm Backup
- Ensure you have backed up ALL partitions
- Type `YES` only if backups are complete
- Type `NO` to cancel and backup first

### 5. Choose Target Partition
- Review the list of available partitions
- Select the MainOS partition (usually labeled "MainOS")
- **WARNING**: Wrong selection = data loss!

### 6. Final Confirmation
- Review the installation summary
- Type `YES` to proceed with installation
- Type `NO` to cancel

### 7. Installation Process
The installer will:
- Mount the Windows PE ISO
- Format the target partition
- Copy Windows PE files
- Configure boot settings

### 8. Reboot
- **REBOOT YOUR PHONE** when installation completes
- Windows PE should boot automatically
- If it doesn't boot, restore from backup

## 🔧 Common MainOS Partitions

Look for these partition labels:
- `MainOS` - Main operating system partition
- `EFIESP` - EFI system partition
- `Data` - User data partition
- `PLAT` - Platform partition

**Always select the correct MainOS partition!**

## ❓ Troubleshooting

### Installer won't run
- Make sure you're running as Administrator
- Disable antivirus temporarily
- Check Windows version compatibility

### Can't find ISO file
- Use the full path: `C:\path\to\file.iso`
- Remove any quotes from the path
- Verify the file isn't corrupted

### Phone won't boot
- Try rebooting again
- Check BIOS/UEFI boot order
- Restore from your backup
- Seek help in community forums

### Installation fails
- Verify ISO file integrity
- Check available disk space
- Ensure proper partition selection
- Review error messages carefully

## 📱 Supported Devices

Compatible with ARM-based Lumia devices that support:
- Custom bootloader installation
- Windows PE ARM32 architecture
- Partition modification

## 🛡️ Safety Tips

1. **Backup Everything** - Cannot stress this enough!
2. **Test on spare device** - If you have one
3. **Keep recovery tools ready** - In case of issues
4. **Join community forums** - For support
5. **Don't rush** - Read each step carefully

## 🔄 What is Windows PE?

Windows PE (Preinstallation Environment) is:
- A lightweight diagnostic OS
- Used for recovery and maintenance
- Provides command-line tools
- Can run system utilities
- Useful for troubleshooting

## ⚗️ Experimental Status

This installer is **IN EXPERIMENT** status:
- Not fully tested on all devices
- May have compatibility issues
- Community-driven development
- Use with extreme caution

## 🙏 Credits

- **@caesarptn-dev** - Installer development
- Windows PE ARM32 community contributors
- Lumia modding community

## 📞 Support

For help and support:
- Check troubleshooting section above
- Visit community forums
- Report issues on GitHub
- Connect with other Lumia enthusiasts

## 📄 License

Use at your own risk. No warranty provided.

---

**Give your Lumia a second chance** 💙

*Transform. Experiment. Explore.*

**Remember: Always backup before experimenting!**

Will it work? Try it with yourself 😏
