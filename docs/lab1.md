## Lab 1: Artemis
[Return to main page](index.md)

### Objective
The objective of Lab 1 was to setup the Arduino IDE and Artemis board. The lab involved various installations for compatability between the Arduino IDE and Artemis board, as well as exercises to help familiarize with the functions of the Arduino IDE. Since the Artemis board will be used as the microcontroller for future lab projects, it was imperative to learn more about its various functions and features.

### Example 1 - LED Blink:
[![Example 1 - LED Blink](https://img.youtube.com/vi/BLUckYMHRmA/0.jpg)](https://youtube.com/shorts/BLUckYMHRmA)

The first example using the Artemis board involved programming the board with pre-written code through the Arduino IDE. The default Blink program involves flashing an LED on the Artemis board on and off every few seconds. The physical example of this can be seen in the linked video.

### Example 2 - Serial:
[![Example 2 - Serial](https://img.youtube.com/vi/bOGpbKbLozU/0.jpg)](https://youtu.be/bOGpbKbLozU)

<iframe width="560" height="315" src="https://www.youtube.com/embed/bOGpbKbLozU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Another important function of the Artemis board is its ability to recieve serial inputs. For this example, the Arduino IDE was used to pass text inputs into the Artemis board. The microcontroller on the board receives these inputs through serial, which can then be read via the serial viewer within the Arduino IDE. The baud rate had to be increased from the default value of 9600 to 115200 in order for the characters to be readable.

### Example 3 - Analog Read:
[![Example 3 - Analog Read](https://img.youtube.com/vi/W3j5OXLEYZQ/0.jpg)](https://youtu.be/W3j5OXLEYZQ)

The third example involved testing the sensors on the board. This prewritten sample code uses a temperature sensor on the board to send data to the serial terminal, which can be viewed in the Arduino IDE.

### Example 4 - Microphone Output:
[![Example 4 - Microphone Output](https://img.youtube.com/vi/MQVtcWXXAas/0.jpg)](https://youtu.be/MQVtcWXXAas)

The final example introduces the microphone sensor on the Artemis board. An online tone producer was used to output sounds of various frequencies through the laptop speakers. When no sound is playing, the sensor measures the frequency of ambient noise. Once the tone producer is enabled, the Artemis board was able to accurately measure the correct frequencies with slight error.

***
