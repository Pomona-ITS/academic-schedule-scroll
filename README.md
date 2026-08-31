# Academic Schedule Scroll
 
This repository hosts the Academic Schedule Scroll used to display important academic dates and deadlines on campus digital signage. The page is published through GitHub Pages and displayed through Visix.
 
## Repository Contents
 
- `index.html` – Main HTML page containing the academic calendar content, styling, and scrolling animation.
 
## Updating the Schedule
 
To update the displayed dates:
 
1. Open `index.html`.
2. Locate the two `content-block` sections.
3. Update the dates and descriptions in both sections.
4. Confirm that both sections contain identical content.
5. Commit the changes to the `main` branch.
 
The content appears twice in the HTML to create a continuous, seamless scrolling loop. Both copies must remain identical.
 
## Adjusting the Scroll Speed
 
The scroll speed is controlled by the following CSS property:
 
```css
animation: scrollUp 40s linear infinite;
