
# UNIONIUM CHROMIUM INTEGRATION

## Upstream
Repository:
https://chromium.googlesource.com/chromium/src.git

## Integration Strategy
- Maintain Chromium as upstream source.
- Pin a known-good Chromium revision.
- Keep Unionium changes in separate patches.
- Avoid committing the complete Chromium checkout
  into the Unionium repository.
- Document every custom patch.

## Android Target
target_os = "android"
target_cpu = "arm64"

## Planned Customizations
1. Application identity
2. Application name
3. Launcher icon
4. Browser theme
5. Home screen branding
6. Toolbar branding
7. Browser settings
8. Privacy configuration

## Build Target
chrome_public_apk

## Build Validation
- Verify source checkout.
- Verify Android toolchain.
- Verify GN configuration.
- Compile browser.
- Install APK on Android.
- Test navigation and tabs.
- Test application identity.

## Important
The build target and customization paths
must be validated against the pinned
Chromium revision.

No successful build is claimed yet.
