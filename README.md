# weather-app
This App is used to integrate the Openweather app with spring and html code


Prerequistes :-

1) Before we need to start the app , we need to signup for https://openweathermap.org .
2) Once above step is done , we  will get API key to our email id, where we can use after 2 hours 
3) Install Java , eclipse and maven versions in your system


Steps to run the code :-

1) Install latest eclipse and  install maven plugin as it is maven based project

2) Dowload the source code and import to "eclipse using import existing maven projects"

Note point:-  a) we need to set jdk path to the project if it is a fresh eclipse
              b) At application-prod.properties we need to update the API key given by openweather app 

3) Right click the project and please clean the with maven

4) Right click the project and please run  spring-boot:run 

5) At this state application will run successfully and it will start app with default tomcat running on 8080 port .

6) Login to browser and please give http://localhost:8080/weather_search.html and enter desired city you want to check temperature

7) Will be able to see the results of that city 




