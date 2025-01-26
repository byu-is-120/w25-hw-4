# HW 4: A CSS Jigsaw Puzzle

## Overview

In this homework, you will recreate a "jigsaw" puzzle using only HTML and CSS. Given a reference image, you will create a grid of rectangles and squares, and position them according to that image. The reference image is provided in the `CSS jigsaw puzzle.pdf` file, or in the description of the assignment on Learning Suite.

The purpose of this assignment is get you good practice with coloring, sizing, and formatting while utilizing the essential CSS properties to do so. Add your CSS styles to the `styles.css` file as your solution. You do not NEED to edit any of the HTML to recreate the image but you MAY do so if you find a better solution for you.

> [!IMPORTANT]
> Do NOT change any styles in the `setup.css` file. This file ensures that the container and its content are displayed correctly.

---

## Requirements

1. **Element Selection**: You will need to use CSS to style the each of the `.box-#` `<div>` elements in the `index.html` file through the `styles.css` file.
2. **Color**: All of the `.box-#` elements should have a background color that reflects the reference image. Two of the boxes have a linear gradient background. You can find the documentation to create a linear gradient [here](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient). If you prefer to manually create the gradient and paste in the generated code, you can use a tool like [this one](https://cssgradient.io/).
3. **Borders**: Some of the boxes have borders. You can find the documentation to create borders [here](https://developer.mozilla.org/en-US/docs/Web/CSS/border). Ensure that each box has the same `border-radius` property value.
4. **Margin & Positioning**: Each of the boxes should be spaced evenly and take up the shown fractional area that is shown in the reference image. You can use `margin`, `padding`, and `position` properties to achieve this.
5. **Hover Effects**: You should provide interactivity to hovering over any *four* of the boxes. You can use any of the following properties to achieve this:
   - Change the background color, opacity, or gradient
   - Change the border color
   - Change the border width
   - Apply a box shadow
   - Change the size of the box (e.g., width, height)
   - Change the transform property (e.g., rotate, scale, translate)
This is up to you, but make sure that the hover effect is noticeable and adds some interactivity to your puzzle. This is a great opportunity to be creative and show your ability to learn new CSS properties. You can find the documentation for the `:hover` pseudo-class [here](https://developer.mozilla.org/en-US/docs/Web/CSS/:hover).

> [!NOTE]
> The `:hover` pseudo-class is just one of multiple pseudo-classes that we are going to learn this semester. This assignment is a great opportunity to learn the *low-hanging fruit* of pseudo-classes on your own.

---

## Submission

Once you have completed the assignment, you should `add`, `commit`, and `push` your changes to your provided GitHub repository. Then, submit the link to your repository in the submission box on Learning Suite. The last `commit` before the deadline will be the version that is graded

You may you reach out to the TA or instructor to request them to grade another version (while taking the late penalty) if you believe more time will grant you a higher grade.

---

## Tips

1. There are multiple style properties that each box may need to inherit, so I've provided a general "box" class to each individual div.
2. It may be easiest to set the position of all the boxes to absolute and pixel count. You may want to start from there.
3. It's easier to pixel count with `box-sizing: border-box;` property to make it easier to size your boxes.
4. You can also use `display: inline-block;` to position your boxes, if you prefer.
5. Remember that there are multiple solutions to this, you just should do what makes the most sense to you.
