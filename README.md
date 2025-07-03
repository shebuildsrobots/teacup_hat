# Teacup Hat
Make a cute teacup headband with a magical self-stirring spoon! See it moving in action [here](https://www.youtube.com/shorts/R1jwUXIRJas).

<img src="https://github.com/user-attachments/assets/d3d6ca2f-fa42-4a52-b826-e625c27bf94c" width="400" alt="teacup hat">

Please note the teacup is huge and quite heavy; there are also some issues with the closure that I detail below. I recommend reworking the model to address these concerns, but if you print as-is, you should still be fairly successful. 

I used:
*  Adafruit Trinket 5V
*  Stepper motor (28BYJ-48)
*  Stepper driver (ULN2003 Driver)
*  9V battery with header snap and wire leads
*  4x 2.3mm wide servo screws
*  Micro on/off switch such as [this](https://www.amazon.com/Switch-SPDT-Micro-Breadboard-GuuYebe/dp/B0CRTPY88B?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=A3DGS5363V8GMZ&gQT=1)
*  Headband
*  Ribbon

  ## Wiring Diagram

  ![449310161-4b2175c9-1c0c-4ceb-80da-5e8f9eb8e209](https://github.com/user-attachments/assets/55017d7d-41a5-4580-9613-6e96c171df08)

  ## Arduino IDE notes
  For the board, select Adafruit Trinket (ATtiny85 @16MHz). To upload, hold and release the button on the Trinket to enter bootloader mode, then upload using programmer (Ctrl+Shift+U) or Sketch > Upload Using Programmer.

  
  ## Assembly
  Solder all the connections in the diagram, plus an on/off switch on one of your power leads. There is a tiny rectangular hole at the base of the teacup to accomodate an 11mm on/off switch; hot glue the switch in place here so that the switch is exposed to the outside of the teacup.

  Glue on the handle.

  Insert the electronics in the hollow cavity underneath the teacup. Run one ribbon through each set of rectangular holes. Screw the closure plate on as shown. **Note that the closure doesn't align very well in the current model. I could only get two of the screws in. I strongly recommend redesigning the file rather than printing as-is.**
  
<img src="https://github.com/user-attachments/assets/e856a459-a64b-431c-b44b-3a98c748413e" width="400" alt="closure">



Tie the ribbons tighly around a headband and decorate however you'd like.
