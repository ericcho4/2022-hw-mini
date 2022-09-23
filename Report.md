Eric Cho & John Sullivan
EC463 ECE Senior Design
9/23/2022


For the Hardware Mini Project, I (Eric) altered the clock divider within the PWM file. Originally the clock divider value was 4. This caused the green LED light on the Pico to fade on and off at a quick rate. For our modification to the code, we aimed to slow down the speed at which the LED turned on and off, and set it to 10. 


After doing that, I (John) attempted to modify the clock divider value to depend on the internal temperature sensor of the Pi Nano. This seems to have worked? It compiles and appears to do something. Probably would have gone better if we’d scaled the readings to make the differences more noticeable though. Tried elevating temp by a few tens of degrees with a heat gun, but that’s a bit of a pain.