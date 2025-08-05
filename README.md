Academia-Check: Student Attendance System

Overview  
Academia-Check is a web-based platform designed to enhance and modernize student attendance management within academic settings. The application provides administrative users with secure, credentialed access to attendance records, along with the capability to add or modify records as necessary. The system is architected using Java Servlets and JSP for backend operations, while the frontend comprises standard technologies such as HTML and CSS.

Key Features

- Secure Administrator Authentication: Access is limited to authorized personnel.
- Attendance Record Management: Administrators may efficiently view and update attendance data.
- Role-Based Access Control: Only users with administrative rights may operate the system.
- MVC Architecture: Ensures a clear separation of concerns, supporting maintainability and scalability.

Technology Stack

- Programming Languages: Java, HTML, CSS
- Core Technologies: Java Servlets, JSP
- Database: MySQL
- Development Tools: Eclipse IDE, Apache Tomcat Server, Git, GitHub
- Architectural Design: Model-View-Controller (MVC) pattern

Project File Structure  
/academia-check/
├── Attendanceservlet.java  
├── studentattendance.jsp  
├── studentattendance.html  
├── index.html  
├── web.xml

Setup Instructions

1. Clone the repository:  
   `git clone https://github.com/tej1234naru/academia-check.git`
2. Open the project in Eclipse and import as an existing dynamic web project.
3. Configure the MySQL database:
   - Create a database named “academia”.
   - If a schema.sql file is provided, import it; otherwise, manually create a table named “attendance” with fields such as student_id, name, date, status.
4. Set up the Tomcat server in Eclipse and add the project.
5. Start the Tomcat server and access the application at [http://localhost:8080/academia-check](http://localhost:8080/academia-check).

Troubleshooting

- For 404 errors, verify servlet mapping in web.xml.
- Ensure Tomcat is running and properly configured in Eclipse.
- Check MySQL credentials and database URL within the servlet source file.
- Utilize browser developer tools (F12) to inspect file paths or form submission issues.

Conclusion  
This system offers a structured and efficient approach for managing student attendance, supporting administrative processes and ensuring data integrity in academic environments.
