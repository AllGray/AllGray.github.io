---
title: MAKERbuino Build Guide

toc_footers:
  - <a href='https://community.makerbuino.com'>Sign Up at our community for more information</a>
  - <a href='https://github.com/lord/slate'>Documentation Powered by Slate</a>
  - <a href='https://github.com/allgray'>Documentation converted by Mathias "AllGray" Thur</a>
  
search: true
rightHandPanel: false
  
---

# Introduction

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/648px-MAKERbuino-buildGuide-1.bmp.png)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/2.png)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/3.png)

# General Description

MAKERbuino is a DIY gaming platform suited for makers. 

It’s based on Arduino and compatible with Gamebuino. 

MAKERbuino project encourages and helps people learn STEM (Science, Technology, Engineering and Mathematics) in a fun and interesting way. 

MAKERbuino allows you to develop your hardware and software skills. 

Make video games, explore new hardware solutions, learn from numerous tutorials and share your work with the community.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/4.jpg)

![Video](embed url=https://youtu.be/roSKvLbrUek)

This is the Official MAKERbuino Kit Build Guide.

For more information visit www.makerbuino.com, and follow the MAKERbuino project on 
[Facebook](https://facebook.com/makerbuino) [Twitter](https://twitter.com/makerbuino) [Google+](https://plus.google.com/u/1/104547318890896420704) [Instagram](http://instagram.com/makerbuino) [YouTube](https://www.youtube.com/channel/UCVUvt1CeoZpCSnwg3oBMsOQ).

# Age Group

Our estimation is that an 11 year-old kid should be able to assemble the MAKERbuino with a tiny bit of help from an adult and thus, estimated age group is 11+.

Estimated build time: **2 hours 30 minutes.** Build time varies and depends on the skills of the person and if the person has ever soldered before.

MAKERbuino was made with purpose of bringing STEM (Science, Technology, Engineering and Mathematics) to people in a fun and interesting way. 

Despite that, it is not the best entry level kit and if you never soldered before you should think about doing some preparatory practice or soldering a simpler kit.

# Required Skills

MAKERbuino comes as a DIY kit. 

It requires basic soldering and assembly skills to put together. 

This kit was designed to be assembled as easy as possible, however, if you never soldered before, it might be a good idea to get some practice first. 

Nevertheless, with enough patience and care, a total newbie can assemble this kit by precisely following these build instructions.

## Skills That Will Ease the Process of Assembling the MAKERbuino:

* Basic soldering experience (some preparatory experience)
* Ability to recognize the basic electronic components

## What You’ll Learn With the MAKERbuino

MAKERbuino’s main goal to educate and motivate you to learn something new or brush the skills you already have. 

In the process of making the MAKERbuino and developing your own MAKERbuino compatible software and hardware you’ll learn:

* How to solder
* What are the basic electronic components and what is their *function
* How can electronic components be connected and why
* What are microcontrollers and some basics of digital electronics
* How to program a microcontroller in C/C++
* What are 3D printers and how to modify and design your own *unique* 3D printed casing
* How to extend beyond MAKERbuino’s capabilities by adding various expansion modules

# What’s In the Box?
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/5.jpg)

<aside class="notice">Box art design might vary depending on when you bought your kit - the old box is displayed in this picture, kits bought in 2017 have an updated box art</aside>

You managed to get your very own basic MAKERbuino kit! 

Well done and thanks for supporting the project and the “STEM through fun” initiative. 

First of all, follow the list of included components and the text below and make sure that you have all the required components laid out on your table and ready for soldering.

For more advanced makers, here is the MAKERbuino’s schematic you can download. Take a peek before building the thing.

If you don’t know how to read these diagrams, you don’t have to worry, you’ll learn.

Click here to view the schematics: [MAKERbuino-schematic.png](https://github.com/AllGray/slate/blob/master/images/MAKERbuino-schematic.png)

Also, this diagram of the main parts of the MAKERbuino console is super useful:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/6.jpg)


### List of Included Components

Label | Component Name | Minimal Quantity
--------- | ------- | -----------
NO LABEL	| MAKERbuino PCB | 1
NO LABEL	| laser cut acrylic casing (consists of 3 pieces)	| 1
NO LABEL	| M3 nylon screws	| 4
NO LABEL	| M3 nylon nuts	| 4
NO LABEL	| M3 6mm nylon hex distancer	| 8
NO LABEL	| M2 nylon (or metal) screws	| 4
NO LABEL	| M2 nylon (or metal) nuts	| 4
NO LABEL	| 128MB Micro SD card + SD adapter	| 1
NO LABEL	| SD socket	| 1
NO LABEL	| 8ohm 0.5W speaker - 28mm diameter	| 1
NO LABEL	| Li-Po battery (650mAh, single cell - 3.7V) with male JST connector	| 1
NO LABEL	| female JST battery connector	| 1
NO LABEL	| USB to RS232 adapter board (serial programmer)	| 1
U1	| ATmega328P-PU microcontroller	| 1
NO LABEL	| 28 pin IC socket (for the ATmega328P)	| 1
LCD	| Nokia 5110 LCD breakout board	| 1
NO LABEL	| female header socket (for connecting the screen)	| 1
NO LABEL	| TP4056 Li-Po battery charger board	| 1
IC2	| 3.3V voltage regulator (MCP1702-3302E in TO-92 package)	| 1
T1	| 2n2222 general purpose NPN transistor	| 1
Q1	| 16MHz crystal	| 1
D1	| 1N4148 diode	| 1
SWITCH1, SWITCH2	| 3 pin slide toggle switch	| 2
C1, C6	| 100nF ceramic capacitor	| 2
C2, C3	| 22pF ceramic capacitor	| 2
C4, C5, C7	| 100uF, 6.3V radial electrolytic capacitor	| 3
BTN	| 12x12x7.3mm pushbutton with button cap	| 7
JP1	| standard double row 3x2 pin angle headers (male) - for SPI port	| 1
JP2	| standard single row 6 pin angle headers (female) - for Serial port	| 1
JP3, JP4	| KF2510-4P angle connector (male + female) - for i2c port	| 2
BREAKOUT	| standard double row 5x2 pin angle headers (male) - for breakout port	| 1
TM1, TM2	| 1Kohm wheel trim potentiometer	| 2
R1	| 2Kohm resistor	| 1
R2, R3	| 10Kohm resistor	| 2
R4, R5	| 4.7kohm resistor	| 2
R6	| 100ohm resistor	| 1
X1	| 3.5mm headphone connector socket	| 1
NO LABEL	| Some thin insulated copper wire (standard and solid core wire)	| 1

<aside class="warning">We tend to place some extra spare components in your MAKERbuino kit. Quantity listed in the above table is the absolute minimum of components required for your MAKERbuino to work, you'll probably get some extra.</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/7.jpg)
**If you’re not sure what every of these components looks like, don’t worry. In the following section we’ll analyze the components and their purpose.**

# MAKERbuino PCB

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/8.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/9.jpg)

