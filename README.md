*** Recommended to perform below commands as a ROOT user ***
----------------------------------------------------------------------------------------------


1. Execute the application locally and access it using your browser

git clone https://github.com/Pavan-1997/JAVA_SPRINGBOOT_LOCAL_BUILD.git

cd JAVA_SPRINTBOOT_LOCAL_BUILD/spring-boot-app


2. Install and Execute the Maven targets to generate the artifacts

sudo apt install maven

mvn clean package


3. Execute locally (Java 11 needed) and access the application on http://localhost:8080

java -jar target/spring-boot-web.jar
