Eric Cho & John Sullivan
EC463 ECE Senior Design
9/23/2022


For the Hardware Mini Project, I (Eric) altered the clock divider within the PWM file. Originally the clock divider value was 4. This caused the green LED light on the Pico to fade on and off at a quick rate. For my modification to the code, I aimed to slow down the speed at which the LED turned on and off by setting the clock divider value to 10. The reason why increasing this value slows down the speed in which the LED fades on and off is because a clock divider results in an clock signal with a lower frequency signal from the original clock signal. This means that as the value of the clock divider increases, the new resulting clock signal frequency will get lower. This slower clock frequency can be visualized in the videos by the LEDs light turning on and off at different rates. 

After doing that, I (John) attempted to modify the clock divider value to depend on the internal temperature sensor of the Pi Nano. This would relate the temperatures sensor values to the reate of which the LED would fade on and off. This addition was successful as the new code properly compiled and appeared to display desirable outputs. From the video it is apparent that the temperature detected by the Pi Nano’s sensor directly influenced the LED of the Pico. By elevating the temperature by a few tens of degrees with a heat gun, the LED began blinking at different frequencies. Possible improvements in the future would be to scale the readings to make the differences more noticeable for different temperature readings. 
