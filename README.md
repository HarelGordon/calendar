# JavaFX Calendar App

A lightweight desktop calendar application built with Java, JavaFX (FXML), and Maven.

## 🚀 Features
- **Monthly View**: Clean visual layout for date navigation.
- **Event Management**: Interface for viewing and managing events.
- **MVC Architecture**: Clean separation between UI (`.fxml`), application controller, and business logic.
- **Zero-Config Setup**: Includes Maven Wrapper – no manual JavaFX SDK installation or path configuration required.

## 🛠️ Built With
- **Java 21**
- **JavaFX 21** (FXML layout)
- **Maven** (with Maven Wrapper)

## 📁 Project Structure
```text
Calendar/
├── .mvn/
├── mvnw
├── mvnw.cmd
├── pom.xml
├── README.md
├── .gitignore
└── src/
    └── main/
        ├── java/
        │   ├── CalendarMain.java
        │   ├── CalendarController.java
        │   └── Logic.java
        └── resources/
            └── calendar.fxml
```


## 🏁 Getting Started

### Prerequisites
* **Java Development Kit (JDK 21 or higher)**

### Running the Application
Open your terminal, navigate to the project root directory, and run:

```bash
./mvnw javafx:run
```
