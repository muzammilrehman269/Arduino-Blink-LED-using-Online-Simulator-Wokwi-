# Arduino-Blink-LED-using-Online-Simulator-Wokwi-
This is a simple project that simulates an LED blinking using an Arduino Uno in [Wokwi Simulator]
## Description
This is a simple project that simulates an LED blinking using an Arduino Uno in [Wokwi Simulator](https://wokwi.com/).

## What It Does
Turns an LED on and off every second
Uses basic Arduino functions: 'pinMode()', 'digitalWrite()', and 'delay()'.
## Code
This code is written in cpp
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
