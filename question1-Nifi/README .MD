This application uses Apache Nifi to convert CSV to JSON.
1-you must first get the xml file up and running, then use docker-compose up to execute all images.
2- nifi is now available on local port 8080 in the browser >> 3- Choose "upload template" to upload the template "Test_Nifi" at localhost:8080/nifi/ >>
drag and drop templete >> select "Test_Nifi" templete >> ADD 
4- Begin the work flow from the left side of the window's operate.
5- Your CSV (get csv folder) file will then be converted to a JSON file (set Json folder)