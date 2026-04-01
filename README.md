# 🎓 Student Management System - System Design & Architecture
> **A complete architectural breakdown and implementation of a Student Management System, featuring structured DFDs, Sequence Diagrams, and Class Diagrams.**

<div align="center">

![Architecture](https://img.shields.io/badge/Architecture-Clean_Code-blue?style=for-the-badge)
![Diagrams](https://img.shields.io/badge/Diagrams-UML_&_DFD-success?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-PHP_API-777BB4?style=for-the-badge&logo=php&logoColor=white)

</div>

---

### 🌟 Overview
This project demonstrates the full lifecycle of a **Student Management System**, from high-level requirements to detailed system architecture. The focus here is on the **Data Flow** and **Structural Design**, ensuring a scalable and maintainable CRUD application using PHP and JSON/Database storage.

---

### 📊 System Architecture & Diagrams
The system's logic is documented through several professional diagrams to ensure clear understanding of the data flow and component relationships:

#### 1. Data Flow Diagrams (DFD)
* **DFD Level 0:** High-level interaction between the User and the System via Student Data and JSON Responses.
* **DFD Level 1:** Detailed breakdown of core processes: **Save Student**, **Read Students**, and **Delete Student**.
* **DFD Level 2:** Granular view of sub-processes like **Data Validation**, **Database Insertion**, and **Record Updating**.

#### 2. UML Class Diagram (CRUD)
The system follows a modular API-based approach:
* **SaveStudentAPI:** Handles insertion and updates.
* **ReadStudentAPI:** Manages data retrieval (`getAllStudents`).
* **DeleteStudentAPI:** Handles record removal.
* **Database & Config:** Centralized classes for PDO connection and system configuration.

#### 3. Sequence & Activity Diagrams
* **Sequence Diagram:** Illustrates the lifecycle of a PHP Script (DB Config) from loading credentials to returning connection results.
* **Activity Diagram:** Shows the decision-making process during database connection attempts and error handling.

---

### 🚀 Key Functional Workflows
1. **Student Registration:** User inputs data -> Validation -> Storage in `Students DB` -> Success Response.
2. **Data Retrieval:** Request for data -> Fetching from DB -> Conversion to JSON -> Display in Browser.
3. **Data Maintenance:** Validating IDs before performing Delete or Update operations to ensure data integrity.

---

### 🛠️ Technical Implementation
* **Language:** PHP (Server-side logic).
* **Data Format:** JSON for API communication.
* **Database Access:** PDO (PHP Data Objects) for secure database interactions.
* **Frontend-Backend Bridge:** Browser-based requests interacting with specific API endpoints.

---

### 📂 Diagrams Folder
You can find the high-resolution architectural diagrams in the `/diagrams` folder of this repository. These were designed to map the system's logic before the coding phase.

---

### 👤 Author
**Youssef Alkamashany**
* 🎓 **Computer Science Student** | Modern Academy.
* 🚀 **Aspiring LLMOps / AI Platform Engineer**.
* 💼 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/youssef-alkamashany/)

---
<p align="center">Built with precision, documented with clarity. 🛠️📖</p>
