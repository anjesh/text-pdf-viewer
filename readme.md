# Text and PDF Comparer

This is a very crude implementation of text and PDF viewer so that they could be compared side by side - after text extraction from the pdf. It uses quill.js for the editor and pdf.js for the PDF viewer. 

Data should be present in the data folder with text files inside text folder and pdfs in the pages folder.

To add your own data

* Have the files in the following format 1.txt, 2.txt for text files and 1.pdf, 2.pdf for each page. 
* Change the totalPages and file folder name in the code

```javascript
var totalPages = 21;
var fileFoler = "in";
```

## TODOs

* Stylesheet 
* Create module for handling the view
* Add saving functionality
