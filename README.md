## Project Description

This is a simple Arduino project that demonstrates how to blink an LED using a digital output pin. It is often used as a first step to learn basic microcontroller programming.

⚙️ Components Used

-Arduino Uno (or compatible board)

-LED

-330Ω resistor

-Breadboard

-2 Jumper wires

🔌 Circuit Setup

LED anode (+) connected to a digital pin (e.g. pin 8)
LED cathode (-) connected to GND through a 330Ω resistor

<img width="414" height="228" alt="Screenshot 2026-07-01 at 19 37 04" src="https://github.com/user-attachments/assets/1a72ffa7-c40b-4109-b83c-6d91c6f2fcd2" />


💻 Code

```cpp
void setup() {
  pinMode(8, OUTPUT);
}

void loop() {
  digitalWrite(8, HIGH);
  delay(500);
  digitalWrite(8, LOW);
  delay(500);
}
```

🎯 What I Learned

-Digital output control

-Basic Arduino syntax

-Using delay and loop structure

-Circuit assembly on breadboard




