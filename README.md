# conference-demo-spring-boot
This is a demo app for conference organizations backend built with spring boot. This repo was indented for self-learning and practicing.



# Database

A postgresql local database is used for this application. After getting a database up and running use the create_tables.sql and insert_data.sql found in ./src/mai/resources/database.



## APIs

The basic 5 cruds [get all, get one, create, delete, update] are implemented using the controllers, JPA repositories, and models java files.



Note: The cruds are implemented only for Sessions and Speakers. 