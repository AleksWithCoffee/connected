
"Connected" - Java Desktop Chat Room Application using javafx(server).

Configurations:

First, create database(MySQL) and table "users" using 'databaseScript' file.
All parameters are listed in 'application.property' file in resources folder, make sure your configurations are appropriate to your needs.

Executing:

Via the main class using IDE or by running artifact(jar file).
To create an executable jar use 'mvn clean install' command.
Jar-with-dependencies will show up in target directory.
'java -jar foo.jar' command runs the server.
You can use 'application.property' as default or your own property file taking into account that names of the attributes must be the same as
in server class. Executing via the main class or by running jar file passing no parameters means that 'application.property' file from resources will be used. To pass configurations parameters from your own application.property file execute application passing one parameter (which is path to your file), for example: 'java -jar foo.jar /path/to/your/application.property'.
