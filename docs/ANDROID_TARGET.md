
# UNIONIUM ANDROID TARGET

## Platform
Android

## Planned Architecture
ARM64

## Chromium GN Configuration

target_os = "android"
target_cpu = "arm64"

## Target Validation
Check the target device ABI before finalizing
the supported architecture.

Android ABI detection:
adb shell getprop ro.product.cpu.abi

## Build Target
chrome_public_apk

## Validation
- APK installation
- Browser startup
- Website navigation
- Multiple tabs
- Network connectivity
- Device compatibility

## Status
Architecture planned.
Build not yet validated.