PCB stands for printed circuit board. 

Basically, this is a board with some copper traces and some other components like protective paint and insulating material. 

Copper layers of the board form traces that connect various MAKERbuino’s electronic components (e.g. they connect the microcontroller to the screen) so that they can work together as an electronic device.

<aside class="notice">MAKERbuino's PCB color might vary depending on when you bought your kit. Latest PCBs are colored red. We plan to offer various PCB colors as an extra option in the shop soon</aside>

## Laser Cut Acrylic Casing

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/10.jpg)

MAKERbuino’s circuitry is protected by a casing made out of laser cut plastic (they're made on a CNC laser cutting machine). 

The casing consists of 3 pieces (see the picture). 

One piece is used to protect the front (top) side of your MAKERbuino device and the other two pieces protect MAKERbuino's back.

Everything is stacked one on another using nuts, bolts and plastic spacers. This style of casings is called "the sandwich design".

We'll explain how to assemble the casing at the end of this build guide.

## Nuts, Bolts and Spacers

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/11.jpg)
These basic mechanical components are needed at the end of MAKERbuino assembly process for fixating the circuit board to the casing. 

M3 or M2 in the name of the screws indicates that the screw’s shaft’s diameter is 3 mm or 2 mm. 

Depeding on the verion, you might get metal screws instead of plastic ones (latest versions of the kit come with plastic screws made out of nylon).

## SD card

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/12.jpg)

The included SD card is used for storing games, programs and other useful data on it (game graphics, music etc.). 

Thanks to this card, you can load multiple on your MAKERbuino. 

It comes preloaded with lots of fun games downloaded from the games gallery on www.gamebuino.com so that you can try it out right after you assemble it. 

You might be wondering, why is the SD card’s capacity mere 128 MB? This is an 8-bit gameboy-like gaming device and programs and games for it are approximately 30 kB. 

128 MB of space will be more than enough for storing plenty of games, programs and useful info.

<aside class="notice">some older versions of the kit were sold with larger SD cards (1GB or 512MB)</aside>

## SD Socket
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/13.png)

The SD socket is the only surface mount component in the whole device. 

Don’t let the look of it discourage you, SD socket’s leads are so big that anyone can solder it with a tiny bit of patience. 

