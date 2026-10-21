# JAVA-LAB

### Student Info
**Student Name:** Sarvesh Jain
**Roll No:**  24EGJAD047 
**College:** Global Institute of Technology (GIT), Jaipur 
**University:** Rajasthan Technical University (RTU), Kota
**Semester:** 5th Semester (B.Tech AI & DS)
**Subject:** Advanced Java Programming Lab Project

A Java laboratory repository designed for college practical learning and hands-on programming practice. This project contains multiple Java exercises covering core Java, Swing GUI development, JDBC database connectivity, socket programming, remote communication, servlet-based web development, and a final project structure.

This repository is structured as a learning workspace where each experiment demonstrates a different Java concept and application model. It is intended for academic use, self-learning, and practical revision before exams and lab assessments.

## Repository Overview

This repository includes:

- Java-based experiments for classroom and lab work
- GUI applications using Swing
- Database connectivity using JDBC and MySQL
- Client-server communication using Java sockets
- Remote method invocation-style calculator application
- Servlet-based Java web application examples
- A final project folder for academic project development

## Repository Structure

```text
JAVA-LAB/
├── README.md
├── ADV.-JAVA-LAB-main/
│   ├── EXP-1/
│   │   ├── StudentRegistration.java
│   │   └── StudentRegistration.class
│   ├── EXP-2/
│   │   ├── Main.java
│   │   ├── CalculatorView.java
│   │   ├── CalculatorModel.java
│   │   ├── CalculatorController.java
│   │   └── *.class
│   ├── EXP-3/
│   │   ├── src/
│   │   │   ├── App.java
│   │   │   └── JdbcDemo.java
│   │   ├── bin/
│   │   └── lib/
│   ├── EXP-4/
│   │   ├── client.java
│   │   ├── server.java
│   │   └── *.class
│   ├── EXP-5/
│   │   ├── Calculator.java
│   │   ├── CalculatorImplementation.java
│   │   ├── Client.java
│   │   └── Server.java
│   ├── EXP-6/
│   │   └── servelet/
│   │       ├── pom.xml
│   │       ├── src/
│   │       └── target/
│   ├── EXP-7/
│   │   └── servlet/
│   │       ├── pom.xml
│   │       ├── src/
│   │       └── target/
│   └── PROJECT/
│       └── SARV-MART/
│           ├── pom.xml
│           ├── src/
│           └── database/
```

## Technologies Used

This repository is primarily based on the Java programming language and uses several Java ecosystem tools and technologies:

- Java SE
- Java Swing for GUI interface design
- JDBC for database connectivity
- MySQL database
- Java Sockets for networking
- Java Remote Method Invocation (RMI-style design in calculator application)
- Servlet-based Java web development
- Maven for build and dependency management
- Apache Tomcat-style deployment model for servlet projects

## Experiment Details

### EXP-1: Student Registration Form

This experiment demonstrates the use of Swing components such as:

- JFrame
- JLabel
- JTextField
- JRadioButton
- ButtonGroup
- JCheckBox
- JButton
- JOptionPane

The application allows a user to enter:

- student name
- roll number
- gender
- branch
- terms and conditions acceptance

It validates fields and shows success or error messages depending on user input.

Use case:
- GUI-based registration form
- form validation
- interactive user input
- event handling with ActionListener

### EXP-2: MVC Calculator

This experiment follows the Model-View-Controller pattern to build a basic calculator.

Files involved:
- Main.java
- CalculatorView.java
- CalculatorModel.java
- CalculatorController.java

The application includes:
- text fields for numbers
- operation buttons for addition, subtraction, multiplication, and division
- result display
- separation of logic, UI, and event handling

Use case:
- understanding MVC architecture
- Java Swing UI
- event-based application design

### EXP-3: JDBC and MySQL Database Example

This experiment shows how Java connects to a MySQL database using JDBC.

Main concept:
- loading JDBC driver
- connecting to a database
- executing SQL statements
- inserting records
- reading and displaying result sets

The sample code uses a database named `college` and inserts data into a table named `student`.

Use case:
- database connectivity
- SQL execution from Java
- practical database integration

### EXP-4: Client-Server Communication

This experiment demonstrates Java socket programming.

Files:
- client.java
- server.java

