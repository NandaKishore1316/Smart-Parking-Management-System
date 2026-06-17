# Smart Parking Management System

A very simple coding and design pattern has ben used to automate the browsing through the parking lots, checking out empty spots, finding out whether it is available for advance booking, etc and fare calculation.

## Technologies used:
- Front end: HTML5, Javascript and CSS3
- Validations: JavaScript
- Back end: Java Servlets
- Database: MySQl
- Server :  Apache Tomcat

## Features

- **Login Register**: Users and parking lot owners can register into the portal and will be allowed to browse through the list of places-> parking lots-> parking spots

- **Current Booking** : Users can check out the availibilty of empty spots currently and book the spot immedietly.

- **Future Booking**:  If a user needs an advance booking, he can do so by booking the car/bike from a fixed time to a fixed time.

- **Fare calculation**: The fare is automatically calculated as per the time booked and per hour charge and is generated at the time of leaving.

## Setup Intructions

### Prerequisites

Make sure the following software is installed:

* Java JDK 8 or later
* Apache Tomcat 8/9
* Eclipse IDE for Enterprise Java Developers
* MySQL Server
* MySQL Connector/J (JDBC Driver)

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Smart-Parking-System
```

### 2. Import the Project into Eclipse

1. Open Eclipse IDE.
2. Select **File → Import**.
3. Choose **Existing Projects into Workspace**.
4. Browse to the project folder.
5. Click **Finish**.

### 3. Configure Apache Tomcat

1. Go to **Window → Preferences → Server → Runtime Environments**.
2. Click **Add**.
3. Select **Apache Tomcat v8.0/v9.0**.
4. Browse to your Tomcat installation directory.
5. Click **Finish**.

### 4. Add MySQL JDBC Driver

1. Download MySQL Connector/J.
2. Right-click the project.
3. Select **Build Path → Configure Build Path**.
4. Click **Add External JARs**.
5. Select the MySQL Connector JAR file.

### 5. Configure Database Connection

Update the database URL, username, and password in the project's database connection file according to your local MySQL configuration.

### 6. Build the Project

1. Select **Project → Clean**.
2. Enable **Build Automatically**.
3. Resolve any build errors if they appear.

### 7. Deploy the Project

1. Open the **Servers** tab.
2. Right-click the configured Tomcat server.
3. Select **Add and Remove**.
4. Add the project to the server.
5. Start Tomcat.

### 8. Access the Application

Open your browser and navigate to:

```text
http://localhost:8080/Smart-Parking-System
```

If the application uses a different context path, use the context path configured in Tomcat.

---

## Troubleshooting

* Ensure Java, Tomcat, and MySQL are installed correctly.
* Verify the JDBC driver is added to the project's build path.
* Check that the database connection settings are correct.
* Make sure Tomcat is running before accessing the application.








