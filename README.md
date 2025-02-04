Selenium 4 with Gradle Project

This project demonstrates how to set up and run Selenium 4 tests using Gradle as the build tool.

Table of Contents
	•	Prerequisites
	•	Project Structure
	•	Setup Instructions
	•	Running Tests
	•	Dependencies
	•	Contributing
	•	License

Prerequisites

Before you begin, ensure you have the following installed:
	•	Java Development Kit (JDK) 11 or higher: Download JDK
	•	Gradle: Download Gradle

Project Structure

The project follows a standard Gradle structure:

selenium4-gradle/
├── .idea/                  # IntelliJ IDEA project settings
├── gradle/
│   └── wrapper/            # Gradle wrapper files
├── src/
│   └── main/
│       └── java/
│           └── org/
│               └── testautomation/
│                   └── AppTest.java  # Sample test class
├── .gitignore              # Git ignore file
├── build.gradle.kts        # Gradle build script in Kotlin
├── gradlew                 # Unix Gradle wrapper script
├── gradlew.bat             # Windows Gradle wrapper script
└── settings.gradle.kts     # Gradle settings script in Kotlin

Setup Instructions
	1.	Clone the Repository:

git clone https://github.com/NickBaynham/selenium4-gradle.git
cd selenium4-gradle


	2.	Build the Project:
Use the Gradle wrapper to build the project:

./gradlew build

This command will download necessary dependencies and compile the project.

Running Tests

To execute the Selenium tests:

./gradlew test

Test reports will be generated in the build/reports/tests/test directory.

Dependencies

The project uses the following dependencies:
	•	Selenium 4: For browser automation.
	•	JUnit 5: For writing and running tests.

These dependencies are managed in the build.gradle.kts file.

Contributing

Contributions are welcome! Please follow these steps:
	1.	Fork the repository.
	2.	Create a new branch: git checkout -b feature/your-feature-name.
	3.	Make your changes.
	4.	Commit your changes: git commit -m 'Add some feature'.
	5.	Push to the branch: git push origin feature/your-feature-name.
	6.	Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Note: This documentation is based on the standard structure and practices for a Selenium project using Gradle. Adjustments may be necessary based on specific project configurations.
