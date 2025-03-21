# Unreal på glasburets computer

## Content 

* [What is VR with unreal engine: examples](#what-is-vr-with-unreal-engine)
* [Preparation](#preparation)
* [Create your 1st VR project in UNREAL ENGINE 4](#create-your-1st-vr-project-in-unreal-engine-4) 	
* [Blueprint scripts](#blueprint-scripts)
* [Optional plugins](#optional-plugins)


## What is VR with unreal engine

1) Game and entertainment https://www.unrealengine.com/en-US/industry/games  
2) Training  https://www.unrealengine.com/en-US/industry/training-simulation 
3) Architecture https://www.unrealengine.com/en-US/architecture-solution 
4) Transportation https://www.unrealengine.com/en-US/industry/automotive-transportation 
5) Events https://www.unrealengine.com/en-US/industry/broadcast-live-events 
6) Television and movies https://www.unrealengine.com/en-US/industry/film-television 
7) More https://www.unrealengine.com/en-US/industry/more-uses 
8) Modelling in VR and 3D printing   https://www.youtube.com/watch?v=PViW68-hbTM
9) Interaction with arduino   https://www.youtube.com/watch?v=3xbV4-DH3hY&list=PLq7fFmlXXY73S0H5xFqpCDMy2IinmsYd4&index=46
10) https://www.youtube.com/watch?v=TWjtE5kUqHA 
11) from 3d scan to vr https://www.youtube.com/watch?v=mZcLKcyHWDs 

## Preparation 
Follow steps 1-6 if it is the first time you use VR on your machine. Otherwise skip to Step 6) Connect VR steam to PC

