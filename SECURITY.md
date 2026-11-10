# Security Policy

## Reporting a vulnerability

Do not publish credentials, access tokens, private user data, or exploit details in public issues.

Report security concerns privately to the repository owner through GitHub's private vulnerability reporting feature, when available.

## Binary integrity

Every published executable must include a SHA-256 checksum. Users should verify the checksum before running the file.

## Release requirements

A release must not be published as stable unless:
- The Windows build completed successfully.
- The executable was tested on a supported Windows system.
- The download source uses HTTPS.
- The checksum matches the uploaded binary.
- The release notes identify the exact version and build.
