# Mug-O-Matic & the TINY CNC Collection
**What is this?**
The Mug-O-Matic is a tiny CNC robot capable of customizing coffee mugs! 

It is one possible configuration from a collection of modules designed to be low cost and have lots of replay value through customization. This robot offers kids an opportunity to learn Arduino, the most common language for physical computing. No soldering or bread-boarding required, controls are all plug and play. 

All 60+ unique 3D printed components are designed for replication, modularity, and to provide maximum performance given their low cost. To that end parts do not require build supports or post processing, and assemblies can accommodate printing variance. 

The intent of the project is to produce a unique and accessible educational tool. One that encourages children to engage in tinkering and making things because those activities are powerful ways to learn and inspire people to pursue STEM careers. 

**Design Liscense Intent:**

-The assembled Mug-O-Matic toy robot will be for sale on EngineerDog.com and I do not want to create competetion over sales of my own body of work. You may use the files to build a Mug-O-Matic for yourself, but you may not sell them.

-However. The software, the PCB design, and the 3d models of subassembly modules & components (linear actuator, pivot joint, brackets, etc) are free for you to use however you wish! Source files ahev been provided!  

HW License for Individual Mechanical Modules = CC BY-SA 4.0.
https://creativecommons.org/licenses/by-sa/4.0/
        
HW Liscense for Assembled Toys (Mug-O-Matic, Post-It-Plotter, Gantry-Claw, etc) - CC BY-NC-SA 4.0- https://creativecommons.org/licenses/by-nc-sa/4.0/
        
SW Liscense for all code = GPL 3.0 
https://www.gnu.org/licenses/gpl-3.0.en.html

        


**NOTES ON GITHUB PROGRAM DOCUMENTS.**

-Mug-O_Matic & Post-it-Plotter use the same code, with the only difference being a section of constants defining the drawing area commented out at the beginning. 

Program List Summary.

    1. Joystick Manual Control- Control robot using single or dual joysticks.
    
    2. Algorythms & Calibration- draw shapes to verify properfunctionality.
    
    3. G-code reader- Read & plot g-code. (Generated via slicer/repetierhost, send using processing)
    
    4. (WIP) Dot Matrix- read & plot dotted drawing from huge array of 0's & 1's. 
    
    5. (WIP) Bluetooth Smartphone Control- Direct control of motors via android phone app over bluetooth
    
