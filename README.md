# Android device tree for Retroid Pocket 5 devices running mainline kernel

## Before flashing the Android build

Erase dtbo partition:

- `fastboot erase dtbo --slot=a`
- `fastboot erase dtbo --slot=b`

## Additional repositories required to build

| Path                  | Source                                                                                          |
| --------------------- | ----------------------------------------------------------------------------------------------- |
| kernel/retroid/sm8250 | https://github.com/lineageos-on-retroid/android_kernel_retroid_sm8250 (branch: `lineage-23.1`)  |
| vendor/retroid/rp5    | https://github.com/lineageos-on-retroid/proprietary_vendor_retroid_rp5 (branch: `lineage-23.1`) |
