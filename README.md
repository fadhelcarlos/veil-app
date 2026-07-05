# Veil — private, hand-drawn notes

Veil is a notebook that lives only on your phone: draw a note, slide it behind a cover, open it
with your fingerprint. No account, no cloud, no copies. **[veilnotes.app](https://veilnotes.app)**

## Download for Android

**[⬇ veil.apk — latest version](https://github.com/fadhelcarlos/veil-app/releases/latest/download/veil.apk)**

Veil installs directly rather than through the Play Store, so Android shows its standard caution
for apps from the web:

1. **Download `veil.apk`.** If your browser warns about the file type, choose **Download anyway**.
2. **Open the finished download.** The first time, Android asks you to allow installs from your
   browser — tap **Settings → Allow from this source**.
3. **Install.** If Google Play Protect offers a second look, tap **More details → Install
   anyway**. That notice is expected for any app delivered outside the store.

Once installed, Veil keeps itself current: when a new version ships, the app offers it right on
your notes list — one tap downloads it, and your notes stay exactly where they are.

iOS is on the way (TestFlight today) — ask at [support@veilnotes.app](mailto:support@veilnotes.app).

## What's in this repository

Only the compiled, signed Android app — the source code is not public.

| Release asset | What it is |
| --- | --- |
| `veil.apk` | The app, signed with Veil's release key — every release uses the same key, so updates always install cleanly over the previous version. |
| `latest.json` | A small manifest the installed app reads to offer updates (version, download URL, checksum). |

---

[Privacy](https://veilnotes.app/privacy) · [Terms](https://veilnotes.app/terms) · [Support](https://veilnotes.app/support)
