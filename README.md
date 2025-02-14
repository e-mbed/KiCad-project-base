# KiCad Base Project

This base project is designed to save you time and effort when starting a new hardware project with KiCad. Systematization is crucial for efficient hardware development and minimizing errors. This project provides a solid foundation to build upon.

## Project Structure

This project includes a hierarchical schematic with two pages:

* **Root:** The top-level sheet of the schematic.  Initially, it only contains a reference to the "Miscellaneous" sheet.
* **Miscellaneous:** This sheet contains elements that are not directly part of the core electronic circuit, such as fiducials, mounting holes, logos, and the PCB project code.

While KiCad doesn't *require* hierarchical schematics, their use is highly recommended, even for simple projects, for better organization and scalability.

The project also includes a pre-configured 4-layer PCB with basic manufacturing and design rules already set up. This allows you to focus on your design rather than initial configuration. A detailed explanation of the design rules used in this project can be found in my blog post:

[https://e-mbed.com/kicaddesignrules/]

## Instructions

1. **Download and Rename:** Download all files to the same directory. Rename the files currently named "EMB-XXXXX PrjName" to your preferred project naming convention. "EMB-XXXXX" represents an internal project code, and "PrjName" is the human-readable project name. While the suggested format is recommended, it's ultimately your choice. *It is essential that the filenames remain identical for all project files you just have renamed.*

2. **Open in KiCad:** Open the KiCad project file (`.kicad_pro`). The project uses the following template files:
    * Schematic Title Block: `e-mbed sch template.kicad_wks`
    * PCB Title Block: `e-mbed pcb template.kicad_wks`

3. **Customize Title Blocks:** To customize the title blocks, open the respective template files (`.kicad_wks`) and modify them as needed (e.g., change the logo 😝).

4. **Text Variables:** The schematic and PCB title blocks extensively use project-defined text variables. These global variables are shared between the schematic and PCB and can be accessed through the "Schematic Setup" (Schematic Editor) and the "Board Setup" (PCB Editor).

5. **Schematic Title Block Specifics:**
    * **Date:** Use the "Issue Date" field within the schematic "Page Settings" menu to automatically insert the current date.
    * **Sheet Number, Size, and Function:** These are automatically populated using system parameters and do not require manual input.

## Conclusion

I hope this base project proves helpful for your KiCad projects. Please feel free to contribute or suggest improvements.

KiCad Version: 8.0.8

Adw!

Xosu Ph.
