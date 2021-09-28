<h1>Hotel Management System
</h1>

<h3>Result (HomePage)</h3>
<img src="https://github.com/Jayant-Chaurasiya/Hotel_Management_System/blob/c2cb386b5770101971ea9b83e28be9f5db4b52b6/FrontEnd/src/assets/img/image.png">
<h3>Project Description</h3>
<p>
  The Application should allow the users to book the hotel rooms for few days which should include accomodation and food during the stay.

Admin allows the Receptionist activations and add Hotel rooms and the services offered by the Hotels. Receptionist allow to display what are the rooms are available & services are being offered. Customers need to register in order to book a room in a hotel from 1 day to 10 days maximum. Customer can also have the facilities of dropping/picking up from/to nearby location.
</p>

 <h1>Technology Used</h1>
<ul>
 
  
  
  <li>  Core Java</li>
  <li>Microservices</li>
<li>  Spring Boot</li>
<li>  Spring Data</li>
<li>  Angular 10</li>
<li>  Spring AOP</li>
<li>  PostgreSQL</li>
<li>   AWS RDS</li>
<li>  AWS EC2</li>
<li>  Docker</li>
<li>  Jenkins</li>
   
</ul>

<h1>Features</h1>
<h3>Admin</h3>
<li>Admin should login before accessing the system</li>
<li>Admin can add new receptionist when he/she joins the hotel. The login credentials for the receptionist is sent through a mail.</li>
<li>Admin can view all the receptionists or by receptionist id.</li>
<li>Admin can add available rooms in the hotel and view all the rooms that he has added.</li>
<li>Admin can add new offers that varies with festivals/seasons, view all the offers and he can change the offers accordingly.</li>
<li>Admin can view customers feedback and booking history.</li>




<h3>Receptionist</h3>


<li>Receptionist should log in to his/her account to perform operations.</li>
<li>Receptionist allocates room numbers to the customers based on their chosen requirementst</li>
<li>Payment will be done by customer while booking hotel room,during check in and check out.</li>
<li>If customer cancels his/her booking the amount will be refunded based on customer check in and cancellation date. While customer vacates, bill gets generated to the customer and balance amount should be cleared by the customer so that he can check out.</li>



<h3>Customer</h3>

<li>Customer can signup if he/she visits website for the first time or if the customer is already having an account then the customer can log in to the website and directly book a room.</li>
<li>Customer can edit their details and update their password if they forgot.</li>
<li>Customer can book a room on the basis of room type,offers,number of members. At the time of booking customer has to pay 10% amount in advance.Customer can update the booking details and cancel booking at a valid time for valid reasons so that they can get a refund accordingly.</li>
<li>Customer can utilize pick drop facilities.</li>
<li>Customer can pay the final bill through card,net banking and cash also.</li>





<h3>Build</h3>
<p>Run ng build to build the project. The build artifacts will be stored in the dist/ directory.</p>

<h3>Test</h3>
<p>Run ng test to execute the unit tests via Karma.</p>


<h3>Running end-to-end tests</h3>
<p>Run ng e2e to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.</p>

 <h3>Further help</h3>
<p>To get more help on the Angular CLI use ng help or go check out the Angular CLI Overview and Command Reference page.</p>



<h1>Technical Aspects</h1>
<ul>

  <li>Used Spring Data for connecting to postgreSQL database.</li>
<li>Used DAO design pattern in the project</li>
<li>Created Interactive Webpages using Angular and Bootstrap for the website</li>
<li>All the client side and server side validations were done using TypeScript and Database</li>
<li>Exception or Error Handling is done in both java and angular(With HttpClient)</li></li>
<li>Tested all the functionalities using JUnit4</li>
<li>Implemented Logging by Log4j</li>



</ul>



<h1>Getting Started</h1>
<p>After running this project , run the angular project . Home page will be displayed where you can see the about,facilities and login section for Admin, Receptionist, Customer.

After login they can view their respective dashboard with all the functionalities.</p>



<h1>Usage</h1>

<h3>Step 1</h3>

<p>
Import this project by a Github Desktop(click here to install) or by downloading the Zip file . If you downloaded the zip file then you need to unzip or extract it and import this in eclipse(file-->import-->select the project) change the database configuration in application.properties file (Driver,Dialect,username and password).</p>
  
  
  <h3>Step 2</h3>
  
  <p>Import the angular Project (find here)by a Github Desktop or by downloading the Zip file. If you downloaded the zip file then you need to unzip or extract it and open the project folder in visual studio code or any other code editor(file-->select folder-->select the project)

That's all you can run this project and see the results.</p>


<h1>Contributors</h1>
<p>This Project is a batch project. Entire batch of 25 members worked on each modules and functionalities collaboratively.</p>
