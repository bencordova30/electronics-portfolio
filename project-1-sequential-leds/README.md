# Project 1: Sequential LED Blink
My first Arduino project - making 3 LEDS blink one after another.

### What I learned
-How to wire LEDS with resistors
-Basic Arduino Code
-How to troubleshoot wrong connections

### Demo Video
[Watch the video here](https://www.tiktok.com/t/ZTU4eAmdD/)

### Code 
```cpp
//Paste your full Arduino code below this line
// Define the LED pins
const int ledPin1 = 12;
const int ledPin2 = 11;
const int ledPin3 = 10;

void setup() {
  // Set all LED pins as outputs
  pinMode(ledPin1, OUTPUT);
  pinMode(ledPin2, OUTPUT);
  pinMode(ledPin3, OUTPUT);
}

void loop() {
  
  digitalWrite(ledPin1, HIGH);
  delay(500);
  digitalWrite(ledPin1, HIGH);
  
  digitalWrite(ledPin2, HIGH);
  delay(500);
  digitalWrite(ledPin2, HIGH);
  
  digitalWrite(ledPin3, HIGH);
  delay(500);
  digitalWrite(ledPin3, HIGH);

}

