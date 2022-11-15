# **_Combining Selectors_**

## **List Selector**

### _repeat same style in multiple elements_

![Alt repeat same font-family](pic/Selection_004.png)

- When a style appears repeatedly in multiple elements, you can use the **list selector**.

### _list selector_

![Alt list selector to replace it](pic/Selection_005.png)

### _chang style for multiple elements at once_

![Alt convenient to change multiple element style](pic/Selection_006.png)

## **Descendant Selector**

### _missing one_

![Alt footer text font-family is different](pic/Selection_007.png)

- You can find that only the footer font on the web page has not been changed.
  - We should wrap its text with element paragraph.

### _fix it with element paragraph_

![Alt fix it with <p>](pic/Selection_008.png)

- But this creates another problem, the text in the footer becomes the same size as the other parts.

### _Descendant selector_

![Alt use descendant selector to limit scope](pic/Selection_009.png)

- We use the **descendant selector** to define the font size specifically for the text in the footer.
  - This concept of selector is based on the **element structure** of html. But this method is prone to problems.

## **Nested Descendant Selector**

### _then, the problem happen..._

![Alt want to italic auther intro](pic/Selection_010.png)

![Alt italic auther text](pic/Selection_011.png)

![Alt add same structure element after it](pic/Selection_012.png)

- The above three images are mainly intended to explain the problems that arise when using the html structure concept of selector.

### _fixtit, but bad method_

![Alt fix it with nested descendant selector](pic/Selection_013.png)

- In the above picture we use the **Nested descendant selector** to solve the problem.
  - However, this is still based on the **html structure of the selector** method, so there is still a chance that the same problem will occur again.
    - We will learn better way in next lecture.
