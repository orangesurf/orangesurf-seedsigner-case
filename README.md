# OrangeSurf SeedSigner Case
Case for the seed signer DIY bitcoin hardware wallet by OrangeSurf (https://orange.surf)

## Donations 
Donations are accepted in bitcoin: bc1qf3hv4em9mclmguqvwug8wl45yp7vk3ssv5wuxr

# Files & Documentation 
- [stl files](/stl)
- [step files](/step)
- [Version information](/CHANGES.md)
- [Licence information](/LICENCE.md)

# Printer Settings
Parts are confirmed to assemble readily when printed on Prusa MK3S with 0.4mm nozzle at the following settings
- Print all parts with no supports anywhere
- Print all buttons upside down (on flat face) at lowest layer height possible. 0.05mm confirmed to work
- Print cover plate upside down (on flat face). 0.10mm confirmed to work
- Print outer case upright (on flat face). 0.10mm confirmed to work. 

# Camera
The camera used was the ZeroCam.

![camera](/images/ssc-camera.JPG)

If using an alternate camera the dimension limits for fits are
- Lens housing base: Width and depth <9mm, height 3.2mm (with lower height the camera will not be fully constrained)
- Lens housing diameter: Less than 7mm
- Max ribbon width: Less than 12mm

![camera-drawing](/drawings/ZeroCam-Measurements.png)

PDF of A4 scaled [drawing](/drawings/ZeroCam-Measurements.pdf)

ZeroCam can be purchased from
- https://thepihut.com/collections/zerocam/products/zerocam-camera-for-raspberry-pi-zero
- https://shop.pimoroni.com/products/raspberry-pi-zero-camera-module?variant=37751082058


# PCB Separation Distance
The case is designed for a 9mm pcb face-to-face distance (from the underside of the waveshare pcb to the top face of the 
raspberry pi pcb). This must be adjusted if using different height header pins.

![gpio-pins](/images/ssc-gpio-pins.JPG)


https://github.com/orangesurf/orangesurf-seedsigner-case/
