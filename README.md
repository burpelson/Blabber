# Blabber Board

A text-to-speech soundboard with funny voices, real audio effects and saved pads.
Everything is in one file, `index.html`. It has no server, and it runs entirely in the browser.

## Three voice sources

| Source | What it is | Real effects? | Works offline? |
|---|---|---|---|
| Phone voice | Your phone or browser's built-in voices | No (pitch, speed and word tricks only) | Yes |
| AI voice | [Kokoro-82M](https://huggingface.co/onnx-community/Kokoro-82M-v1.0-ONNX), an open-source model (Apache 2.0) that runs on your device | Yes | After the first download |
| My recording | Any sound you record or pick | Yes | Yes |

Real effects: Robot, Alien, Wobbly, Megaphone, Telephone, Underwater, Broken radio, Cave, Echo, Crowd and Reverse, plus pitch and talking-speed sliders.

AI clips are saved on the device after the first time they're made, so pads play instantly afterward, even offline.

## Put it online for free with GitHub Pages (all from your phone)

AI voices need the app hosted on a real website. The Claude preview blocks the model download.

1. Make a free account at **github.com** in your phone's browser.
2. Tap **+** → **New repository**. Name it `blabber-board`, set it to **Public**, and tap **Create repository**.
3. Tap **uploading an existing file** (or **Add file → Upload files**), choose `index.html` (and this `README.md` if you like), then tap **Commit changes**.
4. Go to **Settings → Pages**. Under *Branch*, pick **main** and **/ (root)**, then tap **Save**.
5. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/blabber-board/`.
6. Open it on Wi-Fi, switch to **AI voice**, and tap **Load AI voices**. The first download is about 90 MB.
7. Optional: in your phone's browser menu, tap **Add to Home Screen** so it opens like an app.

## Moving your pads over

In the Claude version, open **Move your board to another app or device** → **Copy board code**.
In your hosted version, paste the code into the same box and tap **Add these pads**.
Recordings stay on the device where you made them, so you'll need to re-pick those.

## Good to know

- The first AI voice clip can take a few seconds on a phone. After that, it comes from the saved copy.
- Older or low-memory phones may struggle with the AI model. Phone voices and recordings still work.
- **Save last voice as WAV** (in Fine-tune) works on the hosted version, so you can share clips.

## Ideas for later

- Add Piper voices (MIT licensed, many languages) as a second AI engine.
- Record straight from the microphone inside the app.
- Drag to reorder pads, or sort them into folders and pages.
