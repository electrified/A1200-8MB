# 8MB Fast Ram for A1200

This is a 8MB FastRam board for A1200 designed in 2019 by @edu_arana, coworked with Stephen Leary based on the TF328 project.

# License

This project, as the same as the original, are released under the GNU GPLv2. If you build a modified version of the board you must supply the end user with all the sources (this can be a web link). Also you may create
or base commercial PCBs from the work in this repository but you must make the sources for all derivative work available. The authors on this board must remain and stay legible on the current / new board. Removing the
copyright notices its a breach of the GPL.

BTW, If you make a new board version, we will be glad if you send at least one pcb to each us. This is not a must :p

# Images

<img src='https://github.com/arananet/A1200-8MB/blob/master/images/top.png?raw=true' width=700/>
<img src='https://github.com/arananet/A1200-8MB/blob/master/images/bottom.png?raw=true' width=700/>

# PCB info (for pcb fabricator)

Dimensions :	59 x 100 mm  
Layers :	4 layers  
Layer order: GTL, G1, G2, GBL  
Finished Copper : 1 oz Cu  
PCB Kinds:	2 (because the breakable area)  
Track/Spacing:	6/6mil  
Blind/Buried Via: No  
Material :	Normal FR-4 Board TG150  
Thickness :	1.6 mm  
Solder Mask :	Whatever color you want :)  
Silkscreen :	Whatever color you want :)  
Surface Finish :Immersion gold (recommended)  
Hole Size :	0.4  

# Firmware:

S. Leary a.k.a terriblefire has made an small modification to the current TF322 to disable the ide option, as the A1200 already have one. The firmware jed files are available on the firmware directory.

Xilinx ISE, 14.7
JTAG Adaptor

# Gerbers:

Premade gerbers of the board are available on this repository too.

# Bill of matherials

Note that the only ram chips used and compatible are the K4E151612C, this ram chips are 3v3 only. All the current design is adapter to 3V3. A new LDO regulator is used to get 3V3 vots.


| Part          | Value                   | Package                        |
| ------------- | ----------------------- | ------------------------------ |   
| C1            | 1uF                     | 1206                           |
| C2            | 10uF                    | 1206                           | 
| C3            | 10uF                    | 1206                           | 
| C5            | 1uF                     | 1206                           |
| CN1           | A1200-EXPANSION_SLOT    | CON_150                        | 
| IC1           | K4E151612C              | TSOP44(50)-II                  | 
| IC2           | K4E151612C              | TSOP44(50)-II                  | 
| IC3           | K4E151612C              | TSOP44(50)-II                  | 
| IC4           | K4E151612C              | TSOP44(50)-II                  | 
| IC6           | LD39150DT33-R           | STD5N52U                       | 
| ICC1          | 10uF                    | 1206                           | 
| ICC2          | 10uF                    | 1206                           | 
| ICC3          | 10uF                    | 1206                           | 
| ICC4          | 10uF                    | 1206                           | 
| MUXCPLD       | XC9536_44VQ             | SQFP-S-10X10-44                | 
| RAMCPLD       | XC9572XL-VQ64           | VQ64                           |

# Wiki

There is a TF328 wiki that can be use to resolve any doubt about the compatibility of the current firmware.

https://github.com/terriblefire/tf328/wiki

# Contribution / support

If you wanna buy me a beer or a Mercedes SLR,  please contact me at info at arananet.net or support @terriblefire at youtube :)
