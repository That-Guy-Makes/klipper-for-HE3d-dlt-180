installing klipper is simple, all be it diffrent then I am used to, lucky for you, you have this guide though :)

step 1 - connect to your klipper host
  I wont go into detail, as theres plenty of info on docks, or contact me on discord

step 2 - make menuconfig

  to make your config type in "make menuconfig" (after cd into klipper) and you should have a screen pop up
  
  change it to have these settings: 
  <img width="1668" height="782" alt="Screenshot 2026-07-25 18-52-46" src="https://github.com/user-attachments/assets/d9a6bb04-6ad9-4aff-b550-0d12dd50cea8" />

  Once that is set press "q" and it will prompt to save press "y"

 step 3 - make

   once the config is set type "make clean" into the ssh terminal then "make" it should show a ton of stuff wait for that to be done.

   Navigate to the "out" folder and find "klipper.elf.hex" and save it to your computer

step 4 - flash

  im using cura for this, purely because thats what i knew how to use im sure theres other better ways, but this is how I did it.

  I started by making a custom FFF printer, clicking on that name then opening the manage printers tab.

  on this tab theres a button to flash custom firmware, to use you have to hook the mobo to the pc, so do that.

  once that is done it should be outlined in blue, click it and add the "klipper.elf.hex" to it

  wait a while and it should say its flashed.

step 5 - test

  connect the machine to your klipper host and check for its serial and configure it, i wont go into detail tons of better docks and info

congrats! if everything is done right you should have a klipper flashed HE3d dlt-180

if you have any questions join my discord, and consider subscribing to my youtube
