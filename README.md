# PDF.js
PDF.js library redeveloped for thsconline. 

There are two versions of viewer.js:

* The `viewer_custom.js` is modified specifically to handle base-64 data on a particular variable. It behaves kind of like a browser within a browser. A Google App Script is used to pass the data from the web into the PDF viewer / browser application.

* The `viewer_external.js` is a standard PDF.js file, can be used to handle PDF files hosted on thsconline.github.io itself.

* The stylesheet has been modified to a blue theme, reflecting style choices made on the main `thsconline/s/` repo.
