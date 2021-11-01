# Belly Button Biodiversity

This week's project is related with a study of the biodiversity of bacteria in the navel of a person. The idea behind this study is to find some specific bacterias that could  be used in the process of syntetizing beef. The findings of the study are organized as plots that are shown in an interactive website.

## Overview:

The website is interactively designed such that the user could choose from a drop-down menu a number that identifies a  specific subject. Then, the study results for the chosen subject are shown in three plots at the same time. The plots are:

 - Bar chart: Display at a time, the ten top bacterias that have been found in a specif subject.
 - Bubble chart: All the bacterias found in the same specific subject.
 - Gauge chart:  Shows the belly button washing frequency for each subject.

Each time the user choose a diferent number in the drop-down menu, the plots are updated to display the results for the new subject.

### Results-Layout:

Before to talk about the design of the website, we need the data used for creating the plots that are shown in the webpage.  This data is in `samples.json`.  For the design of the site, we use JavaScript & HTML. The file `charts.js` has the logic and code that captures from the user the event, i.e. what subject is chosen from the drop-down menu, and creates the three plots corresponding to the specific subject chosen by the user. The below figure shows the drop-down menu with the available options.

<img width="40%" src="https://raw.githubusercontent.com/LeidyDoradoM/Plotly_Challenge/main/Images/drop-downMenu.png">

Drop-down Menu for choosing a subject.

### Web-Styling

The main template for our website is bootstrap.  The `index.html` and `style.css` files are used for the design of the website. The basic bootstrap template is styled as it is described below:

1. A specific image is used as the Bootstrap header.

2. The background color of the site was change from white to light-purple.

3. The font-size and color of the bootstrap header and the two containers are changed.

4. In addition, the website is device responsive. 


![](https://raw.githubusercontent.com/LeidyDoradoM/Plotly_Challenge/main/Images/websiteOverview.png)

Overview of the Website.