The server listens on a port and waits for client requests. The client sends a message to the server, and the server replies back.

Use case:
- network communication
- socket programming
- message exchange between client and server

### EXP-5: Calculator Remote Communication Example

This folder contains files such as:

- Calculator.java
- CalculatorImplementation.java
- Client.java
- Server.java

This example is designed to demonstrate remote calculation logic and communication between application components, similar to Java distributed application patterns.

Use case:
- method communication
- service implementation
- distributed Java application structure

### EXP-6: Servlet Example

This folder contains a Maven-based servlet application.

It includes:
- `pom.xml`
- `src` folder
- generated `target` folder

This experiment is a basic servlet project and demonstrates Java web application development using servlet architecture.

Use case:
- Java web programming
- web request handling
- server-side Java logic

### EXP-7: Advanced Servlet Application

This folder contains a more advanced servlet project with a Maven configuration and package structure under `src/main/java`.

This project represents a continuation of Java web application learning and demonstrates a more structured servlet-based application setup.

Use case:
- enterprise-style servlet development
- Java web application structure
- Maven-based deployment workflow

### PROJECT/SARV-MART

This folder acts as the main college project directory. It contains:

- `pom.xml`
- `src`
- `database`

This is the final project area and is intended to represent a complete application or capstone-level project built in Java with a database-backed structure.

Use case:
- project development
- structured codebase
- database-based Java application

## Prerequisites

Before running the project, ensure that the following tools are installed:

- Java Development Kit (JDK)
- Java IDE such as IntelliJ IDEA, Eclipse, or VS Code
- MySQL database server
- Maven
- Apache Tomcat or a compatible servlet deployment environment

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Sarvesarv/JAVA-LAB.git
cd JAVA-LAB
```

### 2. Open a Java Program

For simple Java files, compile and run them using:

```bash
javac filename.java
java filename
```

Example:

```bash
cd "ADV.-JAVA-LAB-main/EXP-1"
javac StudentRegistration.java
java StudentRegistration
```

### 3. Run the JDBC Example

Open MySQL and ensure the required database and table exist.

Example logic:
- database: `college`
- table: `student`

Then run:

```bash
cd "ADV.-JAVA-LAB-main/EXP-3/src"
javac App.java
java App
```

### 4. Run the Socket Example

Open two terminals:

Terminal 1:
```bash
cd "ADV.-JAVA-LAB-main/EXP-4"
javac server.java
java server
```

Terminal 2:
```bash
cd "ADV.-JAVA-LAB-main/EXP-4"
javac client.java
java client
```

### 5. Run Servlet Projects

For the Maven-based servlet examples:

```bash
cd "ADV.-JAVA-LAB-main/EXP-6/servelet"
mvn clean package
```

and

```bash
cd "ADV.-JAVA-LAB-main/EXP-7/servlet"
mvn clean package
```

Then deploy the generated WAR file into a servlet-compatible server or run using an appropriate IDE server configuration.

### 6. Run the Main Project

For the project folder:

```bash
cd "ADV.-JAVA-LAB-main/PROJECT/SARV-MART"
mvn clean package
```

Then deploy or run according to the project configuration.

## Learning Outcomes

This repository helps learners understand:

- Java programming fundamentals
- GUI application development with Swing
- event-driven programming
- object-oriented design
- MVC architecture
- database connectivity with JDBC
- socket-based networking
- remote communication patterns
- servlet-based web development
- Maven project structure
- final project organization for academic submission

## Recommended Use

This repository is best used in the following order:

1. Start with simple Java programs
2. Learn Swing-based form creation
3. Move to MVC and UI logic
4. Practice JDBC and database integration
5. Study networking and communication
6. Learn Java web programming with servlets
7. Use the final project folder for practical implementation

## Project Purpose

The purpose of this repository is to provide a complete Java practical lab experience for college students. It is designed to strengthen core Java knowledge, improve programming confidence, and prepare students for practical exams, mini-projects, and final-year Java application development.

## Conclusion

JAVA-LAB is a collection of educational Java exercises and a structured project workspace. It covers the major concepts needed for a Java laboratory course and helps students build real practical understanding of programming, UI design, database integration, and web application development.

This repository is ideal for:
- college Java lab work
- practical evaluation preparation
- self-learning Java
- building a stronger foundation in Java application development
