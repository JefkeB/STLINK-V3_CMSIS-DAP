# STLINK-V3_CMSIS-DAP
cmsis dap for a stlink-v3mods

Based on the work of [RadioOperator](https://github.com/RadioOperator)

links  
[stlink-v3mods (ST site)](https://www.st.com/en/development-tools/stlink-v3mods.html)  
[CMSIS DAP Firmware](https://github.com/RadioOperator/CMSIS-DAP_for_STLINK-V3MINI)  
[Bootloader with compiled application](https://github.com/RadioOperator/Yet_Another_Bootloader/tree/master/STLINKv3_YAB)  

Download the Bootloader with the compiled application  
Connect the stlink to the computer  
Reset the stlink by bridging CN4  
Run the following command in a terminal window  
>  java -jar STLinkUpgrade.jar -force_prog 

Wait until the update is done ...  
Now the stlink comes up in YAB mode with a new drive appearing called 'APP_HERE'  
Open the drive and drop the application slv3app1 on it  
After a moment we have a 'HighSpeed-HID CMSIS-DAP' programmer available  
