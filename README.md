# hospital-management-system
This project was built with Java, Swing, and MySQL database

#Below are a few procedures to follow when integrating it on your machine.
1. Download the zip file or clone it.
2. Load the folder in visual studio code.
   Make sure you have the "Extension Pack for Java" extension in your vscode.
3. Download the MySQL server that will be used to integrate the database.
   With this, download the java connector, create a lib/java in the root of your project, and add it for easy location.
   In vs code, under preferred libraries, navigate to the jar connector file and add it.
4. Create a new database in your localhost "in terminal", Which you can preferably name "hospital" to match that in the project.
   And then invoke or execute the attached SQL script to your database in this manner; mysql -u root -p your_database_name < path/to/your/script.sql.
5. Run your project
