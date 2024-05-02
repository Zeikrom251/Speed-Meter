# OLED Display Speed Meter

***This Arduino project enables the display of speed on an OLED screen using a potentiometer. The speed value is adjusted using the potentiometer and displayed on the screen in real-time.***

## Components Used
- Arduino Uno
- OLED Display (SSD1306)
- Potentiometer
- Wires

## Libraries Used
- U8glib : A library for monochrome displays, such as OLEDs.
- Adafruit_SSD1306 : A library for SSD1306 based OLED displays.

## How It Works
1. **Initialization :** The necessary libraries are included at the begining of the code.
2. **Display Setup :** The display is set up with its width and height.
3. **Bitmap Images :** Bitmap images are defined for the background.
4. **Main Loop :**
  - The main loop initializes the display and clears it.
  - It reads the analog value from the potentiometer.
  - The analog value is mapped to a suitable range for speed display.
  - The speed value is then displayed on the OLED screen.
**5. Speed Calculation :** The analog value from the potentiometer is converted into a speed value based on a defined mapping.

## Usage
- Connect the components according to the circuit diagram.
- Upload the code to your Arduino Uno.
- Adjust the potentiometer to change the displayed speed.

## Circuit Diagram
![](https://i.ibb.co/rmj3jPh/arduino-oled.jpg)

## Note
- Ensure that the OLED Display and the potentiometer are correctly connected to the Arduino Uno.
- Adjust the code according to your specific requirements, such as changing the speed range or display layout.

[**click to watch**](https://youtu.be/RnRN-e3QYMQ)
