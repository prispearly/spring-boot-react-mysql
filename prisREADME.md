FE:
npm start
http://localhost:8081/ 

BE:
open -e ~/.bash_profile 
source .bash_profile
mvn -v
mvn clean install -Dmaven.test.failure.ignore=true
mvn spring-boot:run