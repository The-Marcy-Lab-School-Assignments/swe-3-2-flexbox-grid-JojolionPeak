# Short Response Questions

Answer the following questions in 2-4 sentences each. Be specific and use vocabulary from the lessons.

## Question 1: Flexbox Basics

What is the difference between a **flex container** and a **flex item**? How do you make an element a flex container?

A **flex container** is a _parent element_ that will hold the **flex items** to be displayed with formatting. The **flex item** is what you apply _properties_ to in order to _change the layout_ of the webpage. To make an element a flex container, you type `display: flex` in the CSS sheet under the element you want to make a container.

## Question 2: Main Axis vs Cross Axis

In Flexbox, what is the **main axis** and what is the **cross axis**? How do `justify-content` and `align-items` work with these axes?

The **main axis** is the axis that the contents of your webpage will be displayed in from **left to right**, while the **cross axis** is what defines the **vertical orientation** of the elements in a container. `Justify-content` controls how the content is _spaced out on the container's main axis_, while `align-items` will control how the elements are _displayed on the container's cross axis_.

## Question 3: Flexbox vs Grid

When would you use **Flexbox** vs **CSS Grid**? Give an example of a layout that would be better suited for each.

You would use **Flexbox** when you want to display the elements of your webpage with only **_one dimension_**, while a **CSS Grid** can allow you to display your webpage in **_two dimensions, vertically and horizontally_**. You would use **Flexbox** when you want each element to _take up all the allocated space_ of their container, whereas a **CSS Grid** will allow you to have _multiple elements on the same line_, while also displaying your elements _vertically_.

## Question 4: The `fr` Unit

What does the `fr` unit do in CSS Grid? Explain what `grid-template-columns: 1fr 2fr 1fr` would create.

The `fr` unit controls how much **fractional space** an element is using within a container. In a CSS file, `grid-template-columns: 1fr 2fr 1fr` would make **3 columns** and make the _first and last element of that column be the same size_, while making the _second element_ take up **double the space** of the first and last element respectively.

## Question 5: Media Queries

What is a **media query** and why are they important for **responsive web design**? Write an example of a media query that applies styles for screens 768px and wider.

A **media query** allows programmers to make specifications of how the webpage should be styled _based on the size of the screen_ that's viewing the webpage. It's important to use **media queries** because they allow users to still be able to view a webpage **_as intended_**, even if their screen _isn't the same size_ as the programmer's who coded the webpage.

```css
@media (min-width: 768px) {
  img {
    background-color: red;
  }
}
```

## Question 6: Mobile-First Design

What does **mobile-first design** mean? What are the benefits of taking a mobile-first approach versus a desktop-first approach?

Having a **mobile-first design** means to start off by designing a webpage for mobile devices and then utilizing **media queries** to _adjust the layout of the webpage_ to fit larger screens after. It's easier to go back and adjust the properties of elements _based off the sizing of the screen_ rather than having the webpage only display correctly on a desktop.
