This repository contains two implementations of AI-based recognition:

Huskylens with Arduino
Face Recognition – Detects and identifies faces using Huskylens AI camera.
OpenCV with Python
Color Recognition – Detects and labels colors in uploaded images.


 task1: Face Recognition using Huskylens (Arduino)
 Requirements :
 
 Hardware:
-Huskylens AI Camera

-Arduino Uno (or compatible board)

-Jumper wires (for I2C connection)


Software:

-Arduino IDE

-Huskylens Library (install via Library Manager)

-How Face Recognition Works?

-Huskylens detects a face and assigns it a unique Face ID.

-The Face ID is stored and used for recognition.

-When the same face is detected, it retrieves the stored ID.

-You can assign custom names to specific Face IDs for easier identification.




![image](https://github.com/user-attachments/assets/fa8a6a36-8ed4-46f3-977c-a39e43df4ebc)



task 2 : Color Recognition using OpenCV (Python)


Requirements :
Python 3.x

OpenCV

NumPy

Google Colab or Jupyter Notebook (if running online)

How Color Recognition Works?:

-Loads an image and converts it to HSV color space.

-Predefined color ranges are used to detect specific colors (Red, Green, Blue, Yellow).

-The script highlights detected colors and labels them.

-Displays the processed image with color names.




![Screenshot 2025-02-12 085215](https://github.com/user-attachments/assets/b8a65baf-9687-4a77-b891-d34e51a5d5b6)
