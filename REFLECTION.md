# Reflection

## What part of the code was most confusing and why?

The most confusing part of the code was understanding how `setInterval()` and `clearInterval()` work together. At first, I thought the code inside `setInterval()` only ran one time. I learned that `setInterval()` repeatedly runs the code after a specific amount of time, which is why the animation keeps changing every 500 milliseconds. The `clearInterval()` function is needed to stop the loop when the animation reaches the maximum number of cycles.

## How does the animation help visualize asynchronous behavior?

The animation helps visualize asynchronous behavior because the browser repeatedly updates the page over time instead of stopping the entire program. The `setInterval()` function schedules the animation code to run every 500 milliseconds. This makes it easier to see how asynchronous operations can happen while the webpage continues responding.

## What did you change or improve, and what effect did it have?

I added a feature that changes the background color as the animation progresses. This made the animation more visually interesting and helped show that JavaScript was actively updating the webpage. I also added comments explaining the variables, DOM elements, `setInterval()`, and `clearInterval()`. These changes helped me better understand how JavaScript can dynamically modify the DOM during an asynchronous loop.