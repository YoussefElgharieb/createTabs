# trimInsideCircleRoutine

## What the project does?
AutoLISP routine that trims inside a selection of circles

## motivation & usage
***Creating tabs*** is a setp in the process of preping CAD files for cutting on the laser machine. 

Tabs are created as follows:

Where for each object inside a circle in a layer of circles ,of diameter equal to the needed tab, placed coincidentally where the tabs are need; is trimmed. 
This task was highly time consuming for some files have hundreds of tabs. Thus, I have wrote this routine to automate this task.



## limitations
This routine was created to automate a specific use case of ***creating tabs*** as effiently as possible. Thus, there are the following limitations for geTeral use.

1. the rountine expects only circles in the the selection
  - How to modify this limitation?
    - filter the selection to include only circles before itirirating on the selection.

2. objects must pass through the centre of the circles.
  - How to modify this limitation?
    - change `0.075` lines 11,12,15,16_
      1.  to any value smaller than the radius of the smallest circle in the selection 
      2.  to the radius of the _i<sup>th</sup>_ circle in the selection
     

## Contact
Youssef Elgharieb - youssef.elgharieb.github@gmail.com
