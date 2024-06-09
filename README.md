<b>Enterprise Application with MySQL, Java Spring Boot, and React </b>

Welcome to our Enterprise Application project! This project demonstrates the integration of MySQL database with Java Spring Boot for the backend and React for the frontend. We've implemented essential functionalities needed for enterprise applications, including CRUD operations, report generation in PDF and Excel formats, sorting, and search capabilities.

<b>Features</b>
<b>CRUD Operations:</b> Perform Create, Read, Update, and Delete operations on your enterprise data.<br />
<b>Report Generation:</b> Generate reports in both PDF and Excel formats for easy data analysis.<br />
<b>Sorting:</b> Sort data by column titles to quickly find the information you need.<br />
<b>Search Ability:</b> Search through your data efficiently with our search functionality.<br />
<b>User Authentication and Authorization:</b> Secure your application with user authentication and authorization.
<b>User Registration Page:</b> Allow new users to register with your application.
<b>User Role:</b> Implement user roles to manage permissions within your application.
<b>Dockerization:</b> Containerize your application components for easy deployment and scalability.
<b>Flywaydb:</b>  Implement database migration tool that allows you to manage and automate the evolution of your database schema over time.

<b>Technologies Used</b>
<b>MySQL:</b> A robust relational database management system for storing your enterprise data.<br />
<b>Java Spring Boot:</b> A powerful framework for building Java-based enterprise applications, providing features such as dependency injection, RESTful web services, and more.<br />
<b>React:</b> A JavaScript library for building user interfaces, offering a component-based approach for creating interactive UIs.<br />

<b>Prerequisites</b>
<ul>Before getting started, ensure you have the following installed:<br />
  <li> Java Development Kit (JDK)</li>
  <li> Node.js and npm</li>
  <li> MySQL Server</li>
  <li> Docker (optional, for containerization)</li>
</ul><br>

<b>Getting Started</b>

<b>Clone the repository:</b> <br />
<b>git clone https://github.com/sarwaraminy/sprint-boot-with-react.git</b><br />

<b>Backend Setup:</b><br />

Navigate to the backend directory.<br />

Configure your MySQL database settings in application.properties.<br />

Run the Spring Boot application:<br />


./mvnw spring-boot:run<br />
Frontend Setup:<br />

Navigate to the frontend directory.<br />

Install dependencies:<br />
npm install file-server<br />
npm install axios<br />
npm install react-router-dom <br />

npm install<br />
Start the React development server:<br />

npm start<br />
Access the Application:<br />

Open your web browser and visit http://localhost:3000 to access the application.<br /><br />

<b>Contributing</b><br />
We welcome contributions from the community! Feel free to open issues for bug fixes or feature requests, and submit pull requests to contribute code.<br />

<b>Deploy</b>: to deployee you need to do the following:<br />
<ul>
<li>Update pom.xml and add the tomcat dependency and update build pacakges</li>
<li>Update your Main application Class DemoApplication.java</li>
<li>Update pom.xml and add the tomcat dependency and update build pacakges</li>
<li>Update your Main application Class DemoApplication.java</li>
<li>run this command in your project: mvn clean package
<li>After running this command, you should find the demo-0.0.1-SNAPSHOT.war file in the target directory.</li>
</ul>

<h1>Screenshots</h1>
<h3>Login page</h3>
<image alt="Room Login page" src="screenshots/login.png" />
<h3>Registraion page</h3>
<image alt="Room Registration page" src="screenshots/signup.png" />
<h3>Dashboard page</h3>
<image alt="Room Dashboard page" src="screenshots/dashboard.png" />
<h3>CRUD opration</h3>
<image alt="Room CRUD opration" src="screenshots/CRUD-opration.png" />


<b>License</b><br />
This project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.<br />

<b>Contact</b><br />
If you have any questions or suggestions, please feel free to contact us at sarwaraminy@gmail.com .<br />

<b>Thank you for using our Enterprise Application! We hope it serves your needs effectively</b>.<br />
