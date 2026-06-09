# BLE spammer for arduino UNO R4 wifi

> ⚠️ **Disclaimer: Strictly Educational Project.**
> This project is a Proof of Concept (PoC) designed solely to explore, illustrate, and understand how Bluetooth Low Energy (BLE) advertising packets function. 
>
> It is **not** designed to disrupt, saturate, or interfere with the normal operation of third-party devices or networks. The use of this code must be restricted entirely to a controlled testing environment on hardware that you own. The author assumes no responsibility for any misuse or violation of third-party platform terms of service. (please just dont do bad things with it) 

## 📖 About the Project

This repository contains the source code for a technical experiment on Arduino, 

When I received my Arduino Uno R4 WiFi, I thought it was impossible since it's very limited, but it works, so there you go.. 

also my readme is made by ai but my code isnt ;)

## 🛠️ Hardware Requirements

* **Board:** Arduino Uno R4 WiFi. 
* **Cable:** USB-C for power and serial communication.

## 📚 Dependencies and Libraries

To compile this project, you will need to install the following libraries via the Arduino IDE Library Manager:
* `ArduinoBLE`: To handle the Bluetooth stack.
* `Arduino_LED_Matrix`: To control the onboard display.

## 🚀 Features

* **Dynamic BLE Broadcasting:** Allows you to load and broadcast various advertising data structures (payloads).
* **Visual Interface (LED Matrix):** * Displays the name of the currently selected payload as scrolling text. (glitchy as f#ck)
  * Shows status emojis (e.g., startup success/failure, broadcasting status).
* **Serial Monitor Control (115200 baud):**
  * `u` (Up): Switch to the next payload.
  * `d` (Down): Return to the previous payload.
  * `m` (Mode): Start or stop broadcasting (Toggle Spam/Stop).
  * `l` (List): Display the complete list of available payloads in the console.

## ⚙️ Installation and Usage

1. Clone this repository or download the `.ino` source file.
2. Open the project in the Arduino IDE.
3. Ensure you have selected the **Arduino Uno R4 WiFi** in the Boards Manager.
4. Upload the code to your board.
5. Open the **Serial Monitor** (set to 115200 baud) to interact with the program.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for more details. 
