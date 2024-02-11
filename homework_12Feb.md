## Carousel:
#### By Ehtisham, Aya, and Evelyn

We started workign with lazy susan and made a fixed base and on top a rotating base for the carousel. Then, we tried to turn the rotating base with a 12v servo motor. Following video and image shows the prototype: 

https://github.com/ehtishamoas/MachineLab/assets/66066342/4076e57d-0466-430b-b5b4-ba015e3a3d45 

![lazy susan](https://github.com/ehtishamoas/MachineLab/assets/66066342/92cd946d-1f92-4be2-ad97-cd3864fcb599) 

The mechanism to move the platform with motor directly underneath would not work as we have to supple power to upper part of the carousel from the central cylinder-shaped part. So, we plan to use the
pulley system to rotate the platform. And in the center, we will use a slip ring to power up the arduino in the upper part. Slip ring with prevent wires from getting twisted from continous rotation of 
the carousel.

Speaking of continous rotation, one problem we had with the 12v servo was that we couldn't make to rotate continously. So, we plan to experiment with stepper motor for the future!

The following sketch drawn by Professor Shiloh is what we will be trying to implement in the next week:
![carousel with roating wires](https://github.com/ehtishamoas/MachineLab/assets/66066342/20944e85-060d-491b-bee7-b6138b84902b)
