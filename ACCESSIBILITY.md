# Accessibility

The goal: play everything from the couch with just a controller, and still be fine with a keyboard
and mouse.

## What works

- **Controller first.** Every menu (the portal menu, the settings, the player menu, Core of Light)
  works with a controller alone, and shows that controller's buttons: Xbox, PlayStation (cross,
  circle, ...) or Nintendo. Buttons can be given other jobs (F4 > Controller), and the vibration
  strength set per player, down to off.
- **Keyboard and mouse** work everywhere too; the hints switch to the keys you press, and every key
  can be changed (F4 > Keyboard).
- **English and German** in every menu, following Windows or the game's language. The games
  themselves speak the languages that are on your disc.
- **Bigger menus:** the menus scale with the window; `ui_scale` in the settings file makes them
  larger still.
- **Less motion:** Core of Light's animations can be turned off (Settings > Animations); motion
  blur in the games is off by default.
- **Volume:** the game's volume and the launcher's music each have their own setting.

## Known limits

- The games' own menus and texts (not ours) keep their size and colours.
- No screen reader support yet.
- Colour is sometimes the only sign of an element; the element's name is shown next to it in most
  places.

## Tell us about a barrier

Open an issue in the project's repository and say what's in your way. That's how things get on the
list.