The socket is soldered to the back side of the PCB and you insert your precious SD card inside.

## Speaker
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/14.png)

This neat little speaker fits at the back side of the device. 

It has a special place in the back of the casing. 

It plays a crucial role in producing all the beeps, boops and crazy chiptunes you’ll compose in your very own games.

<aside class="notice">Standard diameter of the MAKERbuino speaker is 36mm but some kits came with smaller or larger speakers because we had some problems with getting the sufficient quantities</aside>

## Li-Po Battery & JST Connector

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/15.jpg)

The rechargeable battery serves as MAKERbuino’s main power supply. 

650mAh is more than enough for several hours of intense gaming and powering all sorts of power-hungry expansion modules (like GPS receivers, motors, wifi modules, etc.). 

In case you didn’t know, “Li-Po” in the name of the battery indicates its structure and what materials it uses to store electrical energy (Li-Po stands for Lithium Polymer). 

It comes with the male JST power connector that is then connected to the female JST connector soldered directly to the board.

## RS232 Serial UART adapter

USB to RS232 serial UART adapter

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/16.jpg)

This board is connected to MAKERbuino’s serial port (top left black female angle connector). 

It allows you to program your MAKERbuino directly from your computer and send all sorts of useful data from the computer to the MAKERbuino and vice versa.

<aside class="warning">Your MAKERbuino kit might come with the blue or red version of this adapter depending on when you bought your kit. Latest kit revision comes with the red adapter. The two serial adapter boards do the same thing. There's more info on how to use this board later in the guide.</aside>

## ATmega328P-PU Microcontroller

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/17.png)

The ATmega microcomputer (aka. microcontroller) is the brain of the device. 

CPU, RAM memory, flash memory and almost all parts needed for executing programs and games and doing all the smart work. 

Basically, this is a computer in a chip. ATmega328’s astonishing 2kB of RAM and an 8-bit CPU at 16MHz of frequency will bring out the nostalgia and provide you with the authentic old school retro experience. 

It comes with a special dedicated 28 pin socket for easy microcomputer replacement.

## Nokia 5110 LCD
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/18.jpg)

The screen module is an LCD screen on a breakout PCB. 

LCD stands for liquid crystal display. This is a screen that is controlled by the main ATmega microcomputer. 

It’s a graphical display so you can manipulate every pixel’s color with a program in the microcomputer. 

The complete module is stacked on the main MAKERbuino PCB. 

Newer versions of the MAKERbuino kit (version “0.4 beta” and newer) has this screen attached using headers so that you can easily replace the screen if it gets broken. 

Also, the screen has some magnificent features like high resolution (84x48 pixels monochrome), adjustable LED backlight and great visibility on direct sunlight (the display works in the same way as your calculator’s display - can be viewed without the backlight if there is enough light in the room).

<aside class="warning">New version of the kit come with a female header socket which is first soldered to the PCB before connecting your screen. This way you can easily insert and remove the screen fro the board</aside>

## TP4056 Li-Po Battery Charger Board

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/19.png)

This module is stacked and soldered on the main MAKERbuino board. 

It contains the components needed for charging the rechargeable Li-Po battery. 

It’s main thing is the TP4056 charger integrated circuit (the little black chip on the board). 

It’s regulating voltage and current of electricity inputted by the USB port and feeding it to the Li-Po battery.

<aside class="notice">Depending on the version, your MAKERbuino kit might have the mini USB version or the micro USB version of the charger board included (the new ones come with micro USB). USB cables for both versions of the board are easy to find in any electronics store.</aside>

## 3.3V Voltage Regulator

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/20.jpg)

The voltage regulator is one of MAKERbuino’s most important parts. 

It regulates the voltage from the Li-Po battery to stable 3.3V. We need to do that because the battery’s 3.7V of electricity is just too much for MAKERbuino’s circuitry and would fry the SD card. 

Most people say, hey this is a transistor… no, this is not a transistor. 

This exact shape of this 3 tiny 3 leaded black component is called the TO-92 package and it looks the same as the 2n2222 transistor listed below.

<aside class="warning">The only difference between the 2n2222 transistor and this voltage regulator is the text written on the component. The regulator should have MCP1702-3302ET written on it’s surface, whilst the transistor will have 2N2222 written on it’s back. Use a magnifier if needed and check carefully if you have the right component. When soldering the regulator be extra cautious not to accidentally swap it with the transistor.</aside>

## 2n2222 General Purpose NPN Transistor

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/21.jpg)

The general purpose transistor is used in the part of the MAKERbuino dedicated to producing sound. 

The transistor serves as an amplifier that drives the console’s speaker. 

