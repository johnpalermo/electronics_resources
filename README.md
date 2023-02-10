# Electronics Resources
Resources for learning electronics and more.

- 🔗[More here](https://johnpalermo.github.io/electronics/)

## Current Projects
  - Nothing Yet
  
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

## Learning Aanlog Video Electronics
- 🔗[Realtime Composite Video Decoding with PicoScope](https://codeandlife.com/2012/07/31/realtime-composite-video-decoding-with-picoscope/)
  Excellent article on learning about composite video which also contains a project you can learn from.
- 🔗[Composite video decoding: Theory and practice](https://codeandlife.com/2012/10/09/composite-video-decoding-theory-and-practice/)
  Excellent article on learning about composite video which also contains a project you can learn from.

### From Discord

JohnP — Today at 2:39 PM
Not sure if this question has been asked before.  I'm trying to learn how to generate a "simple" composite video signal and how to display it on a NTSC CRT TV screen.  Has anyone played around with this sort of stuff?
And what hardware would I need, such as a signal generator?
I was referred to this book https://www.amazon.com/dp/0750683953?_gl=1*o3xbu5*_ga*OTE0OTM3NDQ5LjE2NjA5MzAyODY.*_ga_S812YQPLT2*MTY2MzE3NzMzMC4zLjEuMTY2MzE4MDkwMS4wLjAuMA..
Video Demystified: A Handbook for the Digital Engineer, 5th Edition
Video Demystified: A Handbook for the Digital Engineer, 5th Edition
Image

marcy — Today at 2:41 PM
i have been playing with this stuff !
mostly in my head still

JohnP — Today at 2:42 PM
oh sweeet

marcy — Today at 2:42 PM
but slowly getting closer to
putting it in a computer

JohnP — Today at 2:42 PM
how are you figuring out?  do you have a book or a good website?

marcy — Today at 2:44 PM
the most basic idea is that you have two counters (horizontal position and vertical ) some sort of memory that holds the screen data, another bit of memory that holds the character data (if you’re doing characters), and a shift register

marcy — Today at 2:44 PM
looking through a lotta older schematics
especially like
apple ii
commodore pet

JohnP — Today at 2:44 PM
ah cool

marcy — Today at 2:45 PM
before they started using custom parts
and also look into don lancaster’s tv typewriter

JohnP — Today at 2:45 PM
where can I find the schematic for the apple ii?

marcy — Today at 2:45 PM
and other early video circuits

JohnP — Today at 2:46 PM
I guess on archive.org, right?

marcy — Today at 2:46 PM
i actually couldn’t ever find one but i did find a book that describes the circuit :P
yea probably
i’m not very organized sorry
it’s all a lotta timing

JohnP — Today at 2:46 PM
no worries.  oh, would love that book. do you know the name of it?

marcy — Today at 2:47 PM
so long as you’ve got the horizontal and vertical sync you can do whatever during the video time
it’s all analog

JohnP — Today at 2:47 PM
yah, that's what i'm looking for ... analog

marcy — Today at 2:47 PM
https://mirrors.apple2.org.za/Apple%20II%20Documentation%20Project/Books/W.%20Gayler%20-%20The%20Apple%20II%20Circuit%20Description.pdf
i think this is it
also check out the tv typewriter cookbook

JohnP — Today at 2:48 PM
nice.  I just happen to have an apple iic.  i'm guessing the circuitry is similar.

marcy — Today at 2:49 PM
i’m not sure

JohnP — Today at 2:49 PM
👍

marcy — Today at 2:49 PM
i think they had consolidated a lot more by the later apple iis 
oh also have a look at the zx80 circuit
and the zx spectrum ula
i’m at that point where i get all the ideas but bad at the logic part
all the nands and flip flops etc
oh also uhh
https://www.pong-story.com/leisure.htm
wrong page
https://www.pong-story.com/mags.htm

JohnP — Today at 2:53 PM
are you gonna make it monochrome?  or are you daring enough to do color?

marcy — Today at 2:53 PM
swtpc also did a tv terminal at one point might want to look at that
i think i’d like to do colour
but idk

JohnP — Today at 2:53 PM
nice

marcy — Today at 2:54 PM
like a 2bpp thing
think vic 20 ish
and then a register to set the 4 colours
also have a look at the harlequin spectrum
ad725 chip
could be useful

JohnP — Today at 2:55 PM
cool. thanks

marcy — Today at 2:55 PM
no problemo

JohnP — Today at 2:58 PM
i love those old analog screens.  my eyes not so much though.
  
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

## USB
- 🔗 [Routing Requirements for a USB 2.0 Impedance Interface on a 2-Layer PCB](https://resources.altium.com/p/routing-requirements-usb-20-2-layer-pcb)
      > Bil Herd — Yesterday at 8:04 PM
      > anybody spot anything wrong is this diagram from the atium Website:
      > ![Routing topology for full-speed and high-speed USB 2.0 routing.](https://resources.altium.com/sites/default/files/styles/max_width_1300/public/inline-images/usb-routing-topology_0.webp?itok=Yq89Ds5N)
      > So the issue with the drawing is they have the Host and Peripheral backwards, or at least the 5.1K  For the peripheral, or upward facing port,  the 5.1K should be a pulldown, not a pull-up.


