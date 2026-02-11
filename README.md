# ExpoEASAndroidDemo

Expo Android app built via **EAS Build (cloud)** and uploaded to [AutoDevice](https://autodevice.io).

## Build Method

- **Platform**: Android (APK)
- **Build**: EAS Build (cloud) — builds run on Expo's servers
- **CI Runner**: `ubuntu-latest`
- **Profile**: `preview` (produces APK for internal distribution)

## Required Secrets

| Secret | Description |
|--------|-------------|
| `EXPO_TOKEN` | Expo access token for EAS Build authentication |
| `AUTODEVICE_API_KEY` | AutoDevice API key for uploading builds |

## Local Development

```bash
npm install
npx expo start
```
