# SPD Unload & Announcement System — GitHub Pages prototype

## UI layout
1. Cart Washer: Cart Std, Container, Escalate
2. Assistance for Washer 1 / 2 / 3
3. Assistance for Drying Cabinet / Pass Window
4. Shift Lead Call

## Features
- Cart Std timer defaults to 13 minutes; Container defaults to 18 minutes.
- One-minute warning chime.
- Browser speech synthesis for assistance calls and completion announcements.
- Escalate is a toggle: tap once for an immediate, repeating buzzer (ON); tap again to stop the buzzer (OFF).
- Stop Sound control.
- Settings for timer durations and announcement wording; saved in the current browser only.
- No backend or database.

## Publish
1. Create a GitHub repository, e.g. `spd-unload-announcements`.
2. Upload `index.html` to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch, branch `main`, folder `/(root)`, then Save.
5. Wait for GitHub Pages to publish and use the URL shown there.

## Test with JBL Go 5
1. Pair the speaker with the Decon desktop and select it as the audio output.
2. Open the webpage, click Enable Audio, then Speaker Test.
3. Confirm both chime and speech are audible through the JBL.
4. For a quick test, change a cycle duration to 1–2 minutes in Settings.
5. Tap Escalate once to turn the repeating buzzer ON, then tap it again to turn it OFF. Also test Stop Sound.

## Important limitations
- Uses browser text-to-speech, not pre-recorded AI voice recordings. Available voice and pronunciation depend on the browser/device.
- The page cannot guarantee Bluetooth connection or prove that sound is audible.
- Browser timers/audio can be delayed if the desktop sleeps or the tab is suspended. Keep the desktop awake and page open during tests.
- This is a prototype, not a certified alarm or life-safety system. Do not rely on it as the sole notification method for safety-critical work.
