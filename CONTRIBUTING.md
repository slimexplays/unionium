# Contributing to Unionium

Thank you for contributing to Unionium.

## Project Rules

- Unionium is planned as a full Chromium source fork.
- Do not replace Chromium with an Android WebView wrapper.
- Keep custom changes organized inside the patches directory.
- Do not commit Chromium build outputs or generated binaries.
- Do not commit passwords, API keys, tokens or signing keys.

## Chromium Changes

- Record the upstream Chromium commit SHA.
- Make one logical change per patch.
- Use descriptive patch filenames.
- Document the purpose of every patch.
- Test changes before marking them complete.

## Documentation

- Keep documentation accurate and updated.
- Clearly distinguish planned features from implemented features.
- Never claim a build or test passed without running it.

## Pull Requests

- Explain what changed and why.
- List affected files.
- Include test results.
- Mention known limitations.

## Build Policy

Full Chromium builds must use a compatible Linux x86-64
environment with sufficient RAM and disk space.
GitHub repository checks do not prove that Chromium builds.
