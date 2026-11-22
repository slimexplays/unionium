
# UNIONIUM UPSTREAM MANAGEMENT

## Official Upstream
Name: Chromium
Repository: https://chromium.googlesource.com/chromium/src.git

## Project Strategy
Unionium maintains its own custom changes separately from Chromium upstream.

The complete Chromium source checkout must not be stored inside this repository.

## Source Management
- Chromium source is checked out separately.
- Unionium custom patches are maintained in this repository.
- Every patch must have a clear description.
- Upstream revisions must be recorded.
- Changes must be tested before integration.

## Planned Directory Structure

unionium/
├── .gitignore
├── README.md
├── docs/
│   ├── PROJECT_PLAN.md
│   ├── BRANDING.md
│   ├── CHROMIUM_INTEGRATION.md
│   ├── BUILD_ENVIRONMENT.md
│   └── UPSTREAM.md
├── patches/
│   ├── android/
│   ├── branding/
│   └── browser-ui/
├── scripts/
└── assets/
    ├── icons/
    ├── logos/
    └── backgrounds/

## Patch Rules
- Keep patches small and focused.
- Document the Chromium revision used.
- Do not commit generated build output.
- Do not commit credentials or signing keys.
- Validate patch compatibility before applying.

## Current Status
- Upstream repository identified.
- Custom patch structure planned.
- Chromium checkout not yet performed.
- No Chromium patch has been tested yet.
- 
