# VANTAGE PRO RC1 Installers

This branch is for direct download of installable RC1 artifacts only.

## Android

- File: `delivery/VANTAGE_PRO_RC1_ANDROID_TEST.apk`
- SHA256: `7a63765c4e56d388f86e38ed3c109329b4d92886a61136227325cf3574a4e584`
- Version: `3.6.1-RC1-TEST` build `907`
- Package: `com.vantagepro.app.rc1test`
- Signing: isolated RC1 test key, not production Play signing

## Android Cloudflare Backend Build

- File: `delivery/VANTAGE_PRO_RC1_ANDROID_CLOUDFLARE.apk`
- SHA256: `a7471f2ae95d379492b17d72911ecca778256f064dbbf00d46a8f1aa68fa212b`
- Version: `3.6.1-RC1-TEST` build `907`
- Package: `com.vantagepro.app.rc1test`
- Backend: `https://vantage-pro-005a.brentleegacpinetown.workers.dev`
- Signing: isolated RC1 test key, not production Play signing

## Android Corrective RC2 Render Backend Build

- File: `delivery/VANTAGE_PRO_CORRECTIVE_RC2_ANDROID_RENDER.apk`
- SHA256: `9f5782870521b8ec7f074f5eac56b356df2d68d76153282a93bd63309a3d6de2`
- Version: `3.6.1-RC1-TEST` build `907`
- Package: `com.vantagepro.app.rc1test`
- Backend: `https://vantage-pro-beta-api.onrender.com`
- Signing: isolated RC1 test key, not production Play signing

## Windows

The Windows installer is produced by a Windows GitHub Actions runner from the same RC1 source checkpoint because Flutter Windows cannot be compiled on the Linux Codex host.
When the runner succeeds, the file will be added here:

- `delivery/VANTAGE_PRO_MASTER_COMPLETION_RC1_WINDOWS_SETUP.exe`

