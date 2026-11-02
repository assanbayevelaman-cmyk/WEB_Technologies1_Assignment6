# WEB_Technologies1_Assignment6

**Name:** Assanbayev Yelaman  
**Group:** SE-2538

## Part 1. Getting Started with jQuery

### Task 0. Setup

Included jQuery from a CDN and wrote a $(document).ready(function() { ... }) function. I tested it by printing "jQuery is ready!" in the console.

### Task 1. Selectors & CSS

Displayed my name, a personal headline, a short introduction, and a profile section with a title "Welcome to My Portfolio.". I used tag, ID, and class selectors to select different HTML elements and used `.css()` to change the styling of selected elements. I also dynamically updated my headline using `.html()` and added buttons to switch between light and dark themes.

## Part 2. jQuery Effects

### Task 2. Visibility Methods

Created an "About Me" section and added a short biography, a current status message, and a list of my interests. I added three buttons: Hide, Show, and Toggle. I used them to control the visibility of my status message.

### Task 3. Fade Methods

Displayed two travel photos and used `.fadeIn()`, `.fadeOut()`, and `.fadeToggle()` effects to control the visibility of the photos.

### Task 4. Slide Methods

Created three clickable headings and placed related information inside a collapsible panel beneath each heading. I used `.slideUp()`, `.slideDown()`, and `.slideToggle()` to make the interaction smooth.

## Part 3. DOM Manipulation with jQuery

### Task 5. Add & Remove Elements

Displayed an initial list containing four technical skills and added a text input where visitors can enter a new skill. I created three buttons: "Add Skill", "Prepend Skill", and "Remove Skill". I used `.append()`, `.prepend()`, and `.remove()` to make the buttons function and also added validation for empty input field.

### Task 6. Modifying Attributes

Added a social media link and created a button that dynamically changes the link's destination using `.attr()`.

### Task 7. Form Interaction

Created a form with inputs for Name and Email. I used `.val()` and `.text()` to display the user's input live below the form.

## Part 4. Animations

### Task 8. Basic Animation

Extended Task 5 by creating a visual representation of three technical skills using skill bars that initially have zero width. Different skill levels use different target widths. I added an "Animate My Skills" button that uses jQuery's `.animate()` method when clicked to increase the width of each skill bar. When the button is clicked again, the skill bars animate back to zero width.

## Summary

Included jQuery from a CDN. Used it to change the styling of selected elements. Used jQuery effects methods like visibility, fade, and slide methods. Used jQuery for DOM Manipulation like adding and removing elements, modifying attributes, and displaying the user's input live. jQuery's `.animate()` was used to add animated skill bars that represent different skill levels of different technical skills.
