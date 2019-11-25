

Exporting Jupyter notebook in HTML 

1.	Run Jupyter notebook and download the notebook in the browser: File->Download as->HTML and you will get a html page with code and output.
2.	Open the exported HTML with browser and activate the browser console with key F12
3.	Run following command in the console:
```document.querySelectorAll("div.input").forEach(function(a){a.remove()})```
4.	The code removes all input div DOM. Then right mouse button and chose "Save Page As" and Save the "Complete page" (not single page).
5.	You will get a page with an associated folder in windows. Use a trick by zip the html page and then extract to unbind the associated. The folder is useless.
6.	Now it is a single html page without code. You can re-distribute it or print it as PDF.

How do you show GIFs in an IPYNB HTML export?
1.	Run this into the cell HTML('<IMG SRC="thegif.gif">'), where “thegif.gif” is your gif’s file name
2.	Download your Export into HTML, create a new folder, put the HTML and GIF file in together. 
3.	Create a zip file from the folder and attach it to an email. 
4.	Send it over in an email to Person Bob. 
5.	Bob opens the zip file and drags the folder out to the desktop.
6.	Open the folder that Bob has dragged into the desktop then open your HTML. PS – HTML only works in Chromium browsers. 



How do you show Plotly plots in an IPYNB HTML?
1.	Run your code and have the plot displayed in your .ipynb file
2.	Create a new folder, then download your Export into HTML to that new folder. You will see a new folder created within that folder called “nameofyourfile_files”, it has all of the files that you need like your jquery, MathJax, etc..
3.	Create a zip file from the folder and attach it to an email. 
4.	Send it over in an email to Person Bob. 
5.	Bob opens the zip file and drags the folder out to the desktop.
6.	Open the folder that Bob has dragged into the desktop then open your HTML. PS – HTML only works in Chromium browsers. 
