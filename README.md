# fastfood
### fast food application project using micro-services

This web-app is helpful to display various services, food items offered at each branch separately where Admins can add,edit and remove the food items for their specific branches and Customers can search,sort & filter the food items and order the food online & track the placed orders.

This is a Full-Stack Web Project done by using the Technologies- Angular (HTML, CSS & Type Script) for Frontend; SPRING Boot as Middleware; JAVA, Data JPA for Backend and MySQL Database. Software used :  Visual Studio Code for Frontend, Intellij for Backend and MySQL DB.



## Start BackEnd : datasourse

1. install MySQL Database
2. config the MySQL datasource in the application.properties file (Datasource URL, Database name and password)

## Start BackEnd : Java and Tomcat

1. instal JDK 8, and Apache Maven 3.6.3
2. go to the __fastfood_BackEnd__ folder, then compile the project : __mvn clean package__
3. start the back-end project : __java -jar target/fastfood-0.0.1-SNAPSHOT.jar__


## Start FrontEND : This project was generated with Angular CLI version 10.0.5.

1. go to the __fastfood_FrontEnd__ folder, then Install Nodejs and npm
2. make these commands : 
- install angular cli : __npm install -g @angular/cli@10.0.5__
- install all module : __npm install --force__
- start the application server : __ng serve__

3. open the browser and make this url to start __FrontEnd__ : http://localhost:4200

## some ionformation for the connection : 

1. utrains@utrains.test | Role : Admin    | pwd : Utrains_p@ss
2. alain@utrains.test   | Role : Customer | pwd : Alain_p@ss
