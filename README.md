# Jarvis Personal Voice Companion

Android-friendly Progressive Web App starter; not a native APK and not the OpenJarvis Python repository. Includes your uploaded logo, microphone button, spoken replies, language choices, reply styles, permission toggle, and an MP3 sample player.

## Publish and install
1. Extract this ZIP.
2. Create a GitHub repository and upload the files in this folder to its root. Never upload an API key.
3. Repository Settings → Pages → Deploy from a branch → `main` → `/(root)` → Save.
4. Wait for the HTTPS GitHub Pages URL, open it in Chrome on Android, menu ⋮ → Install app / Add to Home screen.

## Optional AI
The Settings panel accepts a Gemini API key. The browser sends transcribed text to Google's API. The key is stored in localStorage and can be accessed by someone using/inspecting this browser profile. A public app should use a secure backend. Availability and usage costs depend on current provider terms; ask a parent/guardian before setting up paid services.

## Limits
- Does not provide continuous background listening or a wake word.
- Cannot control every app or do arbitrary phone actions. Integrations require APIs and permissions.
- The MP3 is included as a playable sample, not cloned into a synthetic voice. Voice cloning requires a compatible service and the voice owner's permission.
- Speech recognition and languages depend on browser/Android support.
