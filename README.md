# EcommerceApp 
## It is an Online Electronic Shopping Application. 
### It is Maven Project. Build in Eclipse IDE.

### Technology used in this Project: 
- i) HTML,CSS and Bootstrap: designing page layout. 
- ii )Java & Javascript: all the logic has been written in java & javascript. 
- iii) JSP: all the front end logic has been written in jsp. 
- iv) SQLite: SQLite database has been used as database. 
- v) Tomcat: project will be run over the tomcat server.

### Software And Tools Required:
- Java JDK 8+
- Eclipse EE
- Apache Maven
- Tomcat v8.0+
- SQLite Tools (Online or Offline Tool)

### Steps To Import And Run The Project in Eclipse EE
- In Eclipse
- Click on File
- Select Import
- Select Projects from Git(with smart imporot) -> Next
- Select Clone URI -> Next
- In URI paste this url: https://github.com/swapnilbamble1438/EcommerceApp.git
  -> Next
-  Now in Local Destination if it is not showing error any error then proceed -> Next
   else if it is showing error, means there is already a project with same name exist.
   then change the Directory: like if it is C:\Users\Swapnil\git\EcommerceApp
   then change it to C:\Users\Swapnil\git\EcommerceAppNew
   -> Next
-  Now only select EcommerceAppNew\EcommerceApp
   -> Finish
-  If everything goes right Project will get successfully imported
-  Now wait for few seconds for getting things properly loaded
-  Now open Project > open com.conn package > open DBConnect.java file > Now change Database 
   file location / (mydatabase.db) file location like
   if it is:
   conn = DriverManager.getConnection("jdbc:sqlite:C:/Users/Swapnil/eclipse- 
   workspace/Online Electronic Shopping/mydatabase.db");
   change it according to your mydatabase.db file location.
-  After doing changes save the DBConnect.java file.   
-  Right Click On Project > Run As > Run On Server > Select Tomcat V8.0+ > Next > Finish
-  Now Website will get open, if not then try oepning it manually in Browser,
   Type Url: http://localhost:8082/EcommerceApp
-  Note: In Url put Port according to your server.

  
  


### Some Screenshots of this Project:
![Home Page](a1.png)
==================================================================================================================================================================
![Home Page](a1ii.png)
==================================================================================================================================================================
![Category Page](a2.png)
==================================================================================================================================================================
![Products Page](a3.png)
==================================================================================================================================================================
![Products Page](a4.png)
==================================================================================================================================================================
![Product Page](a5.png)
==================================================================================================================================================================
![Cart Page](a6.png)
==================================================================================================================================================================
![Customer Login Page](a7.png)
==================================================================================================================================================================
![Admin Login Page](a8.png)
==================================================================================================================================================================
![About Page](a9.png)
==================================================================================================================================================================

### Project Creator: Swapnil Bamble


