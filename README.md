<p align="center">
  <img src="https://img.itch.zone/aW1nLzQ1ODM1NjcucG5n/original/wky0ct.png" alt="Anarch Switch Icon" width="256"/>
</p>


🎮 Anarch for Nintendo Switch


This is a homebrew port of Anarch—the ultimate minimalist, 90s-style shooter—brought over to the Nintendo Switch.

Check out the [Original Anarch Project](https://drummyfish.gitlab.io/anarch/) by Drummyfish.


I just wanted to port something awesome to the Switch. All the true genius and hard work belongs to the original creator; I just wrestled with the Makefile nonsense and mapped out some controller bindings to get it running how I wanted.

---

💾 Installation & Setup
For Users

    Download the latest anarch.nro.

    Drop it into the switch/ folder on your SD card.

    Launch it via the Homebrew Menu (usually accessed through the Album app).
    

## 🕹️ Controls

* **D-Pad / Left Stick:** Move Forward/Backward, Turn Left/Right
* **L / R (Shoulder buttons):** Strafe Left / Right
* **B & ZR:** Fire Weapon
* **Y:** Jump
* **X & A:** Cycle Weapons
* **Left Stick Click (L3):** Free Look (Right-click mode)

---

Emulation Tip: If you are testing this build inside an emulator (like Ryujinx), make sure your Graphics Backend is strictly set to OpenGL.
(Ask me how I know... I definitely didn't waste hours debugging a Vulkan black screen just to feel incredibly silly afterward!)

---

For Developers (Compiling from Source)
If you want to compile a fresh binary, make sure you have devkitPro set up alongside the Switch SDL libraries (sudo pacman -S switch-portlibs switch-sdl2 switch-sdl2_image).
```bash
cd Anarch---Switch-homebrew
make
