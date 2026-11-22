
# UNIONIUM BUILD STRATEGY

## Project
Unionium Android Browser

## Build Architecture
- Development control: Android phone
- Source management: Private GitHub repository
- Chromium upstream: Official Chromium Git repository
- Build platform: Linux x86-64 cloud environment
- Target architecture: Android ARM64
- Output: Unionium APK

## Build Requirements
- Minimum RAM: 8 GB
- Recommended RAM: 16 GB or more
- Free disk: At least 100 GB
- Linux x86-64
- Git and Python
- Chromium depot_tools

## GitHub Actions Assessment
Standard private GitHub Actions runners:
- 2 CPU cores
- 8 GB RAM
- 14 GB SSD

Assessment:
Standard runner storage is insufficient for
a complete Chromium checkout and build.

Do not start a full Chromium compilation
on this runner.

## Build Strategy
1. Keep the main repository lightweight.
2. Select a stable Chromium revision.
3. Pin the exact upstream revision.
4. Maintain Unionium patches separately.
5. Validate cloud build capacity.
6. Perform a source checkout.
7. Configure Android ARM64 build.
8. Compile and validate the APK.

## Cost Policy
- Prefer free development tools.
- Do not assume unlimited free cloud compute.
- Do not enable paid services without approval.
- Do not expose credentials in build logs.

## Current Status
- GitHub repository: Complete
- Project documentation: Complete
- Chromium upstream plan: Complete
- Build infrastructure: Not selected
- Chromium revision: Not pinned
- APK: Not built
- 
