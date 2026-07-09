# Azimuts Native Binaries

Versioned native binary artifacts used by Azimuts Desktop pilot builds.

## macOS Audio Tap

Release `azimuts-native-helpers-v1.1.0` includes `macos-audio-tap` archives for
both `darwin-arm64` and `darwin-x64`. The helper embeds its system-audio usage
description, carries a stable ad-hoc signing identifier before app packaging, and
emits `silent_capture` when macOS TCC returns only digital silence. The desktop
pipeline validates these markers and the target architecture before packaging.

## Meeting AEC Helper

Release `azimuts-meeting-aec-helper-v1.0.0` contains:

- `meeting-aec-helper-win32-x64.zip`
- `meeting-aec-helper-darwin-arm64.tar.gz`
- `meeting-aec-helper-darwin-x64.tar.gz`
- `meeting-aec-helper-linux-x64.tar.gz`

These artifacts are rehosted for reproducible Azimuts Desktop builds. Provenance: OpenWhispr `meeting-aec-helper` release artifacts. Azimuts Desktop downloads them during dev/build, then packages the selected helper into the app resources.

Do not use this repository for product data, secrets, Supabase assets, or runtime user-generated files.
