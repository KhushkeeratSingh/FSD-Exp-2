# Experiment Submission – FSD-1 Exp-2

## 1. Personal Information
- Name: Khushkeerat Singh 
- UID: 24BCY70101
- Group: 24BCY-1 (B)

---
## 2. Title of the Experiment
- To implement a live character counter that updates as users type in a text area. 
- To create a dynamic product filter that sorts items based on dropdown selection
- To build an interactive SVG drawing tool with mouse event handlers.
---
## 3. Defined Approach
The experiment was divided into three mini-tasks, each focusing on a specific interactive feature using HTML, CSS, and JavaScript.
### Word Counter
- For the live character counter, a textarea and a display element were created in HTML. JavaScript listened to the input event on the textarea and, on every change, calculated the length of the text and updated the displayed count. When the text neared or exceeded a defined limit, CSS classes were toggled to change the counter’s appearance and clearly indicate the status to the user.
### Product Filter
- For the dynamic product filter, products were displayed as HTML cards with details such as name, price, and category. A dropdown was added to select filter or sort options. Each product carried identifying data (like category or price), and JavaScript responded to dropdown changes by filtering or reordering the product elements and updating their visibility in the DOM.
### SVG Drawing Tool
- For the interactive SVG drawing tool, an SVG element acted as the drawing canvas. JavaScript handled mousedown, mousemove, and mouseup events on the SVG to start, update, and end drawing actions. As the user dragged the mouse, new SVG shapes were created and their coordinates were updated in real time, allowing freeform drawing. A clear option was also provided to remove all drawn elements from the canvas.

---
## 4. Output / Result
- The live character counter successfully updates in real time as the user types, correctly displaying the current character count and visually warning when limits are approached or exceeded.
- The dynamic product filter correctly filters and/or sorts the product list based on the selected dropdown option, instantly updating the visible items on the page.
- The interactive SVG drawing tool allows users to draw directly on the SVG canvas using mouse actions, with the ability to create shapes and clear the drawing area as needed.

---
## 5. Learning Outcome
- Understood how to use DOM events such as input, change, mousedown, mousemove, and mouseup to create real-time, interactive behavior in web pages.
- Gained confidence in manipulating the DOM by updating text, changing styles, showing/hiding elements, and dynamically creating SVG elements.
- Learned to structure and process data (like product details) for filtering and sorting using JavaScript logic and array methods.
- Developed familiarity with SVG and its coordinate system for implementing basic drawing functionality in the browser.
- Improved understanding of state management in the frontend (for example, tracking whether the user is currently drawing or which filter is active).
- Strengthened the ability to integrate HTML, CSS, and JavaScript to build responsive, user-friendly interfaces with clear visual feedback.

---
## 6. Conclusion
- A live character counter that demonstrated real-time DOM updates and input validation.
- A dynamic product filter that showcased filtering, sorting, and UI updates based on user-selected criteria.
- An interactive SVG drawing tool that applied event-driven programming to create a visual, graphics-based interface.
- Together, these tasks strengthened skills in JavaScript event handling, DOM manipulation, SVG graphics, and designing user-friendly interactive components for modern web applications.

---
