mozu-sample-java
================

A sample Java web application that demostrates how to use the Mozu Java API.

To build and run:
1. Download the mozu-java-sdk git project.  
2. In the mozu-java-sdk root directory run gradlew clean install
3. Download the mozu-sample-java project to your machine.
4. In the mozu-sample-java directory run gradlew clean build jettyRun.  This will build the application and start a Jetty web service.

In order to access Mozu through the sample application you must do the following steps in the Mozu application:
1. Obtain a developer account on mozu.
2. Log into Mozu with your mozu developer account.
3. Create an "Application" record in Mozu Dev Center.  ( Applications | Create Application) 
4. Create a tenant in mozu.
5. Return to your application you created in step 3. Click "Install Application" and select the site you want the sample application to access.
6. Return to the tenant you created in step 4.  Click "View Tenant" then "Catalog | Inventory" to add products to your catalog.
7. Add Orders for the product you created.

Running the Sample application:
1. Use a browser to go to the Mozu Sample application (Default: http://localhost:8080/MozuSample)
2. Get the Application ID and Shared Secret from the application you installed in step 3.  You can get this from the Applications page in the Mozu Dev Center.
3. The user name and password is your development account credentials.
4. Once logged in, you can access the tenant and site you created in step 4.  You should be able to see the products and orders you created in step 6 and 7. 

