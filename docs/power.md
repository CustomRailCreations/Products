# Powering your car

[← All guides](../README.md)

A Pixel Xpress car runs from **track power** or from a **USB power adapter**, never both at the
same time.

## Track power

| | |
|---|---|
| **Best range** | **10 to 22 V AC.** Everything works: display, sound and all lights. |
| **Lowest** | **8 V AC.** The display and normal sound and lights keep working down to here. |
| **Below 8 V AC** | The car's electronics switch off and the display restarts when the voltage comes back up. This does no harm. |
| **Highest** | **22 V AC.** Don't go above it. |
| **Command control** | Command-control layouts (a steady track voltage of about 18 V AC) are well inside the range. |
| **DC layouts** | 10 to 22 V DC, either polarity. |

Things to know:

- **Low throttle.** On a conventional layout the track voltage goes up and down with the throttle.
  If you run the train very slowly (under 8 V), the display may switch off and restart. Turn the
  throttle up a little and it comes back.
- **Dirty track.** Very short power gaps from dirty track or rollers are ridden through.
  - At normal throttle (about 14 V and up), gaps of a few hundredths of a second are covered.
  - At low throttle, longer gaps make the display restart. Clean track helps.
- **Derailments and shorts.** The car's power board has resettable fuses. After a short circuit,
  turn the track power off for a minute, fix the derailment, and turn it back on.
- **After a restart** the display takes a few seconds to show pictures again and to rejoin your
  Wi-Fi.

## USB power

- Use a **USB-C power adapter rated 5 V, 1.5 A or more** (3 A adapters are fine).
- The USB-C socket is inside the car, behind the display. The cable that comes with the car
  reaches out through the sliding door.
- A smaller adapter (for example 0.5 A) may restart the display when the sound is loud.

## Never use track power and USB at the same time

> **Important:** take the car off the track, or turn the track power off, **before** plugging in a
> USB cable. Unplug the USB cable before putting the car back on a powered track.

This also applies when you plug in a **computer**, for example to repair the display with the
[Pixel Xpress Flasher](repair-with-flasher.md). Connecting a computer while the car is on a
powered track can damage the car or the computer.
