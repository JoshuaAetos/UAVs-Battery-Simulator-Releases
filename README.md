# UAV Battery Simulator

A free Windows app that simulates how a LiPo/Li-ion battery pack performs on a
drone — built for both hobbyists and professionals.

Tell it your battery's specs (chemistry, cell count, capacity, internal
resistance), your aircraft's motors and mission profile, and it simulates the
discharge in detail: voltage sag under load, pack self-heating, and how state
of charge drops over time — giving you a realistic estimate of flight time
instead of a rough rule-of-thumb.

### What it does

- **Physics-based discharge model** — voltage, internal resistance and usable
  capacity all respond realistically to load, temperature and state of
  charge, instead of assuming a flat battery.
- **Thermal simulation** — tracks pack temperature rise under load and its
  effect on performance.
- **Motor power from real physics (optional)** — instead of guessing a
  wattage, derive it from your aircraft's weight, propeller size, speed and
  climb rate (with presets for common builds: tiny whoop through industrial
  multirotor).
- **Mission profiles** — model takeoff, climb, cruise, hover, with
  always-on electronics (flight controller, GPS, video, etc.) drawing power
  alongside the motors.
- **Clear results** — estimated flight time, energy used, peak current,
  pack temperature, and live charts, plus CSV export for your own analysis.
- **Save/load your setups**, so you can compare different packs or aircraft
  configurations.

### Download

Grab the latest version from the [Releases](../../releases) page — no
installation required, just unzip and run `UAVBatterySim.exe`.

This repo hosts downloads only; the source code is maintained privately.

### Feedback

This is actively developed, and feedback shapes what gets worked on next.
Found a bug, have a feature request, or a parameter that doesn't match your
real-world experience? The app has a built-in feedback form (Help → About),
or email aestosone@gmail.com directly.
