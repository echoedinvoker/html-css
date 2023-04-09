## **Goal and prepare**

![Alt goal and prepare](pic/01.jpg)

![Alt don't need extra container](pic/02.jpg)

- grid layout is two-dimensional, so we can include all blocks in it, so there is no need to generate additional containers.

## **Set Grid**

![Alt set grid container and needs](pic/03.jpg)

![Alt let header and footer occupy whole rows](pic/04.jpg)

## **Remove unwanted margin-bottoms**

> Because the previous flexbox layout only provides one dimension, it cannot contain all blocks, so you still need to rely on margin to create the space between the flexbox container and the neighboring blocks.

![Alt remove margin-bottom of header](pic/05.jpg)

![Alt remove margin-bottom of article](pic/06.jpg)

## **Remove unwanted stretch of Aside**

![Alt unwanted stretch of aside](pic/07.jpg)

![Alt set align-item to start](pic/08.jpg)

- Because it adjusts the position of the grid item in the grid cell, align-item is used instead of align-content.

## **Final result**

![Alt final result](pic/09.jpg)

- Previously we used flexbox to do the layout, so the space between the flexbox container and the header and footer still relied on margin-bottom to create space.
  - This time we use grid layout which contains all blocks at once, so we don't need to rely on margin to generate space.
