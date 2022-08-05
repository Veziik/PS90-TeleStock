# Disclaimer
It is the user's responsibility to know their local laws before attempting to use these files. Nobody is responsible for violaion of local laws other than the user of these files.

# License Requirements
All the files in this repository (Veziik/PS90-TeleStock) are licensed under the GNU General Public License v3.0. As per the license, any modification or commercial use of this code needs to reference the git repository, in order to do so, simply include a physical copy of the README with any PS90s sold with this stock attached. For the original files and updates to this design, visit [https://github.com/Veziik/PS90-TeleStock](https://github.com/Veziik/PS90-TeleStock). 

# Printing Instructions
From now on, I'm going to assume that you are going to be printing in PLA+ or equivalent and already have the settings dialed in on your filament. In my case, I was using [Polymaker 3D Printer PLA+ Filament 1.75mm](https://smile.amazon.com/dp/B097SVHDR5/ref=twister_B09MBYF326?_encoding=UTF8&th=1) with a nozzle temperatuire of 210°C and a bed temperature of 60°C. Assume that you don't need supports until otherwise specified.


1. Go into the STL files and select either the low profile version or the standard version

2. Print the following files on your printer of choice at 70% infill (I used gyroid infill):
    - LockingAssemblyMainTelescopingBody.stl (print this upside down, with the button hole facing up, with supports)
    - telescopingArrayTelescopingPad.stl (print this sideways, the hole for the crosspin facing up, with supports)

3. Print the following files on your printer of choice at 100% infill:
    - telescopingArrayPadCrosspin.stl (Orient this so that the beveled edge is facing up)
    - LockingAssemblyLockingButton.stl (Print this sideways, with the channel for the locking pin oriented vertically).
    - LockingAssemblyLockingPin.stl
        
4. Print the following files on your printer of choice at 100% infill, orient them so that their flatest side is touching the build plate.
    - telescopingArrayLeftTelescopingBar.stl
    - telescopingArrayRightTelescopingBar.stl

# Assembly Instructions
## Required Parts:
1. A 3mm spring of at least 15mm in length. Degree of stiffness is up to you.
2. The parts printed in the Printing Instructions section.

## Step order
### IF YOU ARE BUILDING THIS AT HOME FOR YOUR OWN PS90, FOLLOW THESE INSTRUCTIONS EXACTLY TO REMAIN COMPLIANT WITHIN YOUR STATE THROUGHOUT THE BUILD PROCESS
1. Do not disassemble your PS90 yet.
2. Insert the spring into the main telescoping body, aka the body which houses the button and locking pin.
3. Insert the button, with the locking pin cutout facing towards the dovetail of the main telescoping body.
4. While maintaining some pressure on the button to align it properly, insert the locking pin, with the bevel of the locking pin facing down and towards the dovetail of the main telescoping body. Push the button all the way up once the locking pin is centered, the button should be able to be gently pressed until nearly flush.
5. Push the button up all the way into the telescoping body and insert both of the telescoping arms in from the dovetail side of the telescoping body. This is where we check to make sure that both of the arms glide comfortably, but snug to the telescoping body, in addition to locking and unlocking without the application anything mroe than a gentle push. Both arms should have their cutouts facing up, and the holes for the crosspin with the pad should away from the dovetail side.
6. Extend the to any locking point, slide the telescoping pad so that the flat of the main body and the hollowed out section of the pad touch when fully collapsed.
7. Insert the crosspin. It will take a little bit more force than the rest of the build to proerly insert, but not by much. Feel free to superglue/Loctite/Rockset this part of the build, but the crosspin will remain in postion during normal operation.
8. Function test, make sure that you can extend the butt all the way out and that the button allows you to disengage the locking mechanism. Make sure its all smooth and to your liking.
9. OK, NOW you can disassemble your PS90, all the way to the point where you remove your butttstock. If you dont know how to disassebmle your PS90, read the manual for your PS90 to learn its disassembly.
10. Extend the telescoping pad all the way from the telecoping body. Slide the dovetail of the telescoping body into the place where the old buttpad was. There may need to be some sanding done to get a proper fit, but that way the butt isnt sloppy or too weak to handle mismanagement.
11. Function test again: Repeat step 8 but with the butt attached.
12. Done! Feel free to rubberize the pad itself for better interface with the body.

# Use Guidelines
This is a telescoping stock made out of plastic, it is not made for buttstroking doors, tables, neighbors, or yourself. It will otherwise readily handle the recoil of the 5.7x28mm catrtridge when fully collapsed or at any locking point. I strongly recommend printing an extra set of arms in the event that one breaks.

### When Repairing, ALWAYS keep at least one telesoping arm inserted into the main telescoping body, regardless of damage taken. NEVER leave the main telescoping body without telescoping bars. When replacing both bars, simply swap the bars out one at a time, and always keep the pad connected to the telescoping bars whenever possible. 
