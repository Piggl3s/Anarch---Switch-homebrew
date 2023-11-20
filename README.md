
# Anarch for Nintendo Switch

Port of Anarch for Nintendo Switch homebrew.
Using Devkitpro,

Full details of anarch  
https://drummyfish.gitlab.io/anarch/


I just wanted to port something cool.   
All the hard work was done, I just amended some controls and makefile nonsense.





## Installation

Download the Anarch .nro to the switch folder on SD card and it should show up under homebrew apps/games (usually in the album/photo section)

If you want to compile a fresh version you will need DevkitPro installed and the Switch SDL libraries.

```bash
  cd into the anarch folder
  make
```


Also running this under emulation be sure to set Graphics rendering to OpenGl.
(I may have tried debugging a vulkan rendered version for hours... Ahhh to feel so very stupid)


## Controls

Dpad    Forward backwards, Turn Left Turn right  
B       Fire  
Y       Jump  
X & A   cycle weapons  
L & R   Shoulder buttons Strafe left & right  

## Roadmap

- Analog stick support

- Sound fixes 

