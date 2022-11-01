# **_Three Places of CSS_**

## **Inline Style**

![Alt inline](pic/bandicam%202022-11-01%2023-59-15-613.jpg)

- Never use it!
- But sometimes we see people using it in this way, and we still need to understand it.

## **Internal Style**

![Alt internal](pic/bandicam%202022-11-02%2000-00-51-121.jpg)

- Although the style has been successfully separated from the main part of our html content, if the CSS has 500 styles (which is not uncommon), this approach is still impractical.

## **External Style**

![Alt external](pic/bandicam%202022-11-02%2000-03-45-940.jpg)

- Put the CSS codes completely in another file.
  - This is the way we should use, but if you just need to make a small page quickly, you are still allowed to use the internal way.
- You can see that the style on the page is not yet up, because now the html and css are divided into different files, so you still need to make a **link**.

![Alt link](pic/bandicam%202022-11-02%2000-04-22-601.jpg)

- element **link** is the element that specifically links html and css.
