# nanoKONTROL2 Mixer

Control the volume of your Windows programs with the faders and knobs of your **Korg nanoKONTROL2**.
Spotify quieter, Discord louder, game muted: just move a fader, no alt-tabbing.

Simple, available in English and Dutch, and it runs invisibly in the background.

---

## ⬇️ Download

Go to **[Releases](../../releases/latest)** and download **`nanoKONTROL2-Mixer-Setup-x.x.x.exe`**.

## ✅ Requirements

- Windows 10 or 11 (64-bit)
- A Korg nanoKONTROL2 (connected via USB)

No drivers or other software needed.

---

## 🛠️ Installation

1. Double-click the downloaded file.
2. Do you see the blue **"Windows protected your PC"** message?
   Click **More info** → **Run anyway**.
   *(This happens because the program has no paid digital signature. It is safe.)*
3. The mixer installs right away and opens by itself.

A shortcut is added to your desktop and Start menu.

---

## 🎚️ Usage

1. Plug in your nanoKONTROL2. The light in the top right of the window turns **green**.
2. For each channel, pick a program from the list for the **Fader** and, if you like, for the **Knob**.
3. Done!

| On the nanoKONTROL2 | What it does |
|---|---|
| **Fader** | Volume of the chosen program |
| **Knob** | Volume of a second program (chosen at the top of each channel) |
| **M button** | Mute on/off |
| **S button** | Solo: mute all other programs (press again to undo) |
| **R button** | Mute the knob's program |
| **▶ (Play)** | Play / pause |
| **■ (Stop)** | Stop |
| **◀◀ and ▶▶** | Previous / next track |
| **Track ◀ and ▶** | Previous / next track |

These are the defaults. Use **Button settings** in the top right to choose what each S, R and transport button does, for example:

- Mute the master volume, or master volume +5% / −5%
- **Fader → program in front**: click into a program (e.g. a game), press the button, and that fader controls that program from then on.
- Switch the output device (see below)

The transport buttons act like the media keys on a keyboard, so they work with Spotify, YouTube, VLC and most other players.

You can also choose **Master volume (everything)** or **System sounds**.
Your choices are remembered.

### Send audio to a different output (headset, aux cable, speakers)

Click **Outputs** in the top right and choose, per program, where its sound goes. For example: Spotify through the aux cable and your game through your headset.
Windows remembers this, even after you restart the program. A channel with its own output shows it in orange below the program list.

Want to do it from the nanoKONTROL2? In **Button settings**, set an S or R button to **switch output**. Each press moves that program to the next output.

- An aux output only shows up once a cable is plugged in.
- Some programs only switch after you restart them.

### In the background

- Clicking the **X** hides the window, but the mixer keeps working.
- You'll find it as a **blue circle with faders** in the bottom right next to the clock (possibly behind the **^** arrow).
- **Click** the icon to open the window.
- **Right-click** → **Quit** to really stop the mixer.
- Tick **"Start with Windows"** at the bottom and you never have to think about it again.

### Language

The mixer is available in **English** and **Dutch (Nederlands)**. It starts in the language of your Windows; switch it any time with **Language** in the bottom right.

---

## ❓ Troubleshooting

**My program isn't in the list.**
A program only appears once it plays (or has played) sound. Play a song in Spotify first, for example, and check again.

**The light stays red ("not found").**
- Unplug the USB cable and plug it back in.
- Close other programs that use the nanoKONTROL2 (for example a DAW, OBS plugins or the Korg Kontrol Editor). Windows only lets one program talk to the nanoKONTROL2 at a time.

**The faders do nothing.**
The mixer works with the nanoKONTROL2's default setting (CC mode) and with DAW/Mackie mode.
Did you ever change the controls in the Korg Kontrol Editor? Then reset it to the factory settings.

**The button lights don't turn on when I mute.**
That's the nanoKONTROL2's default setting. Want the lights to show what is muted (or soloed)?
Open the **Korg Kontrol Editor**, set **LED Mode** to **External** and write it to the nanoKONTROL2. You only need to do this once.

---

## 🗑️ Uninstall

Windows Settings → **Apps** → **nanoKONTROL2 Mixer** → **Uninstall**.

---

## 🔒 Privacy

The mixer works completely offline. Nothing is sent or tracked.

---

*This is an independent hobby project and has nothing to do with Korg. Korg and nanoKONTROL2 are trademarks of Korg Inc.*
