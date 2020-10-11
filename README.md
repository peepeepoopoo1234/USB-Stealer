# USB-Stealer
Introducing, USB Stealer. This project was a collection of scripts and codes that are designed to steal stuff from a victims pc. Most of the code was not made by me, but I compiled all the code. Below, I will describe what all the functions do and how you can modify this project for your own needs. 

The .vbs files execute the batch files silently so that no cmd window pops up. The av.bat file MUST BE EXECUTED AS ADMINISTRATOR TO WORK and it adds windows defender exclusions for D: and C: drives. I did D: drive so that my usb would be left untouched by the antivirus as my usb drive is a D: drive. Next, the all.bat file executes all the vbs files besides the filestealer one. You can add this one to the batch file code if you so desire. 

The wifiSTEALER folder contains everything necessary to steal saved wifi passwords on the machine. The passwords are saved the to PASS folder. 

Next, the RAT folder is where you put your RAT stubs if applicable to you. Make sure to add the exes to the batch file to ensure the execution of them. There is an included discord token stealer, but make sure to put your discord webhook in there. Read the text file for more information. 

The third folder is the Product Key folder which caches the installed product key on the machine and saves it to a text file. There will be a messagebox that appears after execution of the vbs file, but you can dismiss it. 

The passwordSTEALER folder steals saved passwords on the victim PC. They are saved to the PASS sub-folder. 

The IpStealer folder steals the ip of the target's connected wifi and saves it to a text folder in the directory. 

Finally, we have the fileSTEALER fodler. This takes any specified file from the user. You can configure which files you want by modifying the attached batch file. 

LEGAL DISCLAIMER-
I, the creator and all those associated with the development and production of this program are not responsible for any actions and or damages caused by this software. You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only. This software's intended purpose is NOT to be used maliciously, or on any system that you do not have own or have explicit permission to operate and use this program on. By using this software, you automatically agree to the above.

Also note, I did not create most of these tools, but merely compiled them into a single, cohesive tool designed for a USB. Any questions or suggestions, please feel free to contact me at my discord, SOVIET#3565. Have fun bois! :)
