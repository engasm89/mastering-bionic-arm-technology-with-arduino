# Mastering Bionic Arm Technology with Arduino — Circuit Schematic

- Course: Mastering Bionic Arm Technology with Arduino
- Author: Ashraf S A AlMadhoun
- Link: https://www.udemy.com/course/bionic-arm-using-arduino/?couponCode=JULYMAXDICOUNT

## Connections

- Potentiometers: `A0..A4` (middle wiper to analog pin, side pins to `5V`/`GND`).
- Servos: Signals on `D3, D5, D6, D9, D10`, power from external 5–6V.
- Common Ground: Arduino `GND` tied to servo power `GND`.

## Diagram (ASCII)

```
   Pots            Arduino UNO                Servos (external 5–6V)
 A0,A1,A2,A3,A4 -> A0..A4                     SIG -> D3,D5,D6,D9,D10
 5V,GND          -> 5V,GND                     VCC -> +5..6V, GND -> GND

  [ All grounds must be common ]
```

## Notes

- Use adequate current supply for multiple servos.
- Consider mechanical limits to prevent overextension.

## Purchase With Discount

Get the full hands-on guide with a discounted price — use the course link above.

