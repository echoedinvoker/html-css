## **1st li element style with old stupy way**

![Alt purpose: 1st li](pic/01.jpg)

![Alt set classes to all 1st li](pic/02.jpg)

![Alt set bold style in .css](pic/03.jpg)

![Alt result](pic/04.jpg)

## **1st li element style with psuedo class**

![Alt use psuedo class to do same work](pic/05.jpg)

## **other psuedo class**

### _last-child_

![Alt :last-child](pic/06.jpg)

![Alt result](pic/07.jpg)

- We can find that we don't need to set the class in HTML at all, we can directly use the psuedo class to catch the element we want, it save lots of time.

### _nth-child_

![Alt :nth-child with number](pic/08.jpg)

![Alt result](pic/09.jpg)

### _nth-child with keyword_

![Alt :nth-child with keyword](pic/10.jpg)

![Alt result](pic/11.jpg)

- This is a very good function, often seen in the form many people use it.

## **misunderstand about usage of psuedo class**

> Here are the parts that most people misuse when using the previous psuedo classes.

![Alt purpose: 1st p in article](pic/12.jpg)

![Alt straitforward think](pic/13.jpg)

![Alt result: not work](pic/14.jpg)

![Alt analyze reason](pic/15.jpg)

![Alt add 1st elememt and its p](pic/16.jpg)

## **concern of psuedo class above**

![Alt result, and concern thing](pic/17.jpg)

- The above psuedo class of \*-child type is only suitable for use in cases where the child element type is very simple.
  - Because the selector is defined using the HTML structure, it is easy to cause bugs if there are various child element types.