As said when describing the regulator above, don’t let the shape of this component trick you, this is not a regulator (mind the tiny "2N2222" written on it!).

## 16MHz Crystal

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/22.jpg)

Inside this metallic package is a crystal used in the MAKERbuino’s microcomputer’s oscillator circuit. 

In other words, MAKERbuino’s neat 16MHz of CPU clock is possible thanks to this component. 

Standard digital clocks and watches work on the same principle.

<aside class="warning">Make sure that your crystal has 16.000 written on it’s package, this means that it’s meant to be used in an oscillating circuit at the frequency of 16 000 kHz = 16 MHz.</aside>

## 1N4148 Diode

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/23.jpg)

This is a standard diode. 

It’s used in MAKERbuino’s sound circuit.

<aside class="notice">This is NOT a light emitting diode (LED), it doesn’t light up, it’s used as an essential part of the sound’s circuit amplifier.</aside>

## 3 Pin Toggle Switches

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/24.jpg)

These 3 leaded standard switches are used for turning your MAKERbuino ON and OFF and muting the speaker. 
<aside class="notice">You get two of these switches!</aside>

## Capacitors

There are three different types of capacitors you have in your MAKERbuino kit

* 100uF Electrolytic Capacitors

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/25.jpg)

* 100nF Ceramic Capacitors

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/26.jpg)
<aside class="notice">You need to have two of these capactirs</aside>

The tiny yellowish capacitor with 104 written on it is a 100nF capacitor used for filtration and in connection with serial programmer.


* 22pF Ceramic Capacitors

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/27.jpg)
<aside class="notice">You need to have two of these capacitors</aside>

These capacitors are used as a part of the 16MHz oscillating circuit along with the previously listed crystal. 

They look similar to the 100nF capacitors so don’t let that trick you. 

Recognize them by number 22 (symbolizing that they have the capacity of 22pF) written on their surface.


## Pushbuttons & Button Caps

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/28.jpg)

Nice and clicky big square pushbuttons are pretty self explanatory. 

They’re MAKERbuino’s essential input devices used for switching menus, changing programs, playing games… 

Button caps are just simply attached to the button’s top side and can be changed.

<aside class="notice">You need to have 7 pushbuttons and 7 button caps in your package</aside>
<aside class="notice">You can buy some extra button caps online in our shop or in almost every electronics shop by searching for 12x12x7.3mm pushbutton caps</aside>

## Various Pin Headers & Connectors

All these pins and headers are used for connecting various modules, expansions and programmers to your MAKERbuino board. 

There are four types of connectors included in the MAKERbuino kit

* 6 pin female header

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/29.jpg)

This tiny black connector is used for connecting your MAKERbuino to the serial UART programmer board (important for programming the console).

* 2x3 male angle ICPS header

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/30.jpg)

Used for connecting expansion modules and reprogramming the game console’s microcontroller over ICSP (in circuit system programming) protocol.

* KF2510 anti reverse angle headers (for i2c ports)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/31.jpg)
<aside class="notice">You need to have two of these</aside>

These yellowish connectors go to the top side of the device and are used for connecting expansion modules and other MAKERbuinos or Gamebuinos (multiplayer games!) 

They’re just like all other connectors but with a special anti-reverse function so that you can’t short circuit your game consoles when connecting them with the multiplayer link cable.


* 2x5 male angle extra breakout header

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/32.jpg)

The 10 pin double row angle header is soldered to the rightmost part of the game console and is an extra option that gives you some extra useful pins for connecting hardware expansions.

## Trim Potentiometers

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/33.jpg)

The tiny wheel potentiometers are very important for regulating the screen’s backlight and dimming the sound volume. 

The potentiometers have B102 written on their back indicating that they have 1Kohm of resistance (10 * 10^2 ohms).

<aside class="notice">You have two of these included in your kit</aside>

## Resistors

Standard passive two-terminal electronic components that implement electrical resistance as a circuit element. 

The resistors are used in MAKERbuino for all sorts of important tasks like adjusting signal levels and regulating current flow. 

There’s three types of resistors used in the MAKERbuino kit. 

Every resistor’s resistance is measured in ohms. 

You can determine the resistance of a resistor by using color code - reading a set of colored rings on the resistor. 

If you already don’t know all this stuff by heart, here is a useful table for using the resistor color code:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/34.jpg)

Resistors that you need to have: - 100 ohm resistor x1 This one is used when outputting sound to MAKERbuino’s headphone jack.

It should have this color combination: brown, black, brown, golden

<aside class="notice">2k ohm resistor x1 This one is important for driving the transistor in the MAKERbuino’s sound circuit. It should have this color code combination: red, black, black, brown, brown(or golden)</aside>

