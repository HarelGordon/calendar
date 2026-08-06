# JavaFX Calendar App

A lightweight desktop calendar application built with Java and JavaFX (FXML).

## 🚀 Features
- **Monthly View**: Clean visual layout for date navigation.
- **Event Management**: Interface for viewing and managing events.
- **MVC Architecture**: Clean separation between UI (`.fxml`), application controller, and data model.

## 🛠️ Built With
- **Java**
- **JavaFX** (FXML layout)

## 📁 Project Structure
```text
Calendar/
├── .gitignore
├── README.md
└── src/
    ├── CalendarMain.java
    ├── CalendarController.java
    ├── Event.java
    └── calendar.fxml
```

## 🏁 Getting Started

### Prerequisites
* **Java Development Kit (JDK 11+)**
* **JavaFX SDK** (if not bundled with your JDK)

### Running the Application

#### Option 1: Via IDE (Recommended)
Import the folder into **IntelliJ IDEA**, **Eclipse**, or **VS Code**, configure JavaFX libraries if needed, and run `CalendarMain.java`.

#### Option 2: Via Terminal
```bash
cd src
javac --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml *.java
java --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml CalendarMain