## Custom Recovery Builder
Compile your first custom recovery via Github Actions - with ldcheck setup.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > Pick which Build you need (`TWRP or PBRP`) > `Run workflow`, then pick required information from each drop-down list:
 * Manifest Branch (android-12.1)
 * Device Tree (Your device tree repository link)
 * Device Tree Branch (Your device tree repository branch)
 * Device Name (Your device codename)
 * Device Path (device/brand/codename)
 * Build Target (Recovery)
 * LDCHECK (path to your target binary file, ie. `system/bin/qseecomd`)
   - If you are building manually/locally and you want to use ldcheck for checking dependencies, visit [THIS](https://github.com/TeamWin/android_device_qcom_twrp-common/tree/android-11#using-ldcheck-to-find-dependencies) this for guide.
  
## Notes
   - Cloned and modified for use with PBRP and TWRP on device NX769J (Red Magic 9)

## Credits
- https://github.com/that1
- https://github.com/TeamWin
- https://github.com/PitchBlackRecoveryProject
- https://github.com/azwhikaru
- And to all Contributors in every repositories and scripts I used.