<aside class="notice">4.7k ohm resistor x2 These resistors are used as pull up resistors on i2c lines (multiplayer and exapnsion ports). They should have this color code: yellow, purple, red, golden or yellow, purple, black, brown, brown</aside>

<aside class="notice">10k ohm resistor x2 These are important for driving the LCD screen and connecting the microcontroller to the serial UART programmer (for connecting the MAKERbuino to your computer). Color code: brown, black, black, red, golden(or brown)</aside>

## Why Are There Tiny Pieces Of Wire Inside?

Your kit also comes with a few pieces of wire. 

These are not included in your kit as a result of a mistake, you need them for connecting the speaker to the MAKERbuino PCB and fixating the Li-Po charger.

# Tools

You’ve carefully read the previous section and checked that you have all the components, good job! 

There are some tools and equipment that are required for the assembly and they are not included. 

If you don't have them, now would be a good time to borrow or purchase them. 

These tools are useful whenever assembling, fixing or modifying electronic devices and should be the part of every maker’s/hacker’s/moder’s/electrician’s equipment. 

Many of these are available in a supermarket or in some professional DIY electronics stores like Radio Shack, Adafruit, Sparkfun...

## Soldering Iron

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/35.jpg)

Any entry level 'all-in-one' soldering iron that you might find at your local hardware store should work (recommended power - something around 30W). 

It’s a good idea to upgrade to a more expensive soldering station with temperature regulation if you plan to dive into the world of DIY electronics more thoroughly.

## Solder

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/36.jpg)

We highly advise buying a rosin core, 60/40 solder. 

This type of solder is usually preferred with the DIY electronics community for similar soldering projects. 

Be careful with buying solder, bad solder leads to lots of complications like bad solder joints and unwanted bridging.

## Diagonal Cutter Pliers

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/37.jpg)

You’ll need pliers like this to trim leads of soldered components and cut wires.

## Desoldering Vacuum Tool (aka. Solder Sucker)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/38.jpg)

This tool is useful in cleaning up soldering mistakes

## Hot Glue Gun OR Some Super Glue OR Some Insulating Tape

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/39.jpg)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/40.jpg)

You’ll need some sort of adhesive to fixate the battery and the speaker to the back plate. 

Our advice: a hot glue gun is the best choice here, but a tube of superglue or some insulating tape you can buy in a supermarket will also do the job.

## Helping Third Hand With Magnification - *optional*

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/41.jpg)

This one is not absolutely necessary but will make your life (...and soldering) much easier.

## Multimeter - *optional*

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/42.jpg)

You can solder this kit without the multimeter but it will prove useful for testing some tricky connections and measuring supply voltage. Besides, if you plan to do DIY electronics, a basic multimeter that can measure voltage and continuity is a must-have.

## Solder Wick - *optional*

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/43.jpg)

It’s used along the desoldering vacuum tool to clean up soldering mistakes. 

This one would come particularly handy when soldering the SD socket on the MAKERbuino board.


# Assembly

Have you ever soldered before? If your answer is "yes", then you probably you'll know what you're doing. 

In case you never soldered before, please take a look at the following how-to-solder guides:

[Adafruit's video tutorial](https://youtu.be/QKbJxytERvg) - a tutorial featuring Collin Cunningham, a super charismatic electronics guru

[Adafruit's standard soldering tutorial](https://learn.adafruit.com/adafruit-guide-excellent-soldering?view=all) - A great and thorough video tutorial. 

An absolute must-read, even if you know how to solder. 

Make sure to check the "common soldering mistakes" section at the end.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/44.jpg)
* we do not own the copyright to this picture. [Picture Soruce](https://learn.adafruit.com/adafruit-guide-excellent-soldering?view=all)

[Sprakfun's video soldering tutorial](https://www.youtube.com/watch?v=f95i88OSWB4) - Another well made how-to-solder video tutorial.
[Sparkfun's standard soldering tutorial](https://learn.sparkfun.com/tutorials/how-to-solder---through-hole-soldering) - Well written tutorial made by Sparkfun

## Motivational tip from Albert Gajšak (The Creator of MAKERbuino):

Soldering is an essential skill if you want to become an electronics ninja one day. 

Don't get frustrated by soldering failure, it's just a matter of practice. 

You'll get better in it over time soldering kits like MAKERbuino and other fun projects you decide to make. 

Good luck with your kit, try to do your best. 

In the worst case scenario, if you tried everything and still can't make your kit work, together we'll make your creation work.



Ok, now you have the required tools and you’ve read the previous section and checked that you have all the parts needed. 

Let’s get down to business!

<aside class="notice">PRO TIP: we suggest that you build the MAKERbuino when you’re fresh because the proces of assembly can take up to 2.5 or even 3.5 hours depending on your soldering skills (in other words, don’t start building it in 2AM)</aside>

We divided the process of assembly in a few main steps and we’ll guide you throughout the assembly methodically.

## SD Card Socket

The only SMD component in the kit and probably the trickiest one to solder. 

Don’t let the word “SMD” discourage you, the socket is so big that a newbie can solder it with a 3$ soldering iron. 

Nevertheless, some extra patience is required. 

Find the SD socket, place it on the back side of the board where there is a big “SD SOCKET” text written on it.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/45.jpg)

Continue by soldering the four pads of the socket’s shielding.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/46.jpg)

When soldering the socket’s contacts, you DON’T have to solder the three rightmost pins because they are not used.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/47.jpg)

## Microcontroller

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/48.jpg)

