# JavaMastery

Welcome to **JavaMastery**! This repository is a curated collection of my Java projects, showcasing a variety of concepts, techniques, and solutions I’ve worked on. Explore my journey through coding challenges, application development, and innovative Java solutions. Here you’ll find a range of projects that demonstrate my expertise and growth in Java programming.

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

**JavaMastery** is intended to demonstrate my skills and progress in Java programming. Here you’ll find a range of projects including:
- Algorithms and data structures
- Application development
- Coding challenges
- Design patterns
- Advanced Java features

Feel free to explore and learn from the projects, or use them as a reference for your own work!

## Projects

### Project 1: OTP Generator

**Overview:**
The OTP Generator project is a Java-based system designed to create and validate One-Time Passwords (OTPs) for enhanced security, particularly in two-factor authentication (2FA) scenarios. It provides functionality to generate random OTPs with customizable settings and ensures their validity within a specified time period.

**Features:**
- **Random OTP Generation:** Creates OTPs of configurable lengths (e.g., 4, 6, 8 digits).
- **Configurable OTP Length:** Users can set the desired length for the OTP.
- **Alphanumeric Support:** Option to include both letters and digits in the OTP.
- **Validity Period:** Defines an expiration time for each OTP.
- **Logging:** Basic logging to track OTP generation and usage.

**Technologies Used:**
- **Java:** Core programming language for OTP generation and validation.
- **Maven:** Build automation and dependency management.
- **JUnit 5:** Testing framework for unit tests.
- **Visual Studio Code:** Integrated development environment (IDE) for coding, with Java Extension Pack and Test Runner for Java.

### Project 2: Number Guessing Game

The Number Guessing Game is a Java-based application designed for players to guess a randomly generated number between 1 and 100. The game provides feedback after each guess, indicating whether the guess is too high, too low, or correct. It also tracks the number of attempts and offers the player an option to start a new game after guessing correctly.

### Technologies Used:
- **Java**: The programming language used to build the game.
- **Random**: Utilized for generating a random number between 1 and 100.
- **Scanner**: Used to capture user input.

### Key Features:
- Random number generation within a specified range.
- Real-time feedback on guesses.
- Attempt tracking and replayability options.

To run the game, clone the repository, compile the Java file, and execute the program.

### Project 3: Brick Breaker Game

The Brick Breaker Game is a classic arcade-style game where players use a paddle to bounce a ball and break bricks. The game features multiple levels with increasing difficulty, various power-ups, and a scoring system to track player progress. It is developed using Java and the Swing framework for its graphical interface.

### Technologies Used
- **Java**: The primary programming language for game logic and functionality.
- **Swing**: Java’s built-in library for creating the graphical user interface.

The project includes:
- **Main.java**: Entry point for the game.
- **GamePanel.java**: Manages the game display and interactions.
- **Paddle.java**: Handles the paddle's movement and behavior.
- **Ball.java**: Manages ball movement and collision detection.
- **Brick.java**: Represents the bricks and their interactions with the ball.

The game can be run on any system with Java Development Kit (JDK) 8 or higher.

### Project 4: ATM Simulation System

### Project Introduction:

The **ATM Simulation System** is a console-based Java application that simulates basic functionalities of an ATM machine. Designed for educational purposes, this project allows users to interact with a simulated ATM to perform common banking tasks. It emphasizes core Java programming concepts such as object-oriented design, exception handling, and file operations, providing a hands-on learning experience for students or developers working on Java applications.

### Features:

- **User Authentication**: Secure login using a predefined PIN.
- **Balance Inquiry**: Displays the current account balance.
- **Cash Withdrawal**: Enables withdrawal of funds with appropriate checks.
- **Deposit Funds**: Allows users to deposit money into their account.
- **Transaction History**: Provides a view of past transactions for review.

### Technology Used:

- **Programming Language**: Java
- **Development Kit**: Java Development Kit (JDK) 8 or higher
- **Development Environment**: Text editors or IDEs like IntelliJ IDEA, Eclipse, or VS Code
- **Version Control**: Git for cloning and managing the project

### Project 5: Fee Report System

### Project Introduction:

The **Fee Report System** is a console-based Java application designed to manage and generate fee reports for educational institutions. It allows administrators to manage student information, define fee structures, track payments, and generate detailed reports. The system ensures smooth fee management by providing tools for role-based access control, student data management, and automated notifications.

### Features:

