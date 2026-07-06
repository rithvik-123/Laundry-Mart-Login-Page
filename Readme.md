# Task 6: CSS Login Page (Flexbox)

**Author:** D P Rithvik Kumar

## Description & Learning Process
This project is a split-layout login page for Laundry Mart. My main goal was to practice using CSS Flexbox for layout control. 

Initially, I struggled to get the main card centered on the screen, but I learned that wrapping it in a `body` tag set to `display: flex; justify-content: center; align-items: center;` does all the math automatically. Inside the container, using `flex: 1` on both the left and right sections made it really easy to split the screen perfectly in half without relying on inline-blocks or float properties.

I also made sure to implement the feedback I received on Task 2 by wrapping my inputs in a semantic `<form>` element instead of a `<div>`, and I added a hover effect to the login button so it feels more interactive.

## How to Run
1. Download and unzip the project folder.
2. Make sure `index.html` and `index.css` are saved in the same directory.
3. Open `index.html` in any web browser (like Chrome or Edge) to view the page.
4. Hover over the "Login" button to view the CSS transition effect.
