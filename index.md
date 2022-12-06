# CS-499 Computer Science Capstone Final Project
## Introduction
This electronic portfolio (ePortfolio) symbolizes the culmination of my time at Southern New Hampshire University's Computer Science program. Each section represents a combination of knowledge and skill I have learned during my time in the program. It includes an informal code review, followed by a single artifact that illustrates growth in three key categories of Computer Science: Software Design and Engineering, Algorithms and Data Structures, and Databases.

### Table of Contents
1. [Professional Self Assessment](#assessment)
2. [Code Review](#review)
3. [Software Design and Engineering Artifact](#artifact-one)
4. [Algorithms and Data Structures Artifact](#artifact-two)
5. [Databases Artifact](#artifact-three)
6. [Artifact Download Link](#download)

### 1. Professional Self Assessment <a name="assessment" />
TBD

### 2. Code Review <a name="review" />

Click to watch:
[![Watch the video](https://github.com/cclayton02/cclayton02.github.io/blob/main/assets/img/code-review-thumb-01.png)](https://drive.google.com/file/d/1IzdhSWAnm-K2svdBZef5wZcRewwbmWQG/view?usp=share_link)
Original Artifact Link - [MonitoringSystem.zip](https://github.com/cclayton02/cclayton02.github.io/tree/main/assets/zip/MonitoringSystem.zip)

This video presentation reflects a code analysis process for my selected artifact, an Animal Monitoring System created as part of the final project for the course IT-145 Foundation in App Development. It is a console-based application written using the Java programming language. This presentation walks through the application's existing functionality, analyzes the code's structure based on a set of checklist items, and discusses potential enhancements that can satisfy the course outcomes.

### 3. Software Design and Engineering Enhancement <a name="artifact-one" />
#### Convert to Blazor Web Application

<img src="assets/img/enhancement-one-thumb-01.png" alt="Thumbnail - Blazor Web Application" width="600"/>

_Description_

The first artifact represents a standalone web application that takes the original Animal Monitoring System code in Java and ports the functionality to a Blazor Application written using a combination of HTML/CSS and C#.

_List of Enhancements Performed:_

* Transfer code/data from the original Java application to a C# web application
* Create a working application that will support other enhancements
* New version of the application still satisfies the original project requirements
* Ability to switch between Animal/Habitat display
* Detailed information panel for each grouping
* Displays an alert warning, if one is present

This artifact enhancement demonstrates an ability to use the SDLC to iteratively take the components from one version of an application into another and ensure each piece works as expected before moving on to the next component. I performed careful planning and analysis in the early stages with proposed documentation and code review. I used this stage to focus on the design and efficient implementation of the new application using industry-standard patterns such as model-view-controller (MVC). I also prepared the project to be maintainable using heavily-documented code.

### 4. Algorithms and Data Structures Enhancement <a name="artifact-two" />
#### Class Abstraction and Unit Tests

<img src="assets/img/enhancement-two-thumb-01.png" alt="Thumbnail - Blazor Web Application" width="600"/>

_Description_

This artifact represents enhancements to the Animal Monitoring System Web Application's Data Structures and Algorithms by building off the previous enhancement work and replacing the original DataFile class and methods with a more object-oriented design. The use of objects allows the ability to validate data structures via Unit Tests and sets up additional work for interaction with a database module.

_List of Enhancements Performed:_

* Replaced DataFile class with more intuitive abstractions for Animals/Habitats, including Models and Services
* Used abstractions to pull and display monitoring information efficiently.
* Validated new data structures with Unit Tests
* Included exception handling to address data errors/missing data
* Prepared for future database work through the use of mock data

The skills and outcomes demonstrated by the work performed at this stage include the reduction of bugs and security vulnerabilities present in the original program by rewriting unoptimized code to feature more abstractions. In addition, I promoted data validation via unit tests and ensured that the new models / services satisfied the original data requirements. Finally, I have created robust and future-proof data structures / components to support other systems or models, if needed at a future date.

### 5. Databases Enhancement <a name="artifact-three" />
#### SQL Server Interface

<img src="assets/img/enhancement-three-thumb-01.png" alt="Thumbnail - Blazor Web Application" width="600"/>

_Description_

The final enhancement for this artifact represents an additional program to support the Animal Monitoring System in the form of a database module that uses APIs to pass data from a SQL Server to the Blazor Application and vice versa. It completes the final issue with the original artifact’s design by replacing plain text data files with a database that the application can use to interact.

_List of Enhancements Performed:_
* Developed a new Server Application that uses REST API
* API serves as a module for Applications to perform CRUD operations
* Created a running SQL database to service the API Server
* Built new forms to support CRUD functions for the Blazor Application

This enhancement demonstrates the ability to create a working database with authentication that bypasses flaws in the security of the original program’s design. It incorporates working CRUD operations into the Web Application and includes some final steps for iteration. I have also validated my architectural design for the Web Application by handling and validating data through an API server.

### 6. Final Project - Artifact Download Link <a name="download" />

[GitHub Page - MonitoringSystemBlazorServer](https://github.com/cclayton02/MonitoringSystemBlazorServer)

[MonitoringSystemBlazorServer.zip](https://github.com/cclayton02/cclayton02.github.io/tree/main/assets/zip/MonitoringSystemBlazorServer.zip)


