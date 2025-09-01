# June 29th, 2025
Time: 2 hours

Today was a significant milestone in my personal electronics journey. After completing my second project—which was heavily focused on PCB design and signal routing—I realized there were areas I hadn’t explored yet, particularly portability, audio integration, and display hardware. With that in mind, I decided to begin my third project: designing and building a custom retro-style handheld game console. Inspired by the Game Boy Color and the nostalgia of games like Pokémon, Tetris, and Super Mario, I wanted to create something that captured that retro aesthetic but also pushed me into new technical territory. Unlike my previous work, this project would combine multiple disciplines: display interfacing, audio output, power management, and user input through physical controls.

Today’s focus was on planning and sourcing all the core components. I researched compact 3.5” displays compatible with SPI or parallel interfaces, small mono speakers with amplifier boards like the PAM8302, and a rechargeable Li-Po battery system using modules such as the PowerBoost 1000C. I also started considering how to route inputs from tactile buttons into the main processing board—likely a Raspberry Pi Zero 2 W for its compact form and emulation capabilities. With the parts identified, the next step is to begin the schematic design, where I’ll bring together power, video, audio, and controls into a single PCB. While I have ideas for future enhancements, like a unique case or custom OS interface, today was about laying the technical foundation.


![Screenshot 2025-06-30 143531](https://github.com/user-attachments/assets/31d42806-0cfc-49f1-9105-30aa27835a35)

# June 30th, 2025
Time : 3 hours

Today was all about refining the hardware planning process. I initially ran into a roadblock when I discovered that many of the footprints for the switches I intended to use were missing from the standard libraries. To solve this, I turned to SnapEDA to search for compatible footprints and cross-referenced them with GrabCAD to find accurate 3D models. This allowed me to visualize how each component would fit together, especially in relation to the microcontroller and 3.5” LED screen, helping me take precise measurements and maintain ergonomic spacing for the physical controls.

During this process, I made a key decision to switch my microcontroller to a Raspberry Pi Zero 2 WH. Its onboard Wi-Fi and processing power made it a better fit for a retro game console, especially for emulation tasks and future expandability. With most of the components selected and properly modeled, I sketched out a rough layout of the PCB, visualizing how everything—screen, buttons, speakers, power module—would come together on a single board. This early planning stage will help streamline the schematic and layout phase moving forward.

 ![Screenshot 2025-07-06 202456](https://github.com/user-attachments/assets/2b100bf5-fced-4035-8437-fb3a0072868e)
![Screenshot 2025-07-06 202507](https://github.com/user-attachments/assets/91ed0d71-3c2d-485a-9502-b1dc79aca13b)



# July 1st, 2025
Time: 3 hours

Today didn’t go as smoothly as I had hoped. I set out to dive deeper into the functionality of the display, power supply, and audio system, hoping to clarify how everything would work together before moving forward with the schematic. While researching, I realized that ensuring a stable power supply from the battery pack would require a buck converter to regulate voltage efficiently. This added complexity made me realize that the project is more challenging than I initially expected. A lot of time was spent just finding component footprints, saving them, and organizing them for future use—something that seems simple but ended up being surprisingly time-consuming.

The most frustrating part of the day came when I thought I wouldn’t have enough available GPIO pins, since the LED screen alone was using 26. That caused a lot of confusion and delayed progress until I found a pinout reference table showing which pins were actually occupied and which ones were still free to use. Thankfully, it turns out I still have enough pins for my other components. While I didn’t make much progress on the CAD model or PCB layout today, I did collect and save screenshots and research links that I’ll refer back to during the build. Even though it was a tough day, it was still valuable in helping me understand the deeper integration challenges of this project.


![Screenshot 2025-07-06 221041](https://github.com/user-attachments/assets/7818d9b6-9c82-4a7e-be69-02a29f32cb5f)
![Screenshot 2025-07-06 221140](https://github.com/user-attachments/assets/e5ac784a-4566-436a-b0b0-a9f4307f28ca)
![Screenshot 2025-07-06 221104](https://github.com/user-attachments/assets/026b5222-1dc5-42f3-bf4b-586a3f24fc23)



# July 2nd, 2025
Time: 1.5 Hours

Today was fully dedicated to research and preparation. I focused on gathering accurate 3D models for all the components I plan to use, which will be essential for designing a properly fitting enclosure later on. Making the case look clean and functional requires precise dimensions, so having reliable CAD references was a top priority. This meant going through part datasheets, mechanical drawings, and online libraries like GrabCAD and SnapEDA to ensure the models were correct and matched the components I plan to purchase.

To stay organized, I created a dedicated folder containing all the part links—both for purchasing and downloading reference files—so everything is centralized when I begin the CAD design. This research phase may not be flashy, but it’s critical for avoiding mistakes later in the build. With the 3D models now in place, I’ll be able to begin roughing out the case design and start aligning it with my PCB layout in the next stages of the project.
![image](https://github.com/user-attachments/assets/bae6c026-d5ea-457e-991e-20224d2aa3f0)


# July 3rd, 2025
Time : 2 hours

Today marked the beginning of the CAD modeling phase, where I started shaping the physical form of my console and working toward a design that felt minimalist yet refined. One major decision I made was to exclude audio circuitry altogether. Instead, I opted for an LED screen that includes a built-in headphone jack, which simplifies the design and stays true to the clean aesthetic I’m aiming for. I want the final look to be simple and intentional on the outside, but technically impressive under the hood—something that reflects both elegance and complexity.

Another key update is that I determined a buck converter is no longer necessary, since my power supply already delivers the correct voltage required by the display. With that out of the way, I finalized my PCB design and officially transitioned into building the 3D model of the PCB. This step is critical, as it allows me to accurately position all components in CAD and begin shaping the custom case around them. From here, I’ll continue refining the layout and focus on making the enclosure both visually distinct and ergonomically sound.

![Screenshot 2025-07-09 194822](https://github.com/user-attachments/assets/b6c4e04a-c924-422e-bd9a-4329f22ed4d0)


![Screenshot 2025-07-09 195436](https://github.com/user-attachments/assets/52386e67-c864-4840-960d-db5699e806a5)



# July 6th, 2025
Time : 0.5 hours

I was out with my family for the July 4th holiday and got back a bit later than expected, so I didn’t have as much time to work on the project today. That said, I still wanted to make some progress and began focusing on the next major step: designing the case for the handheld console.

I started working on the bottom layer of the enclosure, which will house the PCB, battery, and internal wiring. This part is crucial since it determines how the components will sit, how the case will be assembled, and how much internal clearance I’ll need. I kept the design simple for now, focusing mainly on layout and structural alignment, and I’ll refine it as I go.
<img width="1848" height="1203" alt="Screenshot 2025-07-10 205707" src="https://github.com/user-attachments/assets/b4fa6b3b-21c8-4ebd-9617-84ca983d8b34" />


# July 7th, 2025
Time: 2.5 hours

A lot changed today as I took a step back and evaluated my console by listing out its pros and cons. After reviewing the list, I realized I wasn’t satisfied with several key design choices—so I set out to fix them. The first major change was the power system. I decided to switch to a rechargeable lithium-ion battery paired with a boost converter, which not only simplified wiring but made it easier to integrate underneath the Raspberry Pi Zero 2. This setup offers more flexibility and fits better with the portable, self-contained design I’m aiming for.

I also wasn’t happy with the length of the PCB, so I resized the board to fit within 100x100mm—making it more compact and cheaper to manufacture. With the new dimensions in mind, I began rebuilding the case from scratch, and it’s already turning out much cleaner and better aligned. Another improvement involved removing the rotary encoder, which awkwardly stuck out from the case and didn’t contribute enough to justify the hassle. Looking ahead, I’ll need to update the schematic to reflect the new power setup and document how I plan to solder wires to the underside of the Pi. Tomorrow’s focus will be designing a dedicated compartment for the battery and boost converter to keep the internal layout organized and accessible.
<img width="2090" height="1169" alt="Screenshot 2025-07-12 214837" src="https://github.com/user-attachments/assets/3cff467f-c676-4636-b45d-a6329eb671de" />
<img width="1001" height="1044" alt="Screenshot 2025-07-12 144829" src="https://github.com/user-attachments/assets/d15ed4de-7edc-40d6-82b3-ad34798098a6" />
<img width="1634" height="1218" alt="Screenshot 2025-07-12 214920" src="https://github.com/user-attachments/assets/9636149f-08f6-46b2-8875-7c7105c39fcf" />
<img width="1146" height="1125" alt="Screenshot 2025-07-12 214902" src="https://github.com/user-attachments/assets/2c6da0d1-9bfb-4d69-b04c-d0409a8e1a72" />


# July 10th, 2025
Time: 1.5 Hours

I dedicated most of today to working on the CAD model of the console. A big focus was creating a dedicated compartment for the lithium-ion battery and boost converter, along with a precise cutout on the case for access and airflow. Integrating these components cleanly into the design required careful attention to spacing, alignment, and fit, especially to keep things compact without compromising functionality.

In addition to that, I spent a significant amount of time trying to minimize the overall size of the enclosure. Every millimeter mattered, so I went through multiple iterations, adjusting internal placements and wall thicknesses to shrink the footprint wherever possible. The result is a much more efficient and streamlined case design that better matches the compact 100x100 PCB layout I finalized earlier.


<img width="1170" height="1244" alt="Screenshot 2025-07-19 110511" src="https://github.com/user-attachments/assets/48d8982d-7a95-4221-a3f7-0e7f12cf77bd" />



# July 11th, 2025
Time: 1.5 hours

Today was a big milestone—I officially finished the entire CAD model of the console. With the physical design complete, I shifted focus to what I expected to be the easier part: finding a community-supported emulator for running retro games. After a quick search, I came across RetroPie, which turned out to be exactly what I needed. It supports a wide range of classic consoles and even comes with built-in tools for button configuration, which made the firmware setup much simpler than I anticipated.

I also made progress on the schematic, especially now that my hardware layout is finalized. One challenge I faced was figuring out how to document my plan to solder wires to the underside of the Raspberry Pi Zero 2, since that’s not a standard configuration. To address this, I created a custom visual representation in the schematic to clearly show the solder points and wiring paths. This will help keep everything organized and easier to follow during the assembly phase.
<img width="2304" height="1728" alt="Boost to Pi" src="https://github.com/user-attachments/assets/65bb66a0-6caf-44e8-ba34-505002f7a634" />
<img width="1634" height="1218" alt="Screenshot 2025-07-12 214920" src="https://github.com/user-attachments/assets/3c0f122b-cd40-4c9b-9b4d-94fba6c51f99" />
<img width="2193" height="1222" alt="Screenshot 2025-07-20 155823" src="https://github.com/user-attachments/assets/676ae63e-a5a5-4a8b-a742-446bef8bbc18" />

