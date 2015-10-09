# Soffice service

Info : this image is based on openoffice4

## Example with JODConverter

Start the container :
```docker run -d -p 8100:8100 -v `pwd`:`pwd` seguins/soffice```
* ```-v `pwd`:`pwd` ``` : soffice gets the path of the file we want to convert.

Execution of JODConverter : 
```java -jar jodconverter-cli.jar document.doc document.pdf```
