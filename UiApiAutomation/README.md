API Automation Framework built using Rest Assured, Java 8 , Maven, Test NG , AssertJ , Lombok ,JAVA faker , Jackson binding .
Frame work support :
1.	Design pattern used : Builder design pattern ( for Post and PUT request ) and it also support the predefined user input data like JSON file and make changes on the same is also taken care in ApiUtilClass .
2.	Each response of the API will be stored in the OUTPUT folder .
3.	Configuration file will be shared both by API and UI classes .
4.	Response of the each Post request will be shared by GET and PUT APIS using DataStore class .
5.	Faker API is used for uniquely creating data for each test . Assumption:
6.	Always run the Create Booking and then GET that booking . (Create bookingid will be input for the GET booking)

Note : Update and delete cannot be run because of the Token is not generated.( Username password is not working )


How to run the Test :
1.	Install java 8 installed and set JAVA_HOME
2.	Set Maven_home
3.	Check out the code .
4.	Go to the terminal run maven install or mvn clean install test -DsuiteXmlFile="testng.xml"
UI Automation Framework built using Rest Assured, Java 8 , Maven, Test NG , AssertJ , Lombok ,JAVA faker
Frame work support : Design pattern used :
1.	Factory design pattern (Browser support , Currently support CHORME(106) and firefox (104) it can be extended any number of Browsers )
2.	Page objects in fluent style
3.	Configuration file will be shared both by API and UI classes . How to run the Test :
4.	Install java 8 installed and set JAVA_HOME
5.	Set Maven_home
6.	Check out the code .
7.	Go to the terminal run maven install or mvn clean install test -DsuiteXmlFile="testng.xml"