The microcomputer (aka. microcontroller) socket is also soldered at the back of the MAKERbuino board. 

<aside class="warning">Be careful how you rotate the socket because it’s not symmetrical. Be sure to place it on the right indicated by a notch on the socket</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/49.jpg)

<aside class="notice">PRO TIP: First solder the two diagonal pins of the socket. Then make sure that the socket is aligned with the board nicely, correct the alignment if needed and then solder the rest of the pins</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/50.jpg)

## 10kΩ Resistor

Find the tiny 10kΩ resistor (colors: brown, black, red, golden) and solder it to the front side of the board where the R2 mark is (bottom side of the board)

This resistor is necessary for our screen to work.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/51.jpg)

<aside class="notice">PRO TIP: When, you insert the resistor, bend the leads of the resistor so that it doesn’t fall out from the PCB while you’re soldering it</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/52.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/53.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/54.jpg)

<aside class="warning">Remember to cut all leads of the components you’ve soldered using your diagonal cutters</aside> 

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/55.jpg)


## 16MHz Crystal

Find the 16MHz crystal and insert it on the front side of the PCB (right side of the PCB, marked Q1, 16MHz)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/56.jpg)

Apply the previous pro tip and bend the leads of the crystal at the back of the board.


## 22pF Ceramic Capacitors

Solder the two 22pF ceramic capacitors (little red-ish thingies with the number 22 written on them). 

Along with the crystal, these are essential for the oscillating circuit of the game console.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/57.jpg)


## Toggle Switches

Slide toggle switches for turning the console ON and OFF and muting the sound. 

They’re soldered at the bottom side of the PCB and labeled as SWITCH1 & SWITCH2.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/58.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/59.jpg)

The left switch is muting the sound adn the right one will turn the console’s power ON & OFF.

## Electrolytic Capacitors

Locate the three electrolytic capacitors (tiny black barrels with two leads). 

These are marked on the PCB as C4, C5 and C7.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/60.jpg)

<aside class="warning">These capacitors are polarized, make sure to insert them properly. Polarity of the capacitors are indicated with the big white minus (-) sign on the capacitors (the big white stripe)</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/61.jpg)


## MCP1702-3302 3.3V Voltage Regulator

MCP1702-3302 3.3V voltage regulator. 

<aside class="warning">This regulator is very similar to the 2n2222 transistor so be sure to read the text on the component carefully and make sure that it says something like “1702-3302”</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/62.jpg)

Solder the thing on the board where “IC2 3.3V” is marked. Be careful to turn it on the right side!

## LCD Screen

<aside class="notice">Older versions of the MAKERbuino kit had a screen that was soldered directly on the PCB. Now the screen can be easily detached and changed because of the female connector that is soldered first</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/63.jpg)

You will have to solder the tiny female connector first and then plug the Nokia screen into the connector. 

<aside class="notice">PRO TIP: First solder one lead of the bottom connector then check if the screen is aligned properly and corect the allignment if needed. When the connector fits nicely on the board, solder the rest of it’s leads</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/64.jpg)

Attach your screen to the socket you've soldered to the PCB.

<aside class="warning">Fasten the screen with tiny M2 nuts and bolts. After you've fastened your screen, it will be slightly tilted when compared to the rest of the device. This is completely normal and is nothing to be worried about</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/65.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/66.jpg)

## Battery and Connector

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/67.jpg)

Firstly, we’ll solder the battery’s connector to the pads on the top left back side of the board (labeled “BATTERY”)

<aside class="notice">PRO TIP: First apply some solder to the pads and then solder the connector to the pads</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/68.jpg)

<aside class="warning">In electronics, certain wire colors are used for labeling the polarity. Color RED is always the positive pole (+) of the power supply and the color BLACK is always representing the negative pole (-) of the power supply</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/69.jpg)

