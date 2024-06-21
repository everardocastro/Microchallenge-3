# Microchallenge III 



![still](https://hackmd.io/_uploads/rJ5O3zmIC.jpg)

## Concept

To modify existent visuals with sensors in a two persons interactive dance expirience 

## Execution

**1-Planning:**

monday - tuesday: Learn Jitter
Wensday: Work on jitter and teach Wekinator
Thuersday: Assemble

**2-Learning:** 

As we didn't have any experience with sensors or visuals, part of our time was invested in exploring the software Max8 specifically the function of Jitter. We had to watch a lot of tutorials to learn what we could do within the time span and how to assemble the structure of the interaction inside the program.

**Hacking our phones to read Sensors.**

Once we could choose the variables and teach the weakinator, we asked Citlali about the detect body movements to use them as inputs. She mentioned that developing sensors from scratch demands time and sometimes they can not be as accurate as expected. For the time frame we had she suggested to use the sensors our phones already have.

To be able to access the sensors we had to download SIG ZIM (ios) and F- Droid App (android), an application that allows you to obtain the data from the different sensors in your phone. In this case we wanted to obtain the data form the gyroscope or accelerometer.

We had to conduct many trials with combinations of arm movements/arm positions and the type of sensor for the Wekinator to work properly. This took more time than we expected, as we had to figure out three arm movements, determine the best sensor for achieving three different results, and train it many times in the Wekinator



**Main links we use to learn Jitter** 

[Learing Jitter with visuals I](https://www.youtube.com/watch?v=Rn1nImut6Pk )  

[Learing Jitter with visuals II](https://www.youtube.com/watch?v=eSARE8zdtVY&t=2086s )  

[Creating shapes and grids](ttps://www.youtube.com/watch?v=uzQOiwMkESU&t=345s)  

[Helpful objects I](thttps://www.youtube.com/watch?v=yUr4KqBSvP4&t=770s)  

[Helpful objects II](https://www.youtube.com/watch?v=ckp1GSROJIY)  


**3-Prototyping:** 





# Fabrication
## System Diagram
![diagram](https://hackmd.io/_uploads/HJ4yNG7IC.jpg)

## BOM (Build of Materials)


| Part |  |
| -------- | -------- | 
| Cellphone(x2)     |  F- Droid App (android) SIGZIM (ios) to send the sensor information to Wekinator     | 
| Tights    |To attach the cellphone to the arms 






## Inputs
1- Body movements to Wekinator detected through Gravitational sensor 
2- Phone 1: Wekinator data to Max8 (works as commands to trigger functions)
3- Phone 2: Gravitational sensor directly to Max8 (works as regulator of the form)

![body machine](https://hackmd.io/_uploads/B1vTb7m8R.jpg)

## Output (Max8)

1- Phone 1: triggers shape's polyfaces, color, and noise.
2- Phone 2: modifies values of each command.
**Interactive wireframe shape that reacts to body movements, changing its color, number of faces, and noise value.**

![max8](https://hackmd.io/_uploads/SyA4W2ZIR.png)

**Shape generation:**

![shape](https://hackmd.io/_uploads/r15NPmQLA.png)

**Shape's attributes:**

This section controls the shape's numeber of sides, noise quantity and color.
![shape's attributes](https://hackmd.io/_uploads/HJ8K_77IA.png)

**Data receiver and conditional functions:**

This section recieves the data from wekinator (phone 1) and the phone 2. To be able to trigger the commands that control de shape's attributes, it was necessary to use conditionant functions that trigger them when the data is equal to certain value (1,2 or 3).

![receive and conditions](https://hackmd.io/_uploads/BynsdXX80.png)

## Reflect about future development opportunity
### Learning through creating
While working on the project, the conversations about the future revolved around evolving the project so that you can draw and modify the geometry in a smoother way while still having a dance experience.


## Our page links


[Francisca's web page](https://panchipunchi.github.io/MDEF-Francisca/)  

[Everardo's web page](https://everardocastro.github.io/mdef1/)  



