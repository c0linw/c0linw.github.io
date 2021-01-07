# About Me

Third year BSc student at University of British Columbia, majoring in Computer Science.

---

## Personal Projects

### 3D Rhythm Game Prototype (2020-2021)
Early stage of a touchscreen rhythm game project that uses a perspective-skewed “note highway” to display scrolling notes in a similar fashion to games such as Guitar Hero. Notes are stored in JSON, with a beat-relative format for more intuitive musical understanding. 
Development of the project has a strong focus towards elements that make a good rhythm game engine, including millisecond-precise audio sync, framerate-independent gameplay, and an easily extendable note storage format.
Current status: Note renderer complete, currently investigating a solution for framerate-independent input timing precision.
  <iframe width="560" height="315" src="https://www.youtube.com/embed/9o4hZQ7glgA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/>
### BMSdori (2019)
A fork of the iBMSC BMS editor written in Visual Basic, modified to render note types according to mobile rhythm game *BanG Dream! Girls Band Party!*  
Most notably, "slide" notes do not exist in most tradition BMS format games. This version of the editor render slide notes, which connect notes of the same slide type between lanes, while long notes pair to the next long note within its own lane only.  
With a little asset manipulation through tools like UABE and Unity AssetStudio, custom charts can be played in-game.  
  <iframe width="560" height="315" src="https://www.youtube.com/embed/0eTcIp8PGuo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br/><br/>
---


## Academic Projects

### Locally Invariant Feature Matching (2019)
Written in Python. Given a pre-computed set of locally invariant keypoints and descriptors for an image, keypoints are matched between two images.  
Noise and outliers are reduced by first eliminating matches that have significantly different angles from the mean, then performing random sample consensus to narrow matches down to a group in which lines are closest to the mean.
![Local Invariant Matching](c0linw.github.io/assets/localinvariant.PNG)

<br/>
### Texture Synthesis (2019)
A Python implementation of the Efros-Leung texture synthesis method. Select a region from which to sample the texture, and a region over which the texture will be synthesized, and a statistically similar texture will be generated.  
![Texture synthesis region selection](c0linw.github.io/assets/polyselect-paradoxium.png)
![Texture synthesis result](c0linw.github.io/assets/paradoxium-result.PNG)

<br/>
### Template Matching (2019)
Basic template matching techniques implemented in Python. The template image is tested at different scales, calculating correlation over each pixel and marking each pixel that correlates strongly enough to meet a threshold. Boxes centred around the marked pixels are then drawn based on the sizes of the matching templates.
![Template matching](c0linw.github.io/assets/students-result.PNG)

<br/>
### Color Filler (2018)
A program written in C++ that fills pixels in an image with a given pattern, continuing until it reaches a pixel that exceeds a threshold of color difference. It was implemented with different algorithms that determine the order in which pixels are filled. Below are examples of color filling implemented via breadth-first search (BFS) and depth-first search (DFS), respectively.
![BFS Fill](c0linw.github.io/assets/colorfill-bfs.gif)
![DFS Fill](c0linw.github.io/assets/colorfill-dfs.gif)

<br/>
### BusesAreUs (2018)
An Android application written in Java that displays buses, routes, and stops on a map, and gives information on arriving buses for a specific stop when clicked. Students were responsible for writing code to parse data from the Translink API, then using the parsed data to display icons accurately over the map. Students also needed to display the nearest stop based on current GPS data from the device and ensure stops were clustered into a single icon at larger scales where too many icons would be rendered otherwise.
![BusesAreUs map](c0linw.github.io/assets/busesareus-map.png)
![BusesAreUs routes](c0linw.github.io/assets/busesareus-line.png)
![BusesAreUs arrivals](c0linw.github.io/assets/busesareus-stopinfo.png)

<br/><br/>
---
