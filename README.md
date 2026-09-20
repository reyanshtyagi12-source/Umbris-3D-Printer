# Umbris-3D-Printer
A DIY Flying Gantry 3D Printer designed to use entirely off the shelf parts, only excluding the print head files.
<img width="1642" height="1250" alt="image" src="https://github.com/user-attachments/assets/9ce759e3-f4c5-450d-adbd-4d1e31c7ac61" />
https://cad.onshape.com/documents/897164f9d3a291bc840813b3/w/3b4bd3ae2d80c74f6fa1560f/e/0a870a7b4adbb20e8cace31b?renderMode=0&uiState=6ab0283816c96ce59e7e7040

## Key Features
- Uses H shaped gantry to effectively support x axis
- Keeps bed stationary, helping make it more accurate|
- Uses Apogee Print Head design
- Large 300x300 build plate
- Easy to add custom enclosure

## How it actually works
It uses stepper motors to move the entire gantry up and down with further motors using pulleys to pull the carriages backwards and forwards. This setup ends in a final stepper motor moving the printhead left to right. After much deliberation, the Apogee Print Head was chosen because it is light and effective. While I originally looked into voron designs like the stealthburner, they weren't easily compatible with V rail extrusion, the main building block of my design.

## Credits
I would not be able to do this without the amazing community of diy 3d printers who helped me understand how I could get my project to work. I especially owe my thanks to LDO motors who designed the Apogee Toolhead, and adms (https://www.printables.com/@adms), who adapted this design to create the Apogee FAT. It's an amazing design that served as the backbone of my project.
