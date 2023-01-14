# SmartGlasses
This is the official GitHub repository for my Maturarbeit on building Smart Glasses

!!! Read This !!!

-In this GitHub repository, there are all the files necessary to recreate this project. 

-Check the Document on what materials you need. 

-The building process is also listed in the document, along with the problems i faced and soforth. Here i will be providing a rough overview what to do. 

-Check the document on the material list. There there will also be links to getting the materials. 

-Once you've aquired all the necessary parts and also the tools such as a soldering iron and 3D-printer, you can continue by looking at the circuit.png in the repository.

-There you'll see how the circuit is assemble it. Follow the circuit and solder the components with standard copper wires. Make sure to assemble the switch and the touch button only after placing them in the case.

!!TIP!! For GND and 3v3, dont attach two wires to the one port on the ESP32, split the one cable coming from the processor into two via soldering !!TIP!!

-Print out the parts provided in the STL file.

-Start assembling by placing the circuit in the case, make sure the charging port on the side of the switch hole, and the display comes out the opposite hole.

-After placing the glasses in the circuit, you can use tape or glue to attach the lid on top. 

-To attach the holders to the main frame of the glasses, it is recommended to use a screw and screw cap to fasten the connection. 

-Again you can decide whether to use tape or glue when attaching the case to the right holder. Decide how the case comfortably fits. Make sure to put the frame through the wiring of the display, so that the display remains on the inside of the frame. 

-Now attach a lens fittin to your focal length and test the position where it fits you best. Attach it with glue. 

-For the glass part of the glasses, you are free too use what you wish, I decided to use a thin plexiglass film and glue it to the outside of the frame. I then reprinted the frame, changing the thickness of the frame and glueing it ontop of the glass, sandwiching it inbetweek the two frame pieces. 

For the Android Studio, make sure to define the MAC address of the ESP32 in all-caps when copying it over from the Serial Monitor of the Arduino IDE. 

Build the APK and deploy it onto your Android phone. 

When you turn on the switch of the ESP32, it will say Ready, Mode Bluetooth. Go to your phone bluetooth settings and connect the ESP32 to your phone.

Then head to your app and click start. Then press the button, and you will see that the screen changes. The Glasses work. For the features of the Device, check the Paper.

Check the Arduino Code aswell to see the parameters of the powersave and soforth. Adjust to your liking. 

Now you are done!

This Matura Project is based off a tutorial from another repository: https://github.com/heytechv/YouTube_SmartglassesV2 
