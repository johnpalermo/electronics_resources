# Electronics Resources
Resources for learning electronics and more.

- 🔗[More here](https://johnpalermo.github.io/electronics/)

## Current Projects

## My USB Scope
- Hantek 6022BE Digital
    - Standard USBXITM interface, easily inserts into USBXITM housing to make up a combination instrument.
    - Be suitable for notebook computer, product line maintenance, be used easily on business.
    - High performance, 250MS/s real-time sampling, 20MHz-80MHz bandwidth.
    - 23 measurement functions, PASS/FAIL Check, be suitable for technical application.
    - Waveform average, persistence, intensity, invert, addition, subtraction, multiplication, division, X-Y plot.

## Circuit Simulation and PCB design
- 🔗[CircuitMaker](https://circuitmaker.com/)
- 🔗[Getting Started With Circuit Maker](https://babbage.cs.qc.cuny.edu/courses/cs343/Circuit_Maker/)
- 🔗[Using CircuitMaker](http://hades.mech.northwestern.edu/index.php/Using_CircuitMaker)
- 🔗[Teach Me PCB](https://teachmepcb.com/)
  Excellent site on learning PCB deisgn.  I'm enrolled in their courses.
- 🔗[Fritzing](https://fritzing.org/)
  Make pretty 3D schematics with Arduino boards.
- 🔗[SnapEDA](https://www.snapeda.com/)
  Download footprints for components.
  
## Arduino
- 🔗[How To Wirelessly Transmit Data on Arduino](https://www.digikey.ca/en/maker/blogs/2019/how-to-wirelessly-transmit-data-on-arduino)
- 🔗[Uploading sketches Over-the-Air (OTA)](https://www.arduino.cc/en/Tutorial/ota-getting-started)
- 🔗[How to connect your Arduino to Wi-Fi](https://www.deviceplus.com/arduino/how-to-connect-your-arduino-to-wi-fi/)

## LEDs
- 🔗[All About LEDs](https://learn.adafruit.com/all-about-leds/overview)
  - What is an LED?
  - What are LEDs used for?
  - The LED datasheet
  - Forward Voltage and KVL
  - Revisiting Resistors
  - Revisiting Volts
  - Which to Adjust?
  - Adjusting Brightness
  - .... more
- 🔗[‘Resistance’ of an LED](http://lednique.com/current-voltage-relationships/resistance-of-an-led/)
- 🔗[LED Specifications: light emitting diode parameters](https://www.electronics-notes.com/articles/electronic_components/diode/light-emitting-diode-led-datasheet-specifications-parameters-characteristics.php#:~:text=Many%20LEDs%20will%20operate%20at,LED%20increases%20with%20increasing%20current.)
- 🔗[LED Resistor Calculator](https://www.thegeekpub.com/calculators/led-resistor-calculator)

## FPGAs
- 🔗 [FPGA Tutorials](https://nandland.com/)
- 🔗 [Intel® MAX® 10 FPGA Development Kit](https://www.intel.ca/content/www/ca/en/products/details/fpga/development-kits/max/10m50.html)
- 🔗 [Intel® MAX® 10 FPGA Development Kit (Mouser)](https://www.mouser.ca/ProductDetail/Intel-Altera/DK-DEV-10M50-A?qs=bKenfurwlslqr8ev6O9%2FIg%3D%3D)
- 🔗 [Intel® FPGA Development Kits](https://www.intel.com/content/www/us/en/products/details/fpga/development-kits.html)
- 🔗 [Spartan 7 Boards](https://www.xilinx.com/products/boards-and-kits/device-family/nav-spartan-7.html)

## ATMega328
- 📘[Textbook on Microcontrollers (focusing on the ATMega328)](textbooks/microcontroller_course_textbook.pdf)

## Learning Electronics
- 📘[Notes on Electronics](electronics_notes.md)
  These notes serve as a quick way to learn electronics or a refresher for hobbiests, but do not replace a full course or textbook on electronics.  A proper textbook
  on electronics is recommended, such as **Introduction To Electronics by Earl Gates** and a proper course such as [Introduction to Electronics](https://www.coursera.org/learn/electronics) is also recommended.
- 🔗[The Geek Pub](https://www.thegeekpub.com/)
  Excellent site on learning electronics. Select **LEARNING** on the top menu.

## Learning Anlog Video Electronics
- 🔗[Realtime Composite Video Decoding with PicoScope](https://codeandlife.com/2012/07/31/realtime-composite-video-decoding-with-picoscope/)
  Excellent article on learning about composite video which also contains a project you can learn from.
- 🔗[Composite video decoding: Theory and practice](https://codeandlife.com/2012/10/09/composite-video-decoding-theory-and-practice/)
  Excellent article on learning about composite video which also contains a project you can learn from.
  
## Oscilloscopes
- 🔗[Pico Oscilloscopes](https://www.picotech.com/oscilloscope/2000/picoscope-2000-overview)
- 🔗[Measure Electronic Waves: How to Use an Oscilloscope](https://www.dummies.com/article/technology/electronics/general-electronics/measure-electronic-waves-how-to-use-an-oscilloscope-180231/)
- 🔗[How to Use an Oscilloscope](https://learn.sparkfun.com/tutorials/how-to-use-an-oscilloscope/all)


## VLSI chips
- 🔗[Microscope ME580TC-PZ-2L-20MBI3](https://amscope.com/products/c-me580t-pz-2l?variant=41099228283055#)
- 🔗[Sample Image from ME580TC-PZ-2L-20MBI3 ](https://siliconpr0n.org/map/mos/8521r0/mz/#x=7061&y=4907&z=1)

### How to remove the epoxy housing on a VLSI chip

The method is linked in the article on John Grips [page](https://c128.se/posts/silicon-adventures/ ), Chips a la Antoine. Heat up the epoxy with a hot air station, crack it open with pliers. Works well on the epoxy MOS used, less well on some other brands.

### Other notes on reverse engineering VLSI chips

#### From Discord chat with Johan Grip


burnhard — 09/09/2022
@Johan Grip How so you Go about Reverse engineering ics in General? Do you have the schematic of all the ics of the c128

Johan Grip — 09/09/2022
Depends on the IC. For the MMU I'm working from the datasheet and observed behaviours. For the PLA I used a microscope to take photos of the silicon and reverse engineered that way.

burnhard — 09/09/2022
Is there some Info ob how to do this Second Method? I would really Like to learn how to do this.

Johan Grip — 09/09/2022
I did a write up on my homepage, https://c128.se/posts/silicon-adventures/ though it's not very detailed.
Second part of my talk at VCF East this year was also about silicon reversing: https://www.youtube.com/watch?v=hMMiyUGEygE
YouTube
Vintage Computer Federation
Commodore 128 Reverse Engineering – Johan Grip
Image

burnhard — 09/09/2022
Is there some literature which you could recommend?

Johan Grip — 09/09/2022
Yes, actually. It does depend on which chips one wants to reverse, in my case I'm pretty much only focusing on MOS/CSG chips so NMOS.
For that I found https://www.amazon.de/dp/0201043580/ very useful.
Introduction to Vlsi Systems
Introduction to Vlsi Systems
Image
Learning how to reverse ICs means also learning how they are made.

burnhard — 09/09/2022
Thank you will give it a try
What do you use to get rid of the epoxy housing?
Nitrit Avid?
Acid

Johan Grip — 09/09/2022
My method is linked in the article on my page, Chips a la Antoine. Heat up the epoxy with a hot air station, crack it open with pliers. Works well on the epoxy MOS used, less well on some other brands.

burnhard — 09/09/2022
Thanks I will give it a try

Johan Grip — 09/09/2022
For microscope you'd need a metallurgical with reflected light. Which one is a whole topic by itself 🙂

burnhard — 09/09/2022
Do you have a recommendation for me 😉

Johan Grip — 09/09/2022
It gets tricky straight up. Depends on budget, availability of used ones, what chips one wants to look at, etc. etc.
My first I bought for this purpose was an AmScope ME580T-PZ-2L which works well optically. I did have problems motorizing the stage but others have had more success.
This image of a 6526A was taken with that amscope: https://siliconpr0n.org/map/mos/8521r0/mz/
Today I'm using an Olympus BH2 w/ UMA illuminator and a whole mess of home brew for driving the stage.

burnhard — 09/09/2022
Thanks for the tip

burnhard — 09/11/2022
@Johan Grip hello thanks for the much required help
Do you actually have some personal documentation on the homebrew side, because I saw a decent priced scope (Olympus  BH2 w/ UMA illuminator) on ebay.

Johan Grip — 09/11/2022
Not documentation as such, but I'm happy to answer questions and help out in any way I can. The core is a small board with an ESP32 running FluidNC, https://github.com/bdring/FluidNC
GitHub
GitHub - bdring/FluidNC: The next generation of motion control firm...
The next generation of motion control firmware. Contribute to bdring/FluidNC development by creating an account on GitHub.
GitHub - bdring/FluidNC: The next generation of motion control firm...
This then controls the stepper motors that move the stage around.

burnhard — 09/11/2022
Thank you I really appreciate it

Johan Grip — 09/11/2022
Current setup looks like this. Olympus BH2 w/ UMA, mounted on a Nikon base. X/Y linear stages, Z stage, tip/tilt stages all motorized and a manual rotation stage on top. Imaging is a Sony Alpha a6000 with some adaptor optics.
Image

burnhard — 09/11/2022
wow this looks great
what kind of driverboard do you use for the stepper motors

Johan Grip — 09/11/2022
It's a custom board based on Bart Dring's sixpack board, I mostly just moved to stepper sticks and smaller connectors as I don't need high current. I just wanted a smaller board compared to the original.
Image

burnhard — 09/11/2022
Thank you




