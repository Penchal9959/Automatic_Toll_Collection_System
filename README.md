# Automatic Toll Collection

> **Archived.** The reviewed and corrected version of this project lives in
> [embedded-iot-projects / toll-collection](https://github.com/Penchal9959/embedded-iot-projects/tree/main/toll-collection), alongside the others from the same series. Work happens there;
> nothing here changes.

## What this was

An RFID toll barrier. A tag on the windscreen is read as the vehicle
approaches, the toll is deducted from the balance stored on the tag, and a
servo lifts the barrier without the car stopping. An insufficient balance
leaves the barrier down and shows the shortfall on the LCD.

The balance lives on the card rather than in a database, which is what makes
it a self-contained demonstration rather than half of a system.

## Hardware

Arduino UNO, MFRC522 RFID reader, 16x2 LCD, SG90 servo, buzzer, LEDs.

## Why it was archived

Twelve one-off repositories of two files each is not a portfolio, it is a
list. They were consolidated into one maintained repository with the
documentation and the build check they never had. This one is kept so
existing links still resolve.

## Licence

[MIT](LICENSE)
