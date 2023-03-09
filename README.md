# cnc-gas-cutter
CNC gas cutter for low resource contexts

<Insert picture from CAD>

# Introduction

This cnc automated gas cutter was specifically designed for steel fabrication workshops in Oman as a proof of concept for my doctoral thesis, where i investigate the potential of self built low cost CNC automated machine tools for resource constrained contexts. Instead of using a machine torch, it instead automates the hand held gas cutter torch that is often found in steel fabrication shops around the world. This allows end users to directly use what they have and do not have to purchase an extra new torch. 

# Mechanical Design
  
The frame employs a metal frame system made from mild steel square hollow sections, which is easily available in Oman. The frame can be either welded together or bolted together. The linear rails are made of a combination of roller bearings running on bolts as axles, using the frame as part of the linear rail system. The drive system uses a belt and pulley system due to its ease of assembly and affordability.

# Electronics

The electronics are comprised of conventional 3d printer electronics, again with the aim of low cost and availability. The controller board is an arduino mega 2560 board with a ramps 1.4 shield on top. It haS 5 A4988 stepper motor drivers controlling 5 nema17 stepper motors. A reprap full discount 12864 LCD with full SD card support built into a jog pendant that has a joystick and physical buttons for homing, pausing, oxygen lance lever homing and stop. There are currently no solenopid valves built in to control the switching of gas, however this is planned for further iterations.

# Process

Gas cutting is one of the oldest cutting processes in industry and is ubiquitious in metal fabrication workshops around the world. Gas cutting is different from plasma cutting in terms of the medium of cutting where a acetylene or propane flame, instead of a plasma is used to cut the metal. The process can cut only mild steel and not aluminium or stainless steel and is most suited for cutting thick mild steel ranging from 3-300mm. When cutting material thinner than 10 mm, plasma cutting is preferred. 

![Gas cutting](C:\Users\Mohammed Omer\cnc_gas_cutter_repo\cnc-gas-cutter\Images\Flame_distribution_while_preheat.png)

The machine is semi automated i.e. the user has to open the necessary valves and set the flame and then the cutting program can be started. For gas cutting, one needs the cutting torch, acetylene and oxygen. Acetylene gives the hottest flame and is the most commonly used gas used for cutting. <Find link showing how to setup the perfect flame and then summarize>

