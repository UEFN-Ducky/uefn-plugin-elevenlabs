# ElevenLabs Voices

Give your duckies real ElevenLabs voices. Paste your ElevenLabs API key, then pick a voice per ducky (or as the default) — premade voices plus any custom/cloned voices from your account.

Desktop plugin for [UEFN-Ducky](https://github.com/UEFN-Ducky/UEFN-Ducky) (`elevenlabs`).
Install or update from **Settings → Store** in the app — do not install from a zip by hand.

## Build

```bash
py scripts/build_zip.py
```

Writes `deploy/elevenlabs-1.0.10.ducky-plugin.zip` (scripts/ and deploy/ are not packed).

## Secrets

Never commit tokens or keys. The app stores `elevenlabs_api_key` locally (DPAPI), not in this package.
