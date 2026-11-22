
# UNIONIUM CHROMIUM REVISION

## Upstream
https://chromium.googlesource.com/chromium/src.git

## Revision Policy
- Do not build from an untracked revision.
- Record the exact Chromium Git commit SHA.
- Record the checkout date.
- Keep the revision unchanged during a release cycle.
- Test custom patches against the selected revision.

## Initial Revision
Status: NOT PINNED

Branch: main (tracking reference only)

Commit SHA: NOT SELECTED

## Selection Process
1. Inspect official Chromium upstream.
2. Select a suitable source revision.
3. Verify Android build compatibility.
4. Record its full Git commit SHA.
5. Test Unionium patches.
6. Approve the revision for development.

## Update Policy
Never automatically update the pinned revision
during a release build.
