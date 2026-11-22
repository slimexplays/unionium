
# UNIONIUM BUILD ENVIRONMENT

## Build Type
Full Chromium source build for Android.

## Official Build Requirements
- Operating system: 64-bit Linux
- CPU architecture: x86-64
- RAM: Minimum 8 GB
- Recommended RAM: More than 16 GB
- Free disk space: Minimum 100 GB
- Required tools: Git, Python, depot_tools

## Android Configuration
- Target OS: android
- Target CPU: arm64
- Planned build target: chrome_public_apk

## Build Infrastructure
- Source repository: GitHub
- Chromium upstream: chromium.googlesource.com
- Development control: Android phone
- Build execution: Compatible cloud Linux machine
- Output: Android APK

## Build Limitations
- Full Chromium compilation is not practical on a typical Android phone.
- Standard cloud runners may not provide enough disk space or build time.
- Build infrastructure must be validated before compilation.
- No APK build is considered successful until it has been generated and tested.

## Build Security
- Never commit signing keys.
- Never commit passwords or API secrets.
- Use protected repository secrets for sensitive values.
- Keep build logs free of credentials.

## Current Status
- Repository foundation: Complete
- Branding documentation: Complete
- Chromium integration plan: Complete
- Build environment: Documented
- Cloud build provider: Not selected
- Successful Chromium APK: Not built yet
- 
