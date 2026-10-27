# Try Ghost Hunt on your Mac

Ghost Hunt is Ghostlight's mixed-reality team game for Meta Quest 3: a team hunts ghosts that come out of the walls
and furniture of a real room. You don't need a headset to try it. The game runs in Chrome with a built-in Quest 3
emulator, and your Mac acts as the station that runs the game, exactly as it will at a venue.

About 10 minutes the first time.

## What you need

- A Mac with macOS 15 or later
- Google Chrome (the emulator needs Chrome; Safari is fine for the console)
- Internet, the first time, so the station can download the game

## 1. Install the station

1. Download **[Ghostlight-Station.dmg](https://github.com/SwissConnection/ghostlight-builds/releases/download/station/Ghostlight-Station.dmg)**.
2. Open it and drag **Ghostlight Station** to **Applications**.
3. Open Ghostlight Station from Applications. If macOS asks whether to open an app downloaded from the internet,
   click **Open**. If it asks to allow incoming network connections, click **Allow**.

The station has no window. It lives in the menu bar. It downloads the latest game by itself, and its menu shows
**Ghost Hunt** with a version number once it's ready. It also keeps itself and the game up to date.

## 2. Start a session

In the station's menu, choose **Open console**. The console opens in your browser. It's the page a guide at the venue
uses to run the game: it shows who's playing, starts and pauses the hunt, and holds the settings.

On the console, click **Add bot** once or twice. Bots are fake teammates, so you're not hunting alone.

## 3. Join as a player

1. In **Chrome**, open **https://localhost**.
2. Chrome warns that the connection isn't private, because the station uses its own certificate. Click **Advanced**,
   then **Proceed to localhost**.
3. Click **Enter XR**. You're now looking through an emulated Quest 3, standing in a test living room.

**Moving around in the emulator:**

- The panels in the bottom corners show which keys drive the left and right controller. The right controller's
  trigger is your beam.
- The play button (▷) in the toolbar at the top switches to mouse-and-keyboard control, like a first-person game.

## 4. Play

**Training, on your own:**

1. Pull the trigger on the welcome.
2. Pick your color by pointing at one of the glowing orbs and pulling the trigger.
3. Light up the three practice wisps by holding your beam on them.
4. Then wait. A sign tells you to listen to your guide.

Your left wrist shows your lives and points. Raise and turn the left controller to see it.

**The hunt.** Back on the console, click **Start**. Then:

- **Lights out:** the room goes dark, the title appears, and a countdown runs.
- **Three waves of ghosts.** Hold your beam on a ghost until it bursts. Different kinds move differently: some drift
  toward you, some dart around, some sneak up behind you. If a ghost reaches you, you lose a life. Lose all three and
  you're out until the break.
- **Breaks between waves:** everyone gets their lives back.
- **Wave 3 ends with the Landlord,** a boss too big for one beam. He only takes damage while enough of the team beams
  him at the same time, he sends out ghosts of his own, and he closes in on the strongest player. Burst him and the
  room is cleared.

**On the console** you can pause, play again, and change the settings: friendly fire
(beams that hit a teammate drain their life and cost you points), how dark the room gets, and how many ghosts come.

## 5. Stop

In the station's menu, choose **End session**. You can quit the station from the same menu.

## If something's off

- **The menu says "No game yet":** the station needs internet once to download the game. Wait a moment.
- **https://localhost doesn't load:** make sure you chose Open console first. The game only runs during a session.
- **The station says another program is using the game's port:** something else on your Mac uses port 443. Quit it,
  or restart the Mac.
- **The emulator looks frozen:** click into the page, or reload it.

This is an early build, played in an emulator. On a real headset the room around you is your actual room. Tell the
Ghostlight team what you think.