## ATmega328 Microcontroller

Insert the ATmega328 microcontroller in the already soldered socket

Find the little black precious microcomputer. Here comes the tricky part:

<aside class="warning">Most common mistake that people do with the microcontroller is that they either insert it in the socket wrongly or break the microcontroller’s tiny pins in the process of inserting it. Don’t worry, it just need a tiny bit of caution and concentration (don’t hurry with this one):</aside>

Firstly, locate the microcontroller’s notch indicating which side to turn it when inserting it in the socket.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/70.jpg)

Secondly, **DON’T** insert the microcontroller straight away. 

You’ll need to bend the pins a bit. 

Do this pushing the microcontroller’s pins against the table so that you apply equal force to all pins.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/71.jpg)

Check if some of the pins is not bent correctly and correct that. 

Slowly insert the microcontroller in the socket. 

If needed, take the chip out and bend the pins some more. 

The chip fully inserted in the socket looks something like this:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/72.jpg)

## Testing 

Now we’re going to test if all of our core MAKERbuino parts we’ve just soldered work properly
Connect the battery to the already soldered battery jack.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/73.jpg)

Turn the power switch to the left position (ON).

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/74.jpg)

The screen should turn on and display some text. 

If that happened, that means all of the components so far work fine and are properly soldered. 

Don’t worry if your screen is too dim (like mine on the picture above), we’re going to fix that in the settings when we solder the rest of the components. 

It might also display the text saying “battery low, please turn off”, don’t worry about that.

**Your screen didn’t turn on?** some of the common mistakes:

* The microcontroller is inserted wrongly into the socket
* The polarity of the battery connector is swapped
* Some contacts are shorted or improperly soldered, make sure to check all of them

If the screen is working fine that means that the microcontroller is working and the voltage regulator is doing a good job powering the microcontroller.

**Now unplug the battery** (so that you don’t short circuit it when soldering the rest of the components).

## 10kΩ Resistor (Labeled R3)

Solder the second 10kΩ resistor (labeled R3)

(Colors: brown, black, red, golden)

This resistors is important for connecting the microcontroller to the serial UART programmer board.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/75.jpg)

## Female 6 Pin Angle Header

Locate this black female connector. 

It’s soldered to the place labeled “JP2, serial programmer”. 

The serial UART programmer board is connected to this port. 

Make sure to turn it the right way.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/76.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/77.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/78.jpg)

## Potentiometers TR1 & TR2

Solder the two trim potentiometers labeled TR1 & TR2

The left potentiometer is used for regulating the screen’s backlight and the right one regulates the sound volume.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/79.jpg)

<aside class="notice">PRO TIP: If the trim potentiometers are falling out of the PCB when you try to solder them, place you cutting pliers’ handle underneath the potentiometer you’re soldering</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/80.jpg)

## 6 pin ICPS Header & 100nF Capacitors

The header is mounted on the top left front side of the PCB (labeled JP1). 

After the header, find the two little 100nF capacitors (they have 104 written on their surface) and solder them on places labeled with C1 and C6.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/81.jpg)

## Pushbuttons

Seven pushbuttons and the corresponding button caps

Locate the buttons and then first solder the 5 buttons on the left side of the PCB.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/82.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/83.jpg)

## Sound Circuit:

Now let’s solder the basic parts of the sound circuit:

2n2222 transistor, 2.2kΩ resistor (color code: red, red, red, golden), 1n4148 diode and the headphone connector.

<aside class="warning">Be careful to turn the transistor and the diode to the right side! Note the little black ring on the diode indicating how you need to turn the component</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/84.jpg)

## Buttons

Solder the rest of the buttons

(Two buttons at the right side of the PCB)

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/85.jpg)

## Li-Po Charger Board

Mount the Li-Po charger board
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/86.jpg)

You’ll need a piece of solid core wire included in the kit (NOT the soft standard wire).

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/87.jpg)

You must remove the insulation of the wire and cut it in 4 even parts.

<aside class="notice">PRO TIP: Use your cutter pliers for this</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/88.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/89.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/90.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/91.jpg)

Insert the wire through the charger’s and PCB’s contacts and bend the edges of the non insulated pieces of wire before soldering them.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/92.jpg)

## 4.7kΩ Resistors

Two 4.7kΩ resistors (color code: yellow, purple, red, golden) and a 100Ω resistor (color code: brown, black, black, golden) - labeled R4, R5 and R6. 4.7kΩ resistors are used as pull up resistors for the i2c ports and the 100Ω resistor is used when outputting the sound signal to the headphone jack.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/93.jpg)

