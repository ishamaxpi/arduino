# What is Arduino???

Arduino is an open-source electronics platform based on hardware (single-board microcontroller) and software (arduino software-**I**ntegrated **D**evelopement **E**nvironment aka **IDE**).  

Generally, arduino-boards are Atmel 8-bit AVR microcontroller based (some like____ are microprocessor based). Arduino-boards have facillity of **analog and digital I/O pins** making it able to interact with the physical world. This is acheived by sending instruction to arduino-boards. This is done with Arduino programming language (typically like C nad C++) and Ardino software (**IDE**).  

<p align="center"> 
<img src="">
</p>

## why to choose Arduino??

1.) Inexpensive  
2.) Cross-platform  
3.) Simple, clear programming environment  
4.) Open source and extensible software  
5.) Open source and extensible hardware  

There are many Arduino-boards designed for different purposes.  

There are many appliactions you can use with Arduino.   

## Arduino and LED

### Hands-on Arduino and LED- LED Blinking

#### Hardware Required

**1.)** Arduino-board  
**2.)** LED  
**3.)** 220-ohm resistor  
**4.)** Jumper wires  

#### Circuit Diagram

<p align="center"> 
<img src="https://user-images.githubusercontent.com/35935951/37853012-da00ea08-2f0a-11e8-9a6a-4d96ce73a96f.png">
</p>

#### Code

```
// the setup function runs once when you press reset or power the board  

void setup()  
{  
  pinMode(LED_BUILTIN, OUTPUT);     // initialize digital pin LED_BUILTIN as an output.  
}  

// the loop function runs over and over again forever  

void loop()  
{  
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)  
  delay(1000);                       // wait for a second  
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW  
  delay(1000);                       // wait for a second  
}  

```



