---
layout: post
title: Lab 1
description: Artemis
image: assets/images/lab1.jpg
nav-menu: true
---
<section id="content">

##Objective

The objective of Lab 1 was to familiarize students with using the Arduino IDE with the Artemis board. The lab involved a number of installations for compatability between the Arduino IDE and Artemis board, as well as exercises to help better understand the functions of the Arduino IDE. Some of these functions include the Artemis board LEDs, serial read and write, and different types of sensors. Since the Artemis board will be used as the microcontroller for future lab projects, it was imperative to learn more about its various functions and features.

<h2>Setup</h2>
    <p>The materials required to complete the lab include:</p>
    <ul>
        <li>Arduino IDE</li>
            <ul>
                <li> I downloaded the latest version of the Arduino IDE, verison 2.0.3, from the <a href="https://www.arduino.cc/en/software">official website</a></li>
            </ul>https://www.sparkfun.com/products/15443
        <li>SparkFun RedBoard Artemis Nano</li>
            <ul>
                <li>Details of which can be found <a href="https://www.arduino.cc/en/software">here</a></li>
            </ul>
        <li>USB-C to USB-A Cable</li>
    </ul>

<h2>Example 1 - LED Blink:</h2>

<iframe 
    width="320" 
    height="560" 
    src="https://www.youtube.com/embed/BLUckYMHRmA" 
    title="ECE 4160: Lab 1 Example 1" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>

<p>The first example using the Artemis board involved programming the board with pre-written code through the Arduino IDE. The default Blink program involves flashing an LED on the Artemis board on and off every few seconds. Rhe <b>digitalWrite()</b> function was used to set the LED to high voltage for one second and low voltage for one second. The physical example of this can be seen in the linked video.</p>

<h2>Example 2 - Serial:</h2>

<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/W3j5OXLEYZQ" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>

<p>Another important function of the Artemis board is its ability to recieve serial inputs. For this example, the Arduino IDE was used to pass text inputs into the Artemis board. The microcontroller on the board receives these inputs through serial, which can then be read via the serial viewer within the Arduino IDE. The methods used in this example are the <b>Serial.read()</b> and <b>Serial.write()</b> functions. The baud rate had to be increased from the default value of 9600 to 115200 in order for the characters to be readable.</p>

<h2>Example 3 - Analog Read:</h2>

<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/W3j5OXLEYZQ" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>

<p>The third example involved testing the sensors on the board. This prewritten sample code uses a temperature sensor on the board to send data to the serial terminal, which can be viewed in the Arduino IDE. When the chip was heated up by hand, the temperature reading in the serial window slowly increased over time.</p>

<h2>Example 4 - Microphone Output:</h2>

<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/MQVtcWXXAas" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>

<p>The final example introduces the microphone sensor on the Artemis board. An online tone producer was used to output sounds of various frequencies through the laptop speakers. When no sound is playing, the sensor measures the frequency of ambient noise. Once the tone producer is enabled, the Artemis board was able to accurately measure the correct frequencies, ableit with some slight error.</p>