## i2c Multiplayer Headers

Yellow i2c multiplayer headers

These are labeled as JP3 and JP4 on the board. Use the pro tip about placing the pliers underneath the component becuse these might be a bit harder to solder.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/94.jpg)

## Speaker

Solder The Speaker

First you have to find the standard soft wire, strip the insulation at it’s ends and apply some solder to the freshly stripped ends.

<aside class="notice">PRO TIP: Strip the insulation with your cutter pliers and twirl the stripped ends of the wire before apllying some solder to it</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/95.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/96.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/97.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/98.jpg)

Then apply some solder to the speaker’s contacts and solder the wires to the speaker and to the pads labeled “SPEAKER” on the PCB.

<aside class="warning">You don’t have to care about the polarity on this one, the speakers that are included are not polarized</aside>

Take a look at the picture to see where the actual soldering points of the speaker are.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/99.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/100.jpg)

## Before Turning Your Soldering Iron Off

Before turning your soldering iron off, you can solder the extra breakout header.

This is an extra and not necessary for normal functionality of the MAKERbuino gaming device. 

The breakout header will come in handy if you plan to hack/mod/customize your MAKERbuino.

## TEST Everything

Now that you have everything soldered, connect the battery again, turn the tiny wheel potentiometers completely to the left (clockwise) and turn the console on.

* Try dimming the backlight with the left (TM2) potentiometer
* You should hear the signature MAKERbuino sound when you turn the console on. Try muting/unmuting the sound with the left switch (SWITCH2) and dimming it with the right potentiometer (TM1)
* If you see the low battery error on the screen, press the A button to bypass it
* Go through the checkup wizard and adjust your MAKERbuino’s screen contrast and check if all buttons work properly

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/101.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/102.jpg)

* Save the settings and turn the console OFF
* Insert the SD card

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/103.jpg)

* Turn the console ON and press button C at the main screen, the device will load the games stored on the SD card. You will get this screen:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/104.jpg)

<aside class="warning">Don’t panic, loading games from the SD card can take up to 30 seconds, be patient. After the games load you should see something like this:</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/105.jpg)

If you passed all of the steps above and everything worked fine and dandy in the checkup wizard, that means you did a good job. 
**Well done!**

## The last step

The last step is to place place the circuitry inside the laser cut casing. 

You'll need the M3 nuts, bolts and spacers for this. 

Glue the speaker to the casing using any regular type of glue (our recommendation: use a hot glue gun if possible).

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/106.jpg)

Now use the screws and spacers to fasten the casing. 
<aside class="notice">Note that MAKERbuino's back casing actually consists of two acrylic plates.</aside>

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/107.jpg)

Use a regular screwdriver to fasten the back screws.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/108.jpg)

MAKERbuino's front plate is fixated with nuts.

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/109.jpg)

Back side of a finished MAKERbuino:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/110.jpg)

Front side of a finished MAKERbuino:

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/111.jpg)

**The programmer:** USB to serial UART board is connected to the MAKERbuino as showed on the pictures below. Mind the orientation of the serial adapter (you can check whether you've plugged it in correctly by looking at the pin names labeled at MAKERbuino's PCB and the programmer (the labeled pins should match)).

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/112.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/113.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/114.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/115.jpg)

We'll talk more about how and what for you can use the programmer board in a "how to program your MAKERbuino" tutorial (still being written... lots of documentation is still WIP (Work In Progress) and we ask for your patience)


# If you have a 3D printer, you can even print a custom casing for your MAKERbuino

![image](https://raw.githubusercontent.com/AllGray/slate/master/images/116.jpg)
![image](https://raw.githubusercontent.com/AllGray/slate/master/images/117.jpg)


# Conclusion

We hope that you had a fun time assembling the MAKERbuino. 
Now, this is just the beginning. 
Make your MAKERbuino unique. 
You’ll enjoy prototyping and playing with it. 
We’d also love to see what you can do with your MAKERbuino so join the community and let us know what you did with your MAKERbuino on the [MAKERbuino Forum:](https://community.makerbuino.com)

Please, spread the word by showing your brand new MAKERbuino to your friends and colleagues. 
Also, posting a picture of your MAKERbuino on social media would be really helpful.

We would also like to hear some feedback. 
Tell us how you liked the build process, is everything working fine, how can we improve the design, do you have any questions...
Drop us a line at contact@makerbuino.com


Don't forget to follow the project at:

[MAKERbuino](www.makerbuino.com)

[Facebook](https://www.facebook.com/makerbuino)

[Twitter](https://www.twitter.com/makerbuino)

[Instagram](https://www.instagram.com/makerbuino)
