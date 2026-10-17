# Scout-Drone

This is a scout drone from rainbow six siege.

It uses a usb webcam, 2 servo's and a rpi3A+ .

<img src="blob:chrome-untrusted://media-app/5630590d-6904-46b3-ba16-cf829bde0f51" alt="1000034443.jpg"/><img width="4000" height="1800" alt="image" src="https://github.com/user-attachments/assets/9aee908d-24d3-4d11-be63-13eab6aa990a" />

## BOM
- usb webcam
- raspberry pi3A+
- 2x360°servo motors
- a power bank with usb a port
- pla or petg filament
- tpu 95a filament
- a breadboard
- some jumper wires

## Assembly

The first thing you are going to want to do is print the wheels in the tpu and all the other parts in either PETG or PLA.

Then after that you can use some hot glue to attach the usb webcam to the inside of the shell (this way you can use any cheap webcam you can find).

After that you can put the servo's in the wheel hubs and then push them onto the wheels.

After that you can wire everything up using the breadboard and the pi using this wiring schematic:

- 32 to Left servo signal
- 33 to Right servo signal
- 6	to both Servo GND
- 2 to both servo plus
- usb a from webcam to usb from rpi

then all you have to do is attach the power bank to your pi and upload the code to it, you can do this using ssh and then running the command cd ~/siege-drone in the ssh terminal this will automatically give you an adress that you can put in your browser (no wasd support yet).

Finally you slide the wheelhubs in on both sides untill the wheels touch the shell and it should drive.

(no it doesn't jump)



