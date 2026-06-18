# Azimuts Native Binaries

Versioned native binary artifacts used by Azimuts Desktop pilot builds.

## Meeting AEC Helper

Release `azimuts-meeting-aec-helper-v1.0.0` contains:

- `meeting-aec-helper-win32-x64.zip`
- `meeting-aec-helper-darwin-arm64.tar.gz`
- `meeting-aec-helper-darwin-x64.tar.gz`
- `meeting-aec-helper-linux-x64.tar.gz`

These artifacts are rehosted for reproducible Azimuts Desktop builds. Provenance: OpenWhispr `meeting-aec-helper` release artifacts. Azimuts Desktop downloads them during dev/build, then packages the selected helper into the app resources.

Do not use this repository for product data, secrets, Supabase assets, or runtime user-generated files.