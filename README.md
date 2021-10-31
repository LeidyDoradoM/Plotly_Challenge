# Belly Button Biodiversity 

This week's project is all about plotting and designing a website that shows findings and insights about the bacteria world inside of our belly buttons.

## Overview:

The website shows three different plots:

 - Bar chart: Display at a time, the ten top bacterias that have been found in a specif subject.
 - Bubble chart: All the bacterias found in the same specific subject.
 - Gauge chart:  Shows the belly button washing frequency for each subject.

In addition, the web site is interactive such that the user could choose from a drop-menu a specific subject and each one of the plot-charts are updated with the information corresponding to the subject chosen.

### Results-Layout:

Before to talk about the design of the website, we need the data used for creating the plots that are shown in the webpage.  This data is in `samples.json`.  For the design of the site, we use JavaScript & HTML. The file `charts.js` has the logic and code that captures from the user the event, i.e. what subject is chosen from the drop-menu, and creates the three plots corresponding to the specific subject chosen by the user. The below figure shows the drop-menu with all the available options.


### Web-Styling:

The main template for our website is bootstrap.  The `index.html` and `style.css` files are used for the design of the website. The basic bootstrap template is styled as it is described below:

1. A specific image is used as the Bootstrap header.

2. The background color of the site was change from white to light-purple.

3. The font-size and color of the bootstrap header and two containers are changed.

4. In addition, the website is device responsive 