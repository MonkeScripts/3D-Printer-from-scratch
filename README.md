# 3D-Printer-from-scratch

Printer consists OF A 300mm x 300 mm build plate with a direct drive e3D Hemera Extruder and a Duet 2 board to control stepper movements, heat bed, extruder temperatures and lastly wifi connectivity.

First, I designed a simple cartesian structure using Fusin360. I adopted the V-rails from open rails and took inspiration from models from Creality and Zidex Printers

After the design is refined sufficiently, I proceeded to source for parts, mainly from China as the market offers more diversity when looing for parts and also most importantly, the goods are cheaper and more affordable.

My design included multiple 3D printed parts and I was lucky enough to find affordable 3D printing services that would print my parts in stronger black nylon.
I wanted to get the best extruder out there and landed myself with Hemera from e3D. I stuck with a direct drive system as the printer I designed is able to support the added weight and also I wanted to avoid any common filament delivery problems associated with a bowden system.

I chose the Duet 2 Board as the stepper motor drivers are much more reliable. The board also enabled me to use a touch screen interface to control my prints via the PanelDue.

The overall assembly was fun yet challenging, I faced numerous connectivity issues as I was relatively new to electronics. I had to resolder and recrimp my board and connectors numerous times. Some parts that I bought are also inconsistent and I had to improvise and reroute numerous lines for things to work. The worse part of doing the circuitry was the manufacturing problems of the Duet 2 Board. There were many traces that were not connected and I had to diagnosed the problems and route the traces physically using jumpers.

Finally, the code was relatively easy. I updated the json config file via an online RepRap Firmware tool. Using cura, I was able to add my own configurations into its GUI and the software does all the slicing and calculations for me.

Overall, this was an interesting project and I am glad that I was able to stick to the project and finish it in the end during a tough training regime in National Service 

<br></br>
![alt text](https://user-images.githubusercontent.com/104839312/198099008-861fa0aa-379c-44e2-8c40-238cd5e07de5.jpeg)
