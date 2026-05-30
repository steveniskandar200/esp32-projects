# 01 — LED Blink

My first ESP32 project — getting an LED to blink on a breadboard.

## What It Does
An LED connected to GPIO 2 blinks on and off every 500ms.

## Components
| Component | Quantity | Pin(s) Used |
|-----------|----------|-------------|
| LED | 1 | GPIO 2 |
| 220Ω Resistor | 1 | — |
| Breadboard | 1 | — |
| Jumper wires | 2 | — |

## Circuit
- LED **anode (+)** → 220Ω resistor → GPIO 2
- LED **cathode (-)** → GND

## Code Notes
- `pinMode(LED_PIN, OUTPUT)` sets GPIO 2 as an output
- `digitalWrite` toggles the pin HIGH (3.3v) and LOW (0v)
- `delay(500)` pauses for 500 milliseconds between toggles

## What I Learned
- How to wire an LED safely on a breadboard (always use a resistor!)
- How GPIO pins work on the ESP32
- The basic structure of an Arduino sketch: `setup()` and `loop()`

## Next Steps
- Try fading the LED using PWM instead of on/off
- Control the blink speed with a variable or potentiometer
