# IHME_GBD_TEST_PROJECT
IHME D3 Visualization Test Project

This project was part of a coding exercise for the Institute for Health Metrics and Evaluation (IHME).

The visuaiization compares male mean obesity rates for all countries (in the data set) for the years 1990 to 2013.  

The visualizaiton is a donut chart with the inner most ring representing the data for all of the countries for the year 1990. 
Each successive ring represent the next year's data with 2013 at the outermost ring.  The user can look along each wedge from the center 
to the outmost ring and see how each country's obesity rates for males have changed over time.  The color scheme goes from blue through a grey at the mean value out to an orange/red for the max value for any particular age range. There are 17 color values although each bin is not the same size.  The bins on either side of the mean are same size.  It looks very much like a color wheel allowing the user to find outliers as well as seing how each country has changed over time. (look along a wedge at any particular angle). 

Other notes:  
A tooltip is provided for each wedge for each year so the user can see the value for any particular year for any particular 
country.
Pan and zoom are available although they are not particularly well tested and can be glitchy. 
Zoom uses the mouse wheel and pan is a click and drag motion.
The drop-down control allows the user to pick another age group for visualization. The visualization will update automatically.


Demo:http://bladekaj.github.io/IHME_GBD_TEST_PROJECT/WebContent/index.html 
