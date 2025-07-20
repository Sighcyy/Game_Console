# June 29th, 2025

Today was a very important day. After completing my second creation, I wanted to move on to my third. The second invention was very PCB design-heavy, where I had to make sure every was routed efficiently. However, one aspect that I never got to go deeper into was portable objects, sound, or display hardware. Thus, for my 3rd creation, I wanted to make a game console. I was looking into the Gameboy color and trying to re-create it, as I was trying to go for a retro game console kinda look, and Pokémon, Tetris, and Super Mario were all things that I considered retro that was a part of the Gameboy color. However, I wanted to add my twist to it, but that's something that would be considered for later. Today, I made sure to find all the necessary parts, and then I will start creating my schematic. 

![Screenshot 2025-06-30 143531](https://github.com/user-attachments/assets/31d42806-0cfc-49f1-9105-30aa27835a35)

# June 30th, 2025
 A lot of the footprints for the switches I was planning to use were missing, so I spent most of today looking at SnapEDA to find footprints and using GrabCAD to find 3D models of the objects so I could make some measurements relative to the microcontroller and the LED screen. As I was doing this, I realized I had to switch the microcontroller that I was using to a RASPBERRY PI ZERO 2 WH as it would be better for the situation of making a retro game console. 

I also took this opportunity to make a rough sketch of what my PCB would look like with the parts that I had.

 ![Screenshot 2025-07-06 202456](https://github.com/user-attachments/assets/2b100bf5-fced-4035-8437-fb3a0072868e)
![Screenshot 2025-07-06 202507](https://github.com/user-attachments/assets/91ed0d71-3c2d-485a-9502-b1dc79aca13b)



# July 1st, 2025
Today was a bad day for me. Firstly, I wanted to look into the nuances of how the display would function and how the power supply and audio would work. I looked into these mainly because I wanted to make sure that I was performing all the new things as I wanted them to work. I found that I needed to ensure a constant power supply from the battery pack, so I required a buck converter. From this, I learned that this project was a little harder than I thought. This process of just learning and finding the footprints, and saving them was what took so long. Additionally, I realized I may not have enough digital pins in order to get this project done because the LED would be taking 26 pins. That was the biggest time waster; however, I found that not all pins were being used. So I found a table telling me which ones I can still use. Not much was done for the CAD or the PCB, so I included some pictures of my research and some websites I was using to prepare for the building.

![Screenshot 2025-07-06 221041](https://github.com/user-attachments/assets/7818d9b6-9c82-4a7e-be69-02a29f32cb5f)
![Screenshot 2025-07-06 221140](https://github.com/user-attachments/assets/e5ac784a-4566-436a-b0b0-a9f4307f28ca)
![Screenshot 2025-07-06 221104](https://github.com/user-attachments/assets/026b5222-1dc5-42f3-bf4b-586a3f24fc23)



# July 2nd, 2025
All research today. I found 3D models for all my parts so that I could use them to make my case properly. I had to find exactly all the right parts that I was going to use in the process, so I made a folder with all the links to buying the parts and downloading the reference CAD models. 

![image](https://github.com/user-attachments/assets/bae6c026-d5ea-457e-991e-20224d2aa3f0)


# July 3rd, 2025
Today is where I wanted to start making my CAD model and making the design somewhat unique. Firstly, I didn't want to use audio, mainly because I looked for an LED screen that came with a headphone jack. I wanted to embrace a minimalist design look that is somewhat complex in appearance. Additionally, a buck converter would be unnecessary since I was delivering the right amount of voltage needed by the screen. Meaning I was done with my PCB and I started my PCB 3D model, so everything would be added so I can start making my case. 

![Screenshot 2025-07-09 194822](https://github.com/user-attachments/assets/b6c4e04a-c924-422e-bd9a-4329f22ed4d0)


![Screenshot 2025-07-09 195436](https://github.com/user-attachments/assets/52386e67-c864-4840-960d-db5699e806a5)



# July 6th, 2025
I was out with my family for the July 4th holiday and came back a bit late today. I wanted to start making the case. Mostly the bottom layer

<img width="1848" height="1203" alt="Screenshot 2025-07-10 205707" src="https://github.com/user-attachments/assets/b4fa6b3b-21c8-4ebd-9617-84ca983d8b34" />


# July 7th, 2025
Whole lot of changes today. Firstly, I wrote down a list of my pros and cons of my console. I hated all the cons, so I went down trying to fix all of them. Firslty was the battery. I wanted it to be rechargeable, so I switched to a lithium-ion battery and a boost converter. On top of that, these would be easier to wire onto the bottom of the Raspberry PI Zero 2. Next, I hated how long it was, so I changed the sizing of the PCB to make it better for myself and cheaper overall by making it under 100x100. I started to build the new case, and it was coming out a lot better. Finally, I hated how, when I was making the case rotary encoder would stick out. I thought that it would make things annoying, so I removed it. For my schematic I'll have to also document another way to show how I am soldering the wires to the bottom of the Micro Controller, but that is a plan for tomorrow along with making some sort of compartment for the battery and the boost converter.

<img width="2090" height="1169" alt="Screenshot 2025-07-12 214837" src="https://github.com/user-attachments/assets/3cff467f-c676-4636-b45d-a6329eb671de" />
<img width="1001" height="1044" alt="Screenshot 2025-07-12 144829" src="https://github.com/user-attachments/assets/d15ed4de-7edc-40d6-82b3-ad34798098a6" />
<img width="1634" height="1218" alt="Screenshot 2025-07-12 214920" src="https://github.com/user-attachments/assets/9636149f-08f6-46b2-8875-7c7105c39fcf" />
<img width="1146" height="1125" alt="Screenshot 2025-07-12 214902" src="https://github.com/user-attachments/assets/2c6da0d1-9bfb-4d69-b04c-d0409a8e1a72" />


# July 10th, 2025
I spent a whole lot of time today working on the CAD model today. I created a place for the battery and the boost converter, and the whole for it on the case. Additionally, I tried my best to minimize size wherever I can, so I spent a lot of time on that


<img width="1170" height="1244" alt="Screenshot 2025-07-19 110511" src="https://github.com/user-attachments/assets/48d8982d-7a95-4221-a3f7-0e7f12cf77bd" />



# July 11th, 2025
I finished the whole CAD Model and began the easier part. A search for a community-built emulator for retro games. I found it super quick and it turned to be a software called Retro Pie. It would help configure most of my buttons as well so the firmware section got super easy for me. I also finished some schematic and had to create my own way to showcase how I would be soldering to the bottom of the Pi.

<img width="2304" height="1728" alt="Boost to Pi" src="https://github.com/user-attachments/assets/65bb66a0-6caf-44e8-ba34-505002f7a634" />
<img width="1634" height="1218" alt="Screenshot 2025-07-12 214920" src="https://github.com/user-attachments/assets/3c0f122b-cd40-4c9b-9b4d-94fba6c51f99" />
<img width="2193" height="1222" alt="Screenshot 2025-07-20 155823" src="https://github.com/user-attachments/assets/676ae63e-a5a5-4a8b-a742-446bef8bbc18" />

