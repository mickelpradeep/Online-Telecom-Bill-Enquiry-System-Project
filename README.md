# Infosys Springboard Internship (Batch-2)
# Online Telecom Bill Enquiry System (OTBS)

## **Overview**
The Online Telecom Bill Enquiry System (OTBES) is a centralized platform developed for Bharat Teleservices to streamline its day-to-day operations. The system provides a seamless interface for customers and administrators to manage activities such as registration, connection handling, plan management, billing, and complaints. It enhances efficiency, reduces manual effort, and improves the overall customer experience.

## **Features**
- **Customer Management :** Register customers, handle credentials, update personal details.
- **Connection Management:** Apply for new connections and manage multiple connections.
- **Plan Management:** View, select, and update telecom plans as per connection type.
- **Bill Management:** Generate, view, and pay bills for telecom services.
- **Complaint Management:** Raise, track, and resolve complaints with feedback.
- **Report Generation:** Generate analytical reports for administrators and customers.

## **Modules and Functionalities**
**1. Customer Management**

Captures user details such as name, contact information, and address.
Generates unique customer IDs.
Enables customers to update personal information.
Allows secure credential creation for login.

**2. Connection Management**

Supports applying for connections (prepaid/postpaid/broadband).
Manages multiple connections for a single user.
Tracks modifications to connection details.

**3. Plan Management**

Allows customers to choose from a range of telecom plans.
Admins can add, update, or deactivate plans.
Sends email notifications for plan expiry or billing cycles.

**4. Bill Management**

Generates accurate bills based on usage, plan, and additional charges.
Enables viewing, downloading, and online payment of bills.
Sends reminders for bill due dates and unpaid bills via email.

**5. Complaint Management**

Customers can log and track complaints.
Includes escalation processes and feedback submission.
Admins can assign and resolve complaints efficiently.

**6. Report Generation**

Generates insights such as customer activity, most popular plans, and unresolved complaints.
Helps administrators analyze revenue and performance metrics.

## **Technologies Used**
**Backend**
- Java 17
- Spring Boot (REST Services, Data JPA)
- MySQL 8

**Frontend**
- Thymeleaf for dynamic content rendering and form handling.
  
**Tools**
- Spring Tool Suite (STS)
- Postman for API testing.

## **Setup and Installation**
**Prerequisites**
- Install Java 17 or higher.
- Set up MySQL 8 and configure a database for the application.
- Install Spring Tool Suite (STS) for development.

**Steps**

1. Navigate to the project directory and open the backend and frontend projects separately in STS.

2. Configure **application.properties** for database and mail settings:
```application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/otbes
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
spring.mail.username=your_email@gmail.com
spring.mail.password=your_email_password
```
3. Build and run the backend project (OTBS) and the frontend project (OTBSClient).
4. Access the application in your browser:

   Frontend: http://localhost:8091

   Backend API: http://localhost:8080/api/customers

## **Key Highlights**
- Implements client-side and server-side validations for all entities.
- Features email notifications for registration success and billing updates.
- Modular design to facilitate seamless integration and scalability.

## **Challenges Faced**
- Ensuring seamless communication between the frontend and backend.
- Debugging complex modules like billing and complaint management.
- Handling user-friendly error messages during registration and login.

## **Future Enhancements**
- Develop mobile applications for better accessibility.
- Introduce multi-language support.
- Implement AI-based chatbots for automated support.

## **Acknowledgments**
Thank the mentor & project guides, and team members for their support and collaboration.

Mentor: Sudha C (https://github.com/springboardmentor403)

**Thanks to all Team members**