![image](https://user-images.githubusercontent.com/46813348/114923107-b5c0e780-9e2c-11eb-84a5-40ce431ddf85.png)

#### Step 1) Tools required:
* Room or a space big enough to move (you can book and use "glasburet")
* HTC Vive set (from DDlab) 
  * Visor
  * Controllers 
  * Sensors  
  * Connection cables 
* PC or laptop (You can use the vr-machine in glasburet) 

###### Setting up equipment
Set up the two sensores on their wall-mounted spots


<img src="https://github.com/DDlabAU/VR-Guide-/blob/main/PICTURE%20VR/Picture%2022.jpg" width="400" height="400" /> <img src="https://github.com/DDlabAU/VR-Guide-/blob/main/PICTURE%20VR/picture%2021.jpg" width="400" height="400" />


#### Step 2) Set up VIVE ROOM 
Download setup vive from https://www.vive.com/sea/setup/   
Follow the guide to set up the room and the play boundaries.

When the you are asked to put the cords into the computer, the HDMI and USB port needs to be in these posistions if you are using "glasburet". If they are placed correctly, the system will recognise them and accept the placement, during this part of the setup. 

<img src="https://github.com/DDlabAU/VR-Guide-/blob/main/PICTURE%20VR/Picture%2020.png" width="400" height="400" />

#### Step 3) Steam VR
Download steam vr from https://store.steampowered.com/app/250820/SteamVR/  


#### Step 4) Steam
Create an account on Steam


#### Step 5) Unreal Engine 4
Download Unreal Engine 4 from https://www.unrealengine.com/en-US/ 
  

#### Step 6) Connect VR steam to PC

![image](https://user-images.githubusercontent.com/46813348/114928939-79dd5080-9e33-11eb-8de3-94e358bb63ef.png)

Flowchart of the above steps: 

![image](https://user-images.githubusercontent.com/46813348/114925797-d6d70780-9e2f-11eb-9168-ab283f66842a.png)


## Choosing Unreal engine or Unity
Choosing whether to use Unreal engine or Unity is a heavily debated subject, but is in the end up to the individual user. The following is a list of reasons to look at one or the other, based on sources linked futher down.  

### 2D or 3D
First of, both engines are good at what they do and is always best to use what seems easiest for you, but they do have some different implent areas. 
Unreal is good at 3D and and high visual games, and function great for VR for this reason.
Unity are good at making mobile app and 2d platform games, but also function really well with 3D and VR building.
So if you wish to make a 2D game, try and look into Unity.

### Writing
The engines have diffentent coding languages. Where Unreal uses C++, Unity uses C#. C# is generally seen as the easier language of the two for a newbie, but many also point to the benefit of knowing C++, but this is, in the end, up to you.
What is interesting is the Nodes writing style. Both programs have this, but Unreal was the first to use it. Here it is called Blueprint and it is used to code visually and use less actual coding language. You use nodes that can be moved around and connected through lines. Unity imported at thrid party way of doing the same called Bolt a few years ago.
So even if writing code from scratch seems a little intmidating, there are a way of making a game without having to know every command. Here many still prefer Unreals Blueprint since it has been around the longest.

### Grafics
There isn't the biggest difference in the two, especially when beginning and learing the platforms. When put to the test, there is a small grafically lean towards Unreal, especially when it comes to realism. But it is not the biggest of differences, and only become relevant when creating big and grafically impactful games. 

In the end, the decicion is up to you. The best advice would be to look through the links below or find your own, to see which engine you would like to use. We from the lab are also ready to talk about what might be best for your project.


#### Links
https://www.youtube.com/watch?v=OH2sYJw52BQ<br/>
https://www.youtube.com/watch?v=ZG9MF5agh7A<br/>
https://www.youtube.com/watch?v=dphuMHYH_VY<br/>
https://hackr.io/blog/unity-vs-unreal-engine![image](https://user-images.githubusercontent.com/111739605/188424603-ee4a9ac0-db86-4b81-9d23-8ae9a99ad10f.png)<br/>
https://program-ace.com/blog/unity-vs-unreal/![image](https://user-images.githubusercontent.com/111739605/188424632-2c0c8414-d737-450e-bbc0-c390abd3454a.png)<br/>
https://circuitstream.com/blog/unity-vs-unreal/


## Create your 1st VR project in UNREAL ENGINE 4 

Open new level 

![image](https://user-images.githubusercontent.com/46813348/114923250-e43ec280-9e2c-11eb-8495-ae568ebb42ff.png)

You can find both maps under VirtualRealityBP/Maps/ in your Content Browser.
 
![image](https://user-images.githubusercontent.com/46813348/114925536-88296d80-9e2f-11eb-8a0a-48424d1a30b6.png)
 
![image](https://user-images.githubusercontent.com/46813348/114925477-72b44380-9e2f-11eb-8cfe-375095ad54b1.png)
 
![image](https://user-images.githubusercontent.com/46813348/114925365-4d273a00-9e2f-11eb-8e1e-286ba1591831.png)

Under PREFERENCE EDITOR, you check this setting >> (see picture)

![image](https://user-images.githubusercontent.com/46813348/114928264-af356e80-9e32-11eb-8252-48bb85184fa1.png)

## Blueprint scripts 

![image](https://user-images.githubusercontent.com/46813348/114925004-d8ec9680-9e2e-11eb-8523-b3ea66e388fc.png)
 
https://docs.unrealengine.com/en-US/Resources/ContentExamples/Blueprints/index.html 

### What is Blueprints scripts
The Blueprints Visual Scripting system in Unreal Engine is a complete gameplay scripting system based on the concept of using a node-based interface to create gameplay elements from within Unreal Editor. As with many common scripting languages, it is used to define object-oriented (OO) classes or objects in the engine. As you use UE4, you'll often find that objects defined using Blueprint are colloquially referred to as just "Blueprints". 
Blueprint-specific markup available in Unreal Engine's C++ implementation enables programmers to create baseline systems   
Learn more 😊 

## Optional plugins 

![image](https://user-images.githubusercontent.com/46813348/114923392-0e908000-9e2d-11eb-9f06-7a5eadc5850b.png)

### How to install UE4Duino step by step 
https://www.youtube.com/watch?v=XvfG56fa_Lk 
