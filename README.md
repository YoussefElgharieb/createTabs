# trimInsideCircleRoutine

## What the project does?
trims inside a selection of circles

## current limitation
this routine was created for a specific task thus there are the following limitation for general use.

1. the rountine expects only circles in the the selection
2. objects must pass through the centre of the circles.
  - How to modify this limitation?
    - change `0.075` lines 10,12,15,16_
      1.  to any value smaller than the radius of the smallest circle in the selection 
      2.  to the radius of the _i<sup>th</sup>_ circle in the selection



## motivation & use
**Creating tabs** is a setp in the process of preping CAD files for cutting on the laser machine. 

Tabs are created as follows:

Where for each object inside a circle in a layer of circles ,of diameter equal to the needed tab, placed concidentaly where the tabs are need; is trimmed. 
This task was highly time consuming for some files have hundreds of tabs. Thus, I have wrote this routine to automate this task.
