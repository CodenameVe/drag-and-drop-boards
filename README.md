This was a small project built with HTML, CSS, and JS to create a simple Kanban Board. Here are some of the 
things i learned or practiced while working on the project:


HTML:
- Practiced using divs as containers for each section.
- each section title made with an UL and LI for the title/ column
- after the column I used another div for the list of items. For this element we made use of the ondrop, ondragover, and ondrageneter
- After the content I added a button group comprised of a div in order to create the Add and Same item buttons
- made use of inline JS using onclick events for the buttons
- Repeated these elements for each of the 4 sections


CSS: 
- Utilized CSS variables to apply title colors for each column
- Implemented a custom scrollbar from W3schools
- Added stylings for drag items, drop items, button group and individual buttons
- also utilized media query for both smartphones and laptops for responsive utulity.



JS:
- Const variables to target HTML elements with querySelector and getElementByID
- Let variables for dynamic gloabl variables
- function for targeting local storage  with already existing task items, or providing defaults if not present
- function to set local storage arrays utilizing forEach to target each section, then localStorage.SetItem to populate.
- Added function for creating list items while adding class, Attributes, and appending. Passing in the content as a parameter
- Function to updateDOM and filter the arrays as well as update local storage
- Functionality for adding and deleting items with respective buttons as well as show/hide areas based on current action
- Rebuild Array function to update and reflect drag and dropped items using Array.from to turn variable into arrays
- Added functions for drag n drop functionality, utilizing event.preventDefault() method



Overall this was a fun project to follow along to. I learned some very useful techniques/ practices. Main feature of this project
being drag n drop functionality. I still need to practice this to fully understand it, but I'm glad to have taken this one
