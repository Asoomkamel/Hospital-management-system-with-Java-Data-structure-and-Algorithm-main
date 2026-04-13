# Hospital Management System with Java Data Structures and Algorithms

## Description
This project implements a basic Hospital Management System using Java, focusing on fundamental data structures and algorithms. The system provides a console-based interface for managing doctors, patients, and their check-up appointments. It demonstrates the application of linked lists for storing and retrieving information efficiently.

## Features
-   **Doctor Management**: Add new doctors with ID, name, contact, specialty, and fees.
-   **Patient Management**: Add new patients with ID, name, and contact information.
-   **View Records**: Display lists of all registered doctors and patients.
-   **Check-up Scheduling**: Assign patients to doctors for check-ups, with priority levels (Emergency, Intermediate, Normal).
-   **Recommendation System**: Allows for adding recommendations for patients after their check-up.

## Project Structure
```
Hospital-management-system-with-Java-Data-structure-and-Algorithm-main/
├── build/                  # Compiled Java classes
├── nbproject/              # NetBeans project files
└── src/                    # Source code directory
    └── curalli/            # Main package for the application
        ├── Checkup.java    # Represents a check-up appointment
        ├── CheckupList.java# Implements a priority queue for check-ups using a linked list
        ├── CNode.java      # Node for CheckupList
        ├── Curalli.java    # Main application class with console menu
        ├── Doctor.java     # Represents a doctor
        ├── DoctorsList.java# Implements a linked list for managing doctors
        ├── DNode.java      # Node for DoctorsList
        ├── Patient.java    # Represents a patient
        ├── PatientList.java# Implements a linked list for managing patients
        └── PNode.java      # Node for PatientList
```

## Technologies Used
-   Java Development Kit (JDK)
-   Fundamental Data Structures (Linked Lists, Priority Queues)

## How to Run
This project was likely developed using NetBeans IDE. To compile and run it:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Asoomkamel/Hospital-management-system-with-Java-Data-structure-and-Algorithm-main.git
    cd Hospital-management-system-with-Java-Data-structure-and-Algorithm-main
    ```
2.  **Compile the Java files**:
    If using NetBeans, open the project directly. Otherwise, you can compile from the command line:
    ```bash
    javac -d build/classes src/curalli/*.java
    ```
3.  **Run the application**:
    ```bash
    java -cp build/classes curalli.Curalli
    ```
    Follow the on-screen menu to interact with the system.

---

## 👥 Team Members
Developed as part of the **Electrical Machines Project** at **Sana'a University**:
- **Mutasim Al-Kamil** ([GitHub](https://github.com/Asoomkamel) | [LinkedIn](https://www.linkedin.com/in/mutasim-al-kamil-40a299318))
- **Osama Mohammed Maudha**
