# PCB-Business-card
Printed Circuit Boards (PCB) are used in almost all computers and electronics today since it is the main connection holder of the electronics components through its different layers, but what if we use the PCB layers to create an artful design like a PCB Business Card that shows some personal contact information and demonstrate how talented you are.

Following this guide you will be able to customize the PCB Business card model created by JLCPCB and you could update the model with your personnel information like (name, profession, Email etc..). This project guide has the necessary files to help you step by step to produce your own PCB Business card. Please follow the project steps to get a positive result. After finishing your design, you can visit us through our website [JLCPCB](http://jlcpcb.com) to enjoy our special offers.

# Starting from the bottom

All along this explanation, we refered to [EasyEDA](http://easyeda.com) as our main design tool.
Before we starting the below explanation you can just skip it all and just get through the design that JLCPCB provides through the following link which is related to a public EasyEDA project and this way you can just update the design by your personal information. Following is the image related to the designed project :
<p align="center">
  <img src="rootImages/sample.JPG" width="60%"></p>
  
The first and most important information that we must consider is the PCB drawing layers and objects since it is a key when we design a unicolor PCB.
A PCB has multiple layers and each one of these layers has its own use and importance, our PCB Business card is a two sides PCB so we will focus on the following basic layers:
<p align="center">
  <img src="rootImages/PCBlayers.png" width="60%"></p>
  
* TopLayer/BottomLayer: The top side and bottom side of the PCB board, copper layer.
* TopSilkLayer/BottomSilkLayer: Board silkscreen, screen printing is transforming Ink onto a substrate to draw some texts and logos on the board sides.
* TopSolderMaskLayer/BottomSolderMaskLayer: The top and bottom cover layers of the board are typically green oil, which acts to prevent unwanted welding.

We will create our design based on the handeling of the defined above layers 

# How to start the PCB design 
As mentioned above, we will refer to [EasyEDA](http://jlcpcb.com) design tool to prepare our PCB design, all what it takes is getting to the EasyEDA designer (step 1) and start a new project that contains a PCB design file (step 2) than it will appear the PCB Design area.
<p align="center">
  <img src="rootImages/basicSteps.png" width="100%"></p>
Here we will start to prerape the PCB board outline relatively to some real dimensions.
Basically the card has the following width and height sizes:

* Board width: 86.50 mm
* Board height: 53 mm 

right in the PCB design area, select the board outline layer from *layers and objects* palet and select the *track* tool from the pcb tools palet and start drawing the lines of the board outline relatively to the set size
<p align="center">
  <img src="rootImages/size.png" width="100%"></p>

Once you set the baord outline you can start drwing some art shapes and tracks to make a circuit board looking for the design, you can starting by drawing the traces using the top layer (copper) these lines and shapes will be slightly visible under the soldermask layer once you produce the PCB as it shows the below image
<p align="center">
  <img src="rootImages/tracks.png" width="100%"></p>

# Update our JLCPCB design
Please refer to our design if you want to get inspired or if you want to update it with your information.
You will find the following fields :
* Your Name
* Your profession
* Your Email
* Your phone number
* Your website
<p align="center">
  <img src="rootImages/details.png" width="100%"></p>

Just double click the text and write your details as it shows the following image :
<p align="center">
  <img src="rootImages/name.png" width="100%"></p>

Do the same for all of the required details, and you can even add some additional ones.
The selected layer is the TopLayer (copper), you can write or draw in the bottom layer as well.
In our design, we have uploaded our JLCPCB logo as png image and we set it to the bottom copper layer, all what it takes to make the task easier is just hide the TopLayer and keep the bottom layer visible and then move to the PCB tools and select *image* then this will open a new window from where you can browse your computer files to upload the image (please choose an image in PNG format) you can find more details on **how to proparely insert image in PCB editor** through the following link : click [here](https://docs.easyeda.com/en/Import/Import-Image/index.html)  

![settings](/rootImages/settings.png)
![InsertImage](/rootImages/image.png)

