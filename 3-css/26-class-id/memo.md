## **HTML Structure Selector from last lecture**

![Alt HTML structure selectors from last lecture](pic/01.png)

## **ID**

![Alt auther](pic/02.png)

## **CLASS**

![Alt copyright](pic/03.png)
![Alt related-author](pic/04.png)
![Alt use class selector](pic/05.png)

## **Multiple selectors effect same element, isn't it conflict?**

![Alt conflict?](pic/06.png)

- The elements on the right are all specified by three different selectors on the left, so won't there be conflicts?
  - This is in fact an important topic for CSS expertise, and there will be a special lecture on this matter.

## **Challenge**

![Alt challenge](pic/07.png)
![Alt solution, but why use class here?](pic/08.png)

- There is only one element ul used in this class, why does the lecturer suggest that we use class instead of id?
  - The main purpose is to prevent the need for future additions of other list elements to take away the dots, assuming that we are using ids, it is necessary to go back and change to class in order to repeat the use, however, this process may cause a lot of problems.
    - So we usually simply always use class, and never use id.
