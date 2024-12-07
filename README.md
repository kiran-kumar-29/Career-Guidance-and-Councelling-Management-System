# Career Guidance and Counseling Management System

The Career Guidance and Counseling Management System is a web-based application designed to provide students with career guidance, counseling, and mentorship. Built with Java Spring Boot and integrated with a MySQL database, the system facilitates counselor-student mapping, appointment scheduling, and communication channels for a seamless career counseling experience.

## Features

- Student-Counselor Mapping:Admin sssigns students to counselors based on predefined criteria or manual assignment by administrators.
- Appointment Scheduling: Allows students to schedule appointments with counselors based on their availability.
- Counselor Dashboard: Provides counselors with tools to manage student profiles, appointments, and counseling notes.
- Student Dashboard: Enables students to view assigned counselors, check appointment schedules, and access career counseling resources.


## Technologies Used

- Backend: Java Spring Boot
- Frontend: HTML, CSS, JavaScript
- Database: MySQL
- Development Tools: IntelliJ IDEA, Red Hat CodeReady Studio, Eclipse, Spring Tool Suite

  
## Installation and Setup
### 1. Prerequisites
- Install Java 8 or higher.
- Install MySQL Server and ensure it is running.
- Install a Java IDE (e.g., IntelliJ IDEA, Eclipse, or Red Hat CodeReady Studio).


### 2. Clone the Repository
- Run the following commands:
- git clone https://github.com/kiran-kumar-29/Career-Guidance-and-Counselling-Management-System.git
- cd Career-Guidance-and-Counselling-Management-System


### 3. Configure the Database
- Create a MySQL database (e.g., cgcms).
- Update the application.properties file located in src/main/resources with the following configuration:
  
####  application.properties
1. spring.datasource.url = jdbc:mysql://localhost:3306/cgcms
2. spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
3. spring.datasource.username=root
4. spring.datasource.password=YOUR_PASSWORD
5. spring.jpa.show-sql:true
6. spring.jpa.hibernate.ddl-auto=update
