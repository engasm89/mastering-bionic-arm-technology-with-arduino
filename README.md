# Mastering Bionic Arm Technology With Arduino

## Course Snapshot

| Field | Details |
| --- | --- |
| Instructor | Ashraf S A AlMadhoun |
| Hardware Focus | Arduino |
| Course Link | https://www.udemy.com |
| Repository Updated | 2025-11-18 |

## Overview

Mastering Bionic Arm Technology With Arduino is a hands-on course focused on practical
Arduino development. This repository contains curated starter code, wiring notes, and a
repeatable workflow that mirrors the lessons from the video curriculum.

## Learning Objectives

- Understand the core goals of the **Mastering Bionic Arm Technology With Arduino** lessons.
- Map the theoretical material onto executable firmware samples.
- Practice reviewing telemetry / console logs with the provided samples.
- Customize the code to match your target hardware setup.

## Hardware & Components

Consult `CIRCUIT.md` for wiring notes. Typical builds require a development board,
sensors/actuators described in the Mastering Bionic Arm Technology With Arduino videos,
jumper wires, and a USB cable for programming plus logging.

## Setup Instructions

1. Install the latest Arduino IDE or your preferred toolchain.
2. Clone this repository or download it as a ZIP.
3. Review the `README.md`, `CIRCUIT.md`, and `data/` samples.
4. Upload the code to your dev board and monitor the serial console.

## Code Walkthrough

The `*.c` files are intentionally lightweight so you can focus on the core concept taught
in the course. Each file now includes metadata comments that summarize intent, I/O
expectations, and how telemetry maps to the lesson.

## Usage

```bash
# Build and inspect the sample on a desktop toolchain
gcc -Wall -Wextra -std=c11 *.c -o demo && ./demo

# Or upload via Arduino IDE to replicate the Mastering Bionic Arm Technology With Arduino lab
```

## Sample Data

Open `data/sample-telemetry.jsonl` to inspect representative console output. This is
useful when validating your hardware wiring or cloud logging pipeline.

## Additional Notes (Legacy Content)

# Mastering Bionic Arm Technology with Arduino

- Course: Mastering Bionic Arm Technology with Arduino
- Author: Ashraf S A AlMadhoun
- Link: https://www.udemy.com/course/bionic-arm-using-arduino/?couponCode=JULYMAXDICOUNT

## Overview

Control a multi-servo bionic arm with potentiometers. Each potentiometer maps to a servo angle, allowing intuitive movement of fingers and joints.

## Code Explained

- Reads analog values from five potentiometers.
- Maps 0–1023 readings to 0–180° servo angles.
- Writes PWM to five servo channels for smooth motion.

## How To Use

- Connect five potentiometers to `A0..A4` and power.
- Connect servos to PWM pins `3,5,6,9,10` and an external supply.
- Ensure common ground between Arduino and servo supply.

## Purchase With Discount

Unlock the complete build and guidance with a limited-time discount — enroll via the link above.
