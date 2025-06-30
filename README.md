##  Hospital Management System – Python

This project is a **console-based Hospital Management System** built using **Python**, demonstrating core programming concepts like **Object-Oriented Programming (OOP)** and **file handling**. It is designed to manage and streamline basic hospital operations such as adding and viewing patients and doctors, scheduling appointments, and generating bills.

The system is modularized into multiple classes to maintain clarity and scalability. The `PatientManager` and `DoctorManager` classes handle all operations related to storing and retrieving patient and doctor records, respectively. These records are saved persistently in text files (`patients.txt` and `doctors.txt`). The `AppointmentManager` allows scheduling appointments between patients and doctors with a date, and logs them into an `appointments.txt` file. The `BillingManager` is responsible for generating billing records that are stored in `bills.txt` along with timestamps.

The program runs through a menu-driven interface managed by the `HospitalSystem` class. This class acts as the central controller, allowing users to interact with the system in a simple and user-friendly manner. Each action such as adding a patient, scheduling an appointment, or generating a bill is performed through clearly separated methods under relevant classes.

This project is an excellent demonstration of practical software engineering principles like separation of concerns, encapsulation, and clean I/O operations. It is ideal for beginners looking to strengthen their understanding of Python OOP and file-based persistence. Furthermore, the system can be easily extended with advanced features such as user authentication, data validation, or integration with a database or GUI.
