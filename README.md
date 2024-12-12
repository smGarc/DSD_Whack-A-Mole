# CPE 487 Digital System Design Final Project: Whack-a-Mole
## Expected Behavior
<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.thisiswhyimbroke.com%2Fimages%2Fwhac-a-mole-arcade-game-640x532.jpg" width="300">
The goal of this project is to mimic the classic arcade game "Whac-a-Mole". Different holes in the grass light up in yellow when a mole pops out of the hole. The holes are arranged in a grid that correspond to a 4x4 Keypad. The player should be able to hit the button on the keypad that corresponds to the lit up hole to earn points. That hole then deactivates and another hole activates. If the hole goes a duration of time without getting "hit", it deactivates and the game ends. The duration of time that a hole stays lit gets shorter and shorter the longer the player plays the game.

## Necessary Hardware
- Nexys A7-100T FPGA Board
- Computer with Vivado installed
- Micro-USB cable to power Nexys A7-100T FPGA Board and connect it to computer
- VGA Cable
- Monitor with VGA port
- 4x4 Keypad in the configuration below:
<img src="">

## Program Setup
1. Pull or download this repository onto the computer with Vivado installed
2. Connect the Nexys A7-100T board to the computer using the Micro-USB cable
3. Connect the VGA cable to the Nexys A7-100T board and the VGA monitor
4. Connect the keypad to the Nexys A7-100T board, ensuring it's not upside down
5. Open Vivado and create a new RTL Project
6. On the "Add Sources" page, click on "Add Files" and add all of the .vhd files from this repository 
7. On the "Add Constraints" page, click on "Add Files" and add all of the .xdc files from this repository
8. On the "Default Part" page, click on the "Boards" tab and find and select the "Nexys A7-100T" option
9. Click "Finish" in the New Project Setup window
10. In the "Flow Navigator" sidebar, click on Generate Bitstream under the Program and Debug tab
11. It will start Synthesis and Implementation, and will notify you when it's ready
12. Open the Hardware Manager
13. Select "Open Target" then "Autoconnect"
14. Select "Program device" then select the Nexys A7-100T it shows
15. Program should show up on the VGA monitor

## Inputs and Outputs
### Inputs

### Outputs
**vga_top**
## Modifications of Starter Code
