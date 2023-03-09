# cnc-gas-cutter
CNC gas cutter for low resource contexts

# Introduction

This cnc automated gas cutter was specifically designed for steel fabrication workshops in Oman as a proof of concept for my doctoral thesis, where i investigate the potential of self built low cost CNC automated machine tools for resource constrained contexts. Instead of using a machine torch, it instead automates the hand held gas cutter torch that is often found in steel fabrication shops around the world. This allows end users to directly use what they have and do not have to purchase an extra new torch. 

<Insert picture>

# Frame Design
  
The machine was designed and implemented in Oman as part of my doctoral thesis, as a first proof of concept for the design of low cost and affordable open source machine tools for resource constrained contexts. The machine automates a typical gas cutting hand torch, but can also be adapted to use a machine torch or even a plasma cutter. The key features of the design are the metal frame system that utilizes simple square profile mild steel which is easily available in Oman. The linear rails are made of a combination of roller bearings running on bolts as axles, using the frame as part of the linear rail system.

# Electronics

The electronics are comprised of conventional 3d printer electronics, again with the aim of low cost and availability. The controller board is an arduino mega 2560 board with a ramps 1.4 shield on top. It haS 5 A4988 stepper motor drivers controlling 5 nema17 stepper motors. A reprap full discount 12864 LCD with full SD card support built into a jog pendant that has a joystick and physical buttons for homing, pausing, oxygen lance lever homing and stop. There are currently no solenopid valves built in to control the switching of gas, however this is planned for further iterations.

# Process

Gas cutting is one of the oldest cutting processes in industry and is ubiquitious is all kinds of metal fabrication workshops around the world. Gas cutting is different from plasma cutting in terms of the medium of cutting where a acetylene or propane flame, instead of a plasma is used to cut the metal. The process can cut only mild steel and not aluminium or stainless steel and is most suited for cutting thick mild steel ranging from 3-300mm. When cutting material thinner than 10 mm, plasma cutting is preferred. 