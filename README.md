# ModuCard Base Module

This repository provides a template design for creating modules in the ModuCard system. Each module is designed to seamlessly interface with the [ModuCard backplane](https://github.com/KoNarRobotics/ModuCard-backplane), enabling a modular and expandable robotics platform.
![obraz](https://github.com/user-attachments/assets/0c2b05e0-30f5-411c-bce9-ebabc41eedb3)


## Used tools:
<img align="center" height="64" src="img/logos/KiCad.png">

## Features:

### Power section
- **Input voltage:** 12V from the backplane.  
- **Output voltage:** 3.3V @ 0.5A.

### ST-LINK
- Built-in **ST-LINK** connected to the backplane via USB interface.  
- Enables programming and debugging of the onboard MCU.

### CAN interface
- Two independent CAN buses: **CAN1** and **CAN2**.  
- Both connect with the backplane to facilitate communication between the onboard MCU and other modules in the system.


# How to Create a new module from this template
1. **Create a new repository**
2. **Copy files from this repository** to your new repository.  
3. **Rename the files:**
   - `base-module.kicad_pcb` → `<your-board-name>.kicad_pcb`
   - `base-module.kicad_sch` → `<your-board-name>.kicad_sch`
   - `base-module.kicad_pro` → `<your-board-name>.kicad_pro`
4. **Open the project** in KiCad.  
5. **Update page settings** in the schematic and PCB:
   - Change the **Title** to `ModuCard <your project name>`.  
   - Edit **Comment 2** to include your name in the `<author>` field.
6. Enjoy implementing your project!
