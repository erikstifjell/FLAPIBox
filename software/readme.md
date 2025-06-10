# Software
The FLAPIBox uses Bela's IDE for uploading software patches. Although the Bela Mini works with several programming languages, Pure Data has been the prefered language for developing the FLAPIBox. This repository holds diverse modules developed in connection with composing musical pieces. These modules can be joined together to form fully functional patches for the FLAPIBox. The patches for these musical pieces can be found at the repository of the specific pieces, which is linked on this page.

### OLED-screen
The OLED screen is installed by following Bela's guide:
[Using an OLED screen](https://learn.bela.io/using-bela/bela-techniques/using-an-oled-screen/)

For FLAPIBox startup logo, [main.cpp](https://github.com/erikstifjell/FLAPIBox/blob/main/software/OLEDscreen/main.cpp) has to be replaced after installing the OLED-screen
### Infrastructure
[flapiinfra.pd](https://github.com/erikstifjell/FLAPIBox/blob/main/software/flapiinfra.pd) needs to be uploaded to every project and placed as an object in the patch.

### Sound and Buttoncheck
[Sound and Buttoncheck](https://github.com/erikstifjell/FLAPIBox/blob/main/software/SoundAndButtonCheck/_main.pd) let you check that both inputs and outputs work. Input gain on P1 and P2. M1 and M2 should decrease/increase between numbers 1 to 4 and show in display.

### Tryouts 06/2025

### Objects
