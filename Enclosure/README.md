# How to Create an Acrylic Enclosure:

Creating an enclosure for an arduino project moves it from a prototype to it's final permanent phase. It allows for a more sturdy and stable project. It can also help with the longevity of your project. 

## Things to keep in mind:

- What you’ll need to prepare in advance:
    - An arduino project schematic 
- Items you will need:
    - To prototype:
         - Arudino Uno (Unless otherwise necessary)
         - Solderless Breadboard
         - Jumper wires
         - Optional: resistors, Leds, buttons, etc. (what is required for your specific project)
    - To Solder:
        - Arduino prototype shield
        - Soldering iron and materials 
    - To Build Enclosure:
        - Basic measuring tools 
        - Adobe Illustrator 
        - Optional: Screws, screw drivers, and acrylic glue
- Experiences that are relevant or helpful to complete the task:
    - You may find it useful to read through [Getting Started with Arduino](https://www.amazon.com/Getting-Started-Arduino-Electronics-Prototyping/dp/1449363334) for more information. 

# Step-by-Step Instructions(including pictures):

## 1. Build your project
- Prototyping on a solderless breadboard 
- Running tests

## 2. Solder your Project:

1. Before starting to solder your project begin by estimating and measuring how large you’d like your enclosure to be and in what position
    - Start by identifying where your arduino will be placed at the base of your enclosure. Note: It is best to screw your arudino into the enclosure to establish a        secure foundation for the circuit and ensure it does not move around loosely within the enclosure.
    - <img src="images/arduinoscrew.jpeg" style=width:50%;height:50%>
    - Once you know where your arudiono will be located, hold up the project how you’d like it to stand inside the enclosure. If you have extended parts, such as a         keypad and LEDs in this example, make note of how much wire you will need to reach from the arduino to the LED in the position you want. 
    - <img src="images/keypad.png" style=width:25%;height:25%>
    -  <img src="images/wires.png" style=width:25%;height:25%>
    - Take measurements of the height, width, and depth for your enclosure. *Note: It is better to overestimate the measurements and have more space than to squeeze         everything into a smaller enclosure.*
2. It is recommended to not touch your working prototype but use it as a reference. To begin soldering, make sure to collect all the parts you need and ensure they are working properly. You can do this by replacing new parts in increments in the working prototype and making sure it is still functioning properly. 
    - Items you will need: anything you used in your prototype except for jumper wires, we will instead use stranded or solid wire.
        - Solid wire is thicker, and offers higher current capacity. They are greater for longer distances since it features less dissipation. 
        - Stranded wire offers superior bendability and flexibility, making them easier to route around obstacles. They can sustain more vibration and flexing without          breaking. 
        - When it comes down to choosing between solid and stranded wire there is no clear choice, pay attention to the needs of your project. 
        - <img src="images/solidstranded.jpeg" style=width:50%;height:50%>
    - You will also need an arduino prototyping shield. This is where you will solder your cricuit and eventually connect your arduino into. 
3. You will now solder your components into the arduino proto shield following the prototype you made earlier.
    - If you have never soldered before [here](https://www.youtube.com/watch?v=Qps9woUGkvI ) is a quick tutorial on how to solder electronic components
    - <img src="images/soldering.gif" style=width:50%;height:50%>
    - You will also need to solder female and/or male headers to the pin positions on both sides of the arudino proto shield. The type of header you will use depends       on where you need pins inserted. 
        - Female headers have only one side with pins and the other side is where you can connect pins. There are straight and right angle headers.
        - <img src="images/fheader.jpeg" style=width:25%;height:25%>
        - <img src="images/rfheader.jpg" style=width:25%;height:25%>
        - Male headers have pin on both sides you can insert into the arduino shield and connect another female head. 
        - <img src="images/mheader.jpeg" style=width:25%;height:25%>
    - This is what will hold the shield in place with the arduino and secure it. 
    - <img src="images/pinheader.png" style=width:50%;height:50%>
    - <img src="images/arudinoconnected.jpeg" style=width:50%;height:50%>

    
    
## 3. Test/Troubleshooting the Soldered Project:

1. Once you have completed the soldering of your project, you can now plug it into your ardunio and test to see if it works
    - _Note: If your project isn’t working, do not be alarmed it is very typical to run into problems at this stage. _
2. If you run into problems begin by testing the arudino against the original prototype to ensure the code is still running properly.
3. You can then reference your prototype and ensure you have connected all the necessary wires, resistors, etc. properly.
    - Pay close attention to your arduino proto shield and ensure horizontal connections are properly connected. _Note: Shields come in different versions, some pre-        connect rows and others do not._
    - <img src="images/shield1.jpeg" style=width:25%;height:25%> <img src="images/shield2.jpeg" style=width:25%;height:25%>
4. If your circuit is properly connected then take a closer look at the soldering of your components.	
    - You may need to use a magnifying glass to take a closer look at the connection. Make sure that the solder is not only on the component but securly attached to        the shield as well. _Note: Lightly tugging on the wires may help identify a loose connection._
    - <img src="images/soldermistakes.png" style=width:50%;height:50%>
5. Reestablish any loose connections with solder.
    - If you made a mistake while soldering, you make correct it by reheating the misplaced solder. This will turn it back into liquid, and you must quickly slap it        onto a table or surface to remove it. 
6. Revisit steps 2-6 until you are able to troubleshoot and get your project working. Once it is up and running we can begin creating the enclosure. 


## 4. Designing the Enclosure: 

1. Figure what kind of enclosure you want. Enclosures can be made out of many different materials depending on the purpose and usage of the project. However, for this section we will focus on acrylic for the enclosure. 
    - Benefits for acrylic:
        - Excellent optical clarity & transparency
        - Highly resistant to variations in temperature
        - Up to 17 times the impact resistance of ordinary glass
        - Half the weight of glass and idea for precision machining
        - Highly resistant to different chemicals
    - Disadvantages for acrylic:
        - Acrylic is tough and durable, but can also be easily scratched
2. Choose an enclosure design. Using a design platform like, https://en.makercase.com/, you can choose from 3 different enclosure designs: Basic box, polygon box, kerf bent box. 
    - _Note: Unless otherwise necessary, it is reccomended to go with the basic box._
    - <img src="images/box1.png" style=width:50%;height:50%>
4. Modify enclosure design. Using the same platform you can now modify the box your creating. 
    - Modifications include the width, height, and depth of the box. Using the prior measurements you took input the amounts to see a virtual display of your               enclosure.You can also indicate whether the measurements are for the inner or outer dimensions.
    - <img src="images/box2.png" style=width:50%;height:50%>
    - The thickness of your box should correspond to the acrylic piece you will be using.
    - You can also decide whether you’d like the box to be open or closed
    - <img src="images/box6.png" style=width:25%;height:25%>
    - Finally, choose the type of edge you’d like for the box. Using a flat or finger edge will require the use of acrylic glue to stablize the enclosure. _Note: if        you need to access the inside of the box, this would be made difficult with these choices._ Alternatively, t-slot edges are held with bolts. You can decide the        type of bolt diameter and length depending on what you have available. This allows you to access the inside of the box if any debugging or adjustments are              necessary while still maintaining the secure exterior. 
    - <img src="images/box3.png" style=width:50%;height:50%>
5. Customization: Upload to Abobe illustrator. If you’d like to further customize the enclosure you can download the previously created design as an svg file and upload it to adobe illustrator. 
    - <img src="images/box4.png" style=width:50%;height:50%>
    - Using the selection tool you can drag edges as preferred for any customized sides or pieces. You can also add circles for sections to create space for hinges to      be screwed if the box is meant to be opened. 
    - <img src="images/box5.png" style=width:50%;height:50%>

## 5. Print with a laser cutting machine
1. Print a prototype. Once you’ve completed any customization and finalized the design you can now print a protoype on cardboard to ensure the size works for your project before printing on acrylic.
    - To print with a laser cutter upload the adobe illustrator file and follow the instructions to adjust speed, power, and vector settings according to your              instructions. _Note: For New York University Abu Dhabi students be sure to schedule an appointment to access the laser cutting machine and have a lab assistant         help you. _
    - <img src="images/cardboard.jpeg" style=width:50%;height:50%>
2. Adjust if needed and print the final enclosure. Make as many adjustments as needed by repeating the previous step and using cardboard prototypes. Once you have a design that fits your project, print on acrylic and put your final enclosure together. 
    - <img src="images/lasercutting.gif" style=width:50%;height:50%>
