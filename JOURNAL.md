---
title: "CyberCard"
author: "Nathan Alspaugh (NotARoomba)"
description: "A Cyberpunk themed hacker card!"
created_at: "2025-07-29"
time_spent: ~5 Hours
---

# July 29: Schematic and PCB Layout

I wanted to make a cool hackercard before highway ends so I started up a new project and followed a guide on making an NFC Card. I followed the [guide](https://jams.hackclub.com/jam/hacker-card) and added the components from LCSC using a script I made. After importing the components, I wired them up and then sent them over to the PCB. In the PCB I wanted the strip to be on the side like a normal card and have the components as non visible as possible so I grouped them together (except for the led).

![Schematic Design](assets/schematic.png)

![PCB Layout Start](assets/pcb_start.png)

**Time Spent:** 1 Hours

# July 30: Art and Design

After wiring it up I went over to figma and created a new design to modify the artwork that I wanted to place. I ended up taking an image of David and Lucy on the moon from the Edgerunners series. I then added a cool wallpaper to the front along with the symbol on David's jacket. It was a pain to create masks and then find out that the images in svg black and white didn't look good so I had to create many revisions. I also wanted some cool PCB/trace lines/design so I created some "traces" and "planes" in figma before exporting to Kicad. After creating the images, I then imported them into Kicad and added them into the different layers, I wanted David's jacket to have the color of the copper so I added it to tha mask layer and the copper layer.

![Figma Design Process](assets/figma.png)

After that I added some text and then called it a day. This was the end result.

![PCB Design](assets/pcb_final.png)

**Time Spent:** 4 Hours

# August 14: Recieved Cards and Flashing

After recieving the cards I flashed them with `A2:03:E1:10:6D:00,A2:04:03:04:D8:00,A2:05:00:00:FE:00` and then was able to use them!

![Final Card](assets/cybercard_finished.jpg)
