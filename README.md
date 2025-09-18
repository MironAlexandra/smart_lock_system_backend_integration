Smart Lock Project – Backend
============================

About the Project
-----------------

This backend was developed during **Integration 3** (Academic Year 2024–2025, KdG University) as part of an **academic group project**. The business purpose was to implement a **Smart Lock system** where user access could be managed centrally while integrating with an Arduino device that controls the physical lock.

The backend validates RFID tags scanned on the Arduino, manages user accounts, and enables **remote unlocking commands**.

Although it was a **team effort**, I personally contributed significantly to the **backend logic, API design, and data handling**.

My Contributions
----------------

*   Designed and implemented the **REST API** for communication between Arduino and backend.
    
*   Built **user management** (registration, validation of RFID tags, access roles).
    
*   Developed the **Spring Boot service layer** following clean architecture principles.
    
*   Integrated with **PostgreSQL** for persistence.
    
*   Wrote **documentation** explaining API endpoints and integration steps with Arduino.
    
*   Participated actively in **Agile sprints**: user stories, sprint demos, and GitLab issue tracking.
    

Technologies Used
-----------------

*   **Backend:** Java 21, Spring Boot (3-layer architecture), Hibernate ORM
    
*   **Database:** PostgreSQL
    
*   **Security:** Role-based validation for RFID tag access
    
*   **Deployment & Build:** Gradle, Docker (dev), GitLab CI/CD
    
*   **Integration:** REST API endpoints for Arduino communication
    

Agile Process
-------------

We worked in **Scrum-inspired iterations** with:

*   User stories in GitLab board
    
*   Sprint planning & demos
    
*   Buddycheck peer reviews
    
*   Shared code ownership and continuous refactoring
    

Relation to Arduino Repo
------------------------

This backend is fully integrated with the Arduino repository:

*   The Arduino sends **RFID tag scans** to the backend for validation.
    
*   The backend can send **remote unlock commands** to the Arduino.
    

How to Run
----------

### Prerequisites

*   Java 21
    
*   PostgreSQL
    

### Steps

`   ./gradlew bootRun   `

Default config: see application.properties.

Contact
-------

📧 [mariaalexandra.mirongavril@student.kdg.be](mailto:mariaalexandra.mirongavril@student.kdg.be)
