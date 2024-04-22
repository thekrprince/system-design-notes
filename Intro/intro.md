# **System Design Guide**

## Why System Design?

- System design is a critical phase in the development process of any complex software or hardware system. It involves the process of defining the architecture, components, modules, interfaces, and data for a system to satisfy specified requirements.

## Architectural characteristics of web-based applications

- Some web-based applications use a two-tier architecture, and some use the n-tier architecture that consists of three or more tiers.

  1. **2-tier architecture:** A 2-tier architecture, also known as a two-tier architecture, is a software architecture model that consists of two main components or layers: the client and the server. In this architecture, the client is responsible for the user interface and application processing, while the server handles the data storage and database management. Here's a simple breakdown of the two tiers:

     a. Client Tier (Front-end):

     - This tier represents the user interface and application logic that runs on the user's device, typically a personal computer or workstation.
     - The client is responsible for presenting information to the user, capturing user inputs, and processing some aspects of the application's logic.
     - In a 2-tier architecture, the client communicates directly with the server for data retrieval and storage operations.

     b. Server Tier (Back-end):

     - The server tier is responsible for managing data storage, processing data-related operations, and handling database management tasks.
     - It interacts with the database to retrieve and store data based on the requests from the client.
     - The server performs the back-end processing and executes business logic, responding to requests from the client.

     In a 2-tier architecture, the communication between the client and the server typically involves direct interactions. For example, when a user interacts with the client-side application, such as entering data or requesting information, the client sends a request directly to the server. The server processes the request, interacts with the database if necessary, and sends back the results to the client.

     While 2-tier architectures are straightforward and easy to implement, they may have limitations in terms of scalability and maintenance, especially for large and complex systems. As a result, more modern architectures, such as 3-tier and n-tier architectures, have become popular to address these scalability and maintenance challenges.

  2. **3-tier architecture:** It is a software architecture model that divides an application into three interconnected components or tiers, each responsible for specific functions. The three tiers in this architecture are the presentation tier (client), the application or logic tier, and the data tier.

     a. **Presentation Tier (Client):**

     - This tier represents the user interface and user interaction components. It's the part of the application that users directly interact with.
     - The client tier is responsible for presenting information to users, capturing user inputs, and providing a graphical interface for interaction.
     - It communicates with the application tier to request and receive data, as well as to execute specific application functions.

     b. **Application Tier (Logic Tier):**

     - The application tier, also known as the logic tier or middle tier, contains the business logic and application processing.
     - It processes and executes application-specific logic, handling tasks such as validation, calculations, and workflow management.
     - The application tier communicates with both the presentation tier (client) and the data tier (server) to retrieve and manipulate data as needed.

     c. **Data Tier (Server):**

     - The data tier is responsible for managing data storage, retrieval, and database management.
     - It stores and retrieves data from a database based on requests from the application tier. This tier is often referred to as the database server.
     - The data tier ensures data integrity, security, and efficient storage and retrieval

  3. **n-tier architecture:**
