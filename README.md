# My Day Clock

A simple learn-the-time app for iPad. It runs in Safari and works best in portrait.

- Turn the **little red hand** with a finger. The long blue minute hand moves with it.
- Each time the hand passes an o'clock, the app chimes and says the time, for example *"Eleven o'clock in the morning"*. The clock counts the full 24 hours, so going round twice takes you from morning to night.
- Tap the time at the top to hear the exact time ("quarter past seven in the morning").
- **Now** jumps to the real time. 🔊 turns the sound on or off.
- Below the clock, a picture shows the day: asleep, getting dressed, brushing teeth, walking to school through the blue gate, playing, dinner, iPad time, bath, pyjamas, a bedtime story, and lights out. The sky changes from day to night.

## Putting it on the iPad

The app is one web page (`index.html`) plus an icon, so it needs to be served from any web address, for example GitHub Pages:

1. On GitHub, go to **Settings → Pages**, choose to deploy from this branch, folder `/ (root)`, and save.
2. Open the address GitHub gives you in **Safari** on the iPad.
3. Tap **Share → Add to Home Screen**. It then opens full screen like an app, and keeps working offline after the first visit.

The iPad's volume needs to be up to hear the voice. iOS only allows sound after the first touch, so the first turn of the hand switches the sound on.

## Changing things

- The words on the school sign and gate are at the top of the script in `index.html` (`SCHOOL_SIGN` and `GATE_BANNER`).
- The daily timetable is in the `boyState()` function.
