# Description #

This reproduces a performance regression with Chrome 51.0.2704.84.  When we have a PrimeFaces p:editor inside of a p:dialog, and we put an image into the p:editor using a data URI, it takes a very long time for the dialog to become visible.

# Usage #

* Execute command: `mvn tomcat7:run`
* Visit [http://localhost:8080/](http://localhost:8080/)
* Click "Click Me" button
