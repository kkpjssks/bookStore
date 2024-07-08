# bookStore
I created a simple spring boot application to demonstrate a book store.

# Running
Clone the repo and open it in intelliJ (not necessary but I would prefer), then let it download the dependencies from pom.xml. Or you can manually give it a check by opening that file then there will be a hovering icon, just need to press it.

# Database Connection
I used mariaDB, if by any chance you are on mySQL then you will have to change the dependency of mariaDB connector to mySQL-connector. You can find the code on https://mvnrepository.com/artifact/com.mysql/mysql-connector-j. Then in src/main/resources you will find a file named application.properties. Open it and change the code according to your database connection (username and password).

Once this is done, simply hit run button and as per default, open browser go to https://localhost:8080/ and home page of simple book store will be visible. 
