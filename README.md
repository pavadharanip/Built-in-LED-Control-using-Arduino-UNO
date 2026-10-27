LED Blinking Using Arduino UNO

📌 Project Overview

This project demonstrates how to control the built-in LED on an Arduino UNO board using a simple Arduino program. The LED turns ON and OFF at regular intervals, helping beginners understand digital output control and basic embedded systems programming.

🎯 Objective

- Learn the basics of Arduino UNO programming.
- Understand the "setup()" and "loop()" functions.
- Configure a digital output using "pinMode()".
- Control the built-in LED using "digitalWrite()" and "delay()".

🛠️ Components Required

- Arduino UNO board
- USB cable
- Computer with Arduino IDE

Note: No external LED, resistor, or jumper wires are required because this project uses the built-in LED on the Arduino board.

💻 Source Code

void setup() {
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000);

  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}

⚙️ Working Principle

1. The "setup()" function runs once when the Arduino starts.
2. "pinMode(LED_BUILTIN, OUTPUT)" configures the built-in LED pin as an output.
3. "digitalWrite(LED_BUILTIN, HIGH)" turns the LED ON.
4. "delay(1000)" pauses the program for one second.
5. "digitalWrite(LED_BUILTIN, LOW)" turns the LED OFF.
6. The "loop()" function repeats these steps continuously.

▶️ How to Run

1. Connect the Arduino UNO to your computer using a USB cable.
2. Open the Arduino IDE.
3. Paste the source code into a new sketch.
4. Select Tools → Board → Arduino UNO.
5. Select the correct port under Tools → Port.
6. Click Upload and observe the built-in LED.

✅ Expected Output

The built-in LED blinks continuously, remaining ON for one second and OFF for one second.
## 📸 Hardware Setup

![Arduino UNO Hardware Setup](1000045090.jpg)

📚 Concepts Learned

- Microcontroller programming
- Digital input/output (GPIO)
- Arduino IDE
- Basic C/C++ programming
- Timing control using "delay()"

🚀 Future Improvements

- Change the blinking speed.
- Create different blinking patterns.
- Control the LED using a push button.
- Blink an external LED using a digital pin.

🏁 Conclusion

This beginner-friendly project demonstrates basic digital output control using Arduino UNO. It provides a foundation for learning embedded systems, electronics, and IoT projects.

🔖 Technologies Used

- Hardware: Arduino UNO
- Software: Arduino IDE
- Programming Language: Arduino C/C++
