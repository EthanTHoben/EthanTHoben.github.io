---
title: "High Power Laser Turret"
excerpt: "Designed, built, and tested a 115W 450nm Laser array turret platform with automated tracking and engagement using computer vision and automatic focal length adjustment<br/><img src='/images/Laser resized.jpg'>"
collection: portfolio
---

The high power laser (HPL) was the first major project I undertook as a hobby, and it required me to learn skills such as power supply design, optics, 3D modeling, mechatronics, and above all else, saftey.

I undertook this project after my first summer intership enabled me to aquire more exotic components (AKA I had disposable income for the first time). I had been a big fan of creators such as [Styropyro](https://www.youtube.com/@styropyro), and once I had the means I set to work searching on ebay for listings for the same or similar high power laser arrays as he used. Eventually, I found a international vendor and was able to negotiate a discount, on account of me being a student, and the promise that I would purchase more laser arrays, which I did. 

Once I got the laser arrays, my first problem was reverse engineering the wiring diagram, as the array did not come with an adequate schematic. I was able to use a multimeter on it's continuity setting to get the schematic, and I was able to move onto my next problem: power.

You see, lasers, while thought of by most to be some futuristic technology, are in fact, rather simple. In this case specifically, since the laser was 450nm (blue) laser diode, it behaved almost exactly as a normal LED (Light Emitting Diode) would. This, of course, meant that the laser was a current mode device, and needed a power source with precise current control, as a small variation in the voltage supply would produce drastic changes in output power, and potentailly destroy the laser diode. The following image will help me explain this:
![Diode IV Curve](./images/diode-iv-curve.jpg "Diode IV Curve")


