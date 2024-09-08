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

### Project 1: OTP Generator (./Project_1_OTP Generator)

# OTP Generator

## Overview
The OTP (One-Time Password) Generator project is designed to create a simple yet effective OTP generation and validation system using Java. The OTP generator can be utilized in various applications to enhance security through two-factor authentication (2FA).

## Features
- **Random OTP Generation:** Generates random OTPs of a specified length.
- **Configurable OTP Length:** Allows users to configure the length of the OTP (e.g., 4, 6, 8 digits).
- **Alphanumeric Support:** Option to generate OTPs containing alphanumeric characters.
- **Validity Period:** Sets a validity period for the OTP, after which it expires.
- **Logging:** Basic logging to keep track of OTP generation and usage.

## Prerequisites
- **Java Development Kit (JDK)**: Install the JDK from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html) or [AdoptOpenJDK](https://adoptopenjdk.net/).
- **Maven**: Install Maven from the [Apache Maven website](https://maven.apache.org/download.cgi).
- **Visual Studio Code (VS Code)**: Download and install VS Code from the [official website](https://code.visualstudio.com/).
- **VS Code Extensions**:
  - [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
  - [Test Runner for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test)

## Installation
1. **Clone the Repository**:
    ```sh
    https://github.com/PriyantNikhare/JavaMastery.git
    cd PriyantNikhare/JavaMastery
    ```

2. **Open the Project in VS Code**:
    - Open VS Code.
    - Use the `File` > `Open Folder` menu to open the `otp-generator` directory.

3. **Install Necessary Extensions**:
    - Open the Extensions view (`Ctrl+Shift+X`).
    - Search for and install the **Java Extension Pack**.
    - Search for and install **Test Runner for Java**.

4. **Build the Project**:
    - Open the integrated terminal in VS Code (`Ctrl+``).
    - Run the following command:
        ```sh
        mvn clean install
        ```

## Usage
1. **Run the Application**:
    - Open `OtpGenerator.java` in VS Code.
    - Right-click anywhere in the editor and select `Run Java`.

2. **Expected Output**:
    ```
    Generated Numeric OTP: 839502
    Generated Alphanumeric OTP: j8K3ZmQ2
    Is OTP valid? true
    ```

3. **Run Unit Tests**:
    - You can run tests from the Test Explorer view in VS Code.
    - Alternatively, in the terminal, run:
        ```sh
        mvn test
        ```

## Project Structure
otp-generator/
|-- src/
|   |-- main/
|   |   |-- java/
|   |   |   |-- com/
|   |   |   |   |-- otp/
|   |   |   |   |   |-- OtpGenerator.java
|   |   |   |   |   |-- OtpValidator.java
|   |-- test/
|       |-- java/
|           |-- com/
|               |-- otp/
|                   |-- OtpGeneratorTest.java
|                   |-- OtpValidatorTest.java
|-- pom.xml
|-- README.md

## Contributing
1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature/your-feature`).
3. **Commit your changes** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature`).
5. **Open a pull request**.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
- [JUnit 5](https://junit.org/junit5/)
- [Apache Maven](https://maven.apache.org/)

*Replace "Project_1_OTP Generator" with the actual relative path to the project folder within your repository.*

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

*Replace "Project_2_Number_Guessing_Game" and descriptions with details about your specific projects.*

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
