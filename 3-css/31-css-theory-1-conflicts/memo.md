## **Concept**

### _Multiple selectors point to the same element_

![Alt concept 1](pic/01.jpg)

### _Priority of conflict property_

![Alt concept 2](pic/02.jpg)

- Avoid using No.5 and No.4 as much as possible.

- This priority only works if there is a conflict, basically all styling to the element will be applied if there is no conflict.

## **Examples**

### _Footer: various kind of selectors_

![Alt footer example: various kind of selectors](pic/03.jpg)

![Alt footer example](pic/04.jpg)

### _h1 example: same kind of selectors_

![Alt h1 example: last one](pic/05.jpg)

- The conflict is for a single property, not the entire selector.

### _anchor example: psuedo-calss & !important_

![Alt anchor example: psuedo-class](pic/06.jpg)

![Alt anchor example: !important](pic/07.jpg)

- Only use it if you are completely confused about why it is so styling...
  - We need to simplify CSS styling codes as much as possible
    - Fewer nests
    - Fewer ID selectors
