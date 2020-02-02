# PDF.js
PDF.js library redeveloped for thsconline. 

There are two versions of viewer.js:

* The `viewer_custom.js` is modified specifically to handle base-64 data on a particular variable. How this is actually can be deployed is using server-side (in this case Google App Script) to pull the file from ther web and then stores the data temporarilty. (The script clears the variable once it has been passed into the PDFApplication)

* The `viewer_external.js` is a standard PDF.js file, can be used to handle PDF files hosted on thsconline.github.io itself.

* The stylesheet has been modified to a blue theme, reflecting style choices made on the main `thsconline/s/` repo.
