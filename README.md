# Gallery — APK releases

Releases-only repository for **Gallery**, a personal Android gallery & file viewer:

- Browse photos, videos, audio and documents (PDF) on the phone, sort by name / date / size / type
- Full-screen image viewer with zoom, video player, audio player, PDF viewer
- Delete single or multiple files
- Offline semantic search powered by Google's on-device **EmbeddingGemma 300M** model (bundled; no cloud, no API keys)
- Material 3 with dark mode

The app source code is not published here. Each [release](../../releases) contains:

- `gallery-vX.Y.Z.apk` — the signed APK (arm64)
- `update.json` — the update manifest the app reads via
  `https://github.com/ShaneTeks/gallery-app-releases/releases/latest/download/update.json`

Install the first APK once; later versions arrive via **Settings → Check for updates** in the app.

The bundled EmbeddingGemma model is provided under the [Gemma Terms of Use](https://ai.google.dev/gemma/terms).
