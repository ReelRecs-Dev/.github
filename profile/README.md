# ReelRecs Organization

Welcome to the ReelRecs, a comprehensive movie recommendation system designed to provide personalized and popularity-based movie suggestions. This project is my solo endeavor, built using advanced data analytics and machine learning techniques to enhance movie discovery for users.

## Repositories
- **ReelRecs-core**: Contains all backend logic, handling functionalities such as user authentication and data management.
- **ReelRecs-webapp**: The front-end application that users interact with, built to provide a smooth and responsive experience.
- **ReelRecs-data-pipeline**: Manages automated ETL processes for integrating external data into the system.
- **ReelRecs-dashboards**: Focuses on the visualization of user data and system performance through Google Data Studio.
- **ReelRecs-legacy**: This repository hosts the original Jupyter Notebook version of the project, serving as the foundational legacy code from which the revamped ReelRecs project was derived.

## UML Diagram: System Architecture

The diagram below provides an overview of the ReelRecs architecture, showing the relationships between the key components: the **core backend**, **ETL pipeline**, **webapp**, and **dashboard**.

![ReelRecs UML Diagram](reelrecs-overview-uml.png)

### **Explanation of Components:**
- **External API**: External data sources (e.g., TMDb, IMDb) providing raw movie data.
- **Extract**: Fetches raw data from the external APIs.
- **Transform**: Cleans and processes raw data into a usable format.
- **Load**: Loads the transformed data into the core database.
- **Data Warehouse**: Optional storage for raw or intermediate data.
- **Google Cloud Dataflow**: Orchestrates the ETL process, managing extraction, transformation, and loading.
- **Controller**: Handles incoming API requests from the web app and routes them to services.
- **Service**: Contains business logic for user interactions and recommendations.
- **Model**: Represents the database structure and interacts with the database.
- **Database**: Stores processed data, including movies, users, and ratings.
- **Auth**: Manages user authentication and session security.
- **Webapp**: The frontend interface users interact with to request recommendations and view data.
- **Dashboard**: Visualizes system performance, usage metrics, and ETL statistics.

---

## Project Setup
(Include project setup instructions here)

For more details on each component, please visit the respective repositories linked above.