- **Student Information Management**: Add, update, and delete student details, including personal and academic information.
- **Fee Structure**: Define multiple fee categories and set fee structures based on courses and programs.
- **Fee Payment Tracking**: Record, track, and manage fee payments, including due and overdue payments, and generate fee receipts.
- **Report Generation**: Create detailed individual and institutional fee reports, exportable in formats like PDF and Excel.
- **User Roles and Access Control**: Assign roles such as Admin, Accountant, and Student with different access permissions.
- **Notifications**: Send reminders for upcoming payments and overdue fee notifications to students and parents.

### Technology Used:

- **Programming Language**: Java
- **Development Kit**: Java Development Kit (JDK) 8 or higher
- **Development Environment**: IDEs like IntelliJ IDEA, Eclipse, or a text editor
- **Version Control**: Git for project management and version control
- **Export Formats**: PDF and Excel for report generation

### Project 6: Supermarket Billing System

### Project Introduction:

The **Supermarket Billing System** is a console-based Java application developed to manage supermarket billing operations. This application allows users to add items to a cart, view the cart, and generate a bill, providing a hands-on approach to learning Java programming. It demonstrates key Java concepts such as object-oriented programming, user input handling, and basic data processing.

### Features:

- **Add Item**: Add products to the cart by specifying the item's name, price, and quantity.
- **View Cart**: Display all items in the cart along with their individual and total cost.
- **Generate Bill**: Calculate the total cost of all items in the cart, display a detailed bill, and clear the cart for the next transaction.
- **Exit**: Close the application.

### Technology Used:

- **Programming Language**: Java
- **Development Kit**: Java Development Kit (JDK) 8 or higher
- **Development Environment**: IDEs such as IntelliJ IDEA, Eclipse, or a text editor
- **Version Control**: Git for project management and version control

### Project 7: Text-Based Adventure Game

### Project Introduction:

The **Text-Based Adventure Game** is a Java-based command-line game where players engage in an interactive adventure by making choices that shape the story’s progression. Players explore different scenarios, making decisions that lead to multiple paths and outcomes. This game serves as an excellent project for practicing Java programming skills such as user input handling, control flow, and basic game design.

### Features:

- **Interactive Storytelling**: Players navigate a branching narrative, where each choice influences the direction of the story.
- **User Input Handling**: The game is entirely driven by text commands, making it simple yet immersive.
- **Dynamic Outcomes**: Multiple endings and paths provide replayability, as the game changes based on player choices.
- **Command-Line Interface**: The game runs in a text-based interface, focusing on story-driven engagement without graphics.

### Technology Used:

- **Programming Language**: Java
- **Development Kit**: Java Development Kit (JDK) 8 or higher
- **Development Environment**: Text editors or IDEs like IntelliJ IDEA, Eclipse, or VS Code
- **Version Control**: Git for managing the project

### Project 8: Broadcasting Chat Server

### Project Introduction:

The **Broadcasting Chat Server** is a Java-based application that enables real-time communication between multiple clients through a server. This server broadcasts messages from any client to all other connected clients, demonstrating the use of multi-threading and Java networking. It is a simple, console-based tool ideal for understanding client-server communication, socket programming, and multi-threading in Java.

### Features:

- **Multi-Client Support**: Allows multiple clients to connect and communicate simultaneously using multi-threading.
- **Real-Time Broadcasting**: Messages are instantly broadcast to all connected clients in real-time.
- **Robust Error Handling**: The server includes error handling mechanisms to manage unexpected issues and maintain stability.
- **Console-Based Interface**: Both server and client applications use a simple, easy-to-use command-line interface.

### Technology Used:

- **Programming Language**: Java
- **Development Kit**: Java Development Kit (JDK) 8 or higher
- **Networking**: Java socket programming for client-server communication
- **Multi-threading**: Threads are used to handle multiple client connections
- **Development Environment**: IDEs like IntelliJ IDEA, Eclipse, or a text editor
- **Version Control**: Git for managing the project

## Getting Started

To get started with any of the projects in this repository:

1. Clone the repository:
   ```sh
   git clone https://github.com/PriyantNikhare/JavaMastery.git
   ```

2. Navigate to the project directory:
   ```sh
   cd JavaMastery/ProjectName
   ```

3. Build and run the project:
   ```sh
   javac Main.java
   java Main
   ```

*Replace the build and run commands as needed based on your specific projects.*

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

Please ensure your contributions adhere to the coding standards used in the repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please reach out to me at [priyant.p.nikhare@gmail.com](mailto:priyant.p.nikhare@gmail.com).

---

Thank you for visiting **JavaMastery**! Happy coding!
