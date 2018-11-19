# Spring Boot Resume Parser Application

	This app would process employee's details and processes it and shows as form ouput in the result page. 
	Upload the CV / Resume in word format and conversion of word to pdf happens in the back-end and copies the new pdf file to System.temp directory and shows the pdf file with print/download options in the result page. 
	Apache POI apis are used for word to pdf conversion.

# Requirements

	For building and running the application you need:
	- JDK 1.10
	- Maven 3

# Instructions to run this app on localhost
	
	There are several ways to run a Spring Boot application on your local machine. One way is to execute the main method in the com.test.cvprocessor.SpringBootWebApplication class from your IDE. Alternatively you can use the Spring Boot Maven plugin like so:
mvn spring-boot:run