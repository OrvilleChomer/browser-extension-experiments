# Visible Page Element Count Browser Extension

Injects JavaScript code that walks the DOM and counts up the number of visible DOM elements on the page, displays that count, and the total milliseconds it took to do.

The display box has a 'Recalc' button to click to walk the DOM again (in case the page has dynamically changed since the last calculation was done and 
we want to see the new results.

This extension was created to give me a sense of how much time a basic walking of the DOM would take on some complex page and how many visible DOM elements were involved.

In a real application it would do something with each DOM element, but I want to see how much time and elements traversing the DOM would take to start with.
