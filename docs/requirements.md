# Requirements

## User Needs

### User stories
The following user stories describe how different users will interact with the system.

1. Student

   As a student, I want to view youth-offending statistics across Bristol wards so that I can understand and use the information for academic research.

2. Researcher

   As a researcher, I want to compare youth-offending statistics between different wards so that I can identify patterns and differences.

3. Community Organisation

   As a community organisation, I want to access youth-offending information in different wards so that I can better understand the issues affecting local communities.

4. Council Staff

   As a council staff member, I want to view statistics for different Bristol wards so that I can understand the distribution of youth offending across the area.
### Actors
Actors are the people or external systems that interact with the application to achieve a particular goal.

Student- Uses the application to view and understand youth-offending statistics for academic purposes.

Researcher- Uses the application to explore and compare statistics across different Bristol wards.

Community Organisation- Uses the available information to understand youth-offending patterns within local communities.

Council Staff- Accesses the statistics to understand youth-offending information across Bristol wards.

Note: These actors do not need separate accounts because the application will not have a login or registration feature.

### Use Cases
UC1 – View Dashboard
*Description: Allows users to access the dashboard and view an overview of youth crime statistics in Bristol.

*Actors: General User, Researcher, Council Officer

*Assumptions: The user has access to the dashboard and the dataset has been loaded successfully.

*Steps	1. User opens the dashboard. 2. System loads the available statistics. 3. System displays an overview of the youth crime data.

*Variations: If the data cannot be loaded, the system displays an error message.

*Non-functional: The dashboard should load within a reasonable amount of time.

*Issues: None currently identified.

UC2 – View Ward Statistics
*Description: Allows users to view youth offender counts, estimated population and offending rates for individual Bristol wards.

*Actors: General User, Researcher, Council Officer

*Assumptions: The dataset contains the relevant ward information.

*Steps	1. User selects a ward. 2. System retrieves the ward's statistics. 3. System displays the information to the user.

*Variations: If a ward is not available, the system informs the user.

*Non-functional: Statistics should be displayed clearly and accurately.

*Issues: The available dataset covers the 2016/17 period.

UC3 – Search for a Ward
*Description: Allows users to search for a specific Bristol ward to find its youth crime statistics.

*Actors: General User, Researcher, Council Officer

*Assumptions: The ward exists in the dataset.

*Steps	1. User enters a ward name in the search field. 2. System checks the dataset. 3. System displays the matching ward and its statistics.

*Variations: If no matching ward is found, the system displays a message.

*Non-functional: Search results should be returned quickly.

*Issues: None currently identified.

USE CASE DIAGRAM
<img width="1536" height="1024" alt="Use Case Diagram" src="https://github.com/user-attachments/assets/a5c28b9a-1f8c-4f90-89be-8687ec783d9e" />


## Software Requirements Specification
### Functional requirements
Functional requirements describe the specific functions the system must perform to meet users' needs.

*FR1	The system shall allow users to access and view the main dashboard.	UC1

*FR2	The system shall display an overview of available youth crime statistics in Bristol.	UC1

*FR3	The system shall retrieve and display youth offender counts for individual Bristol wards.	UC2

*FR4	The system shall display the estimated population for each selected ward.	UC2

*FR5	The system shall display the offending rate for each selected ward.	UC2

*FR6	The system shall allow users to enter a ward name into a search field.	UC3

*FR7	The system shall search the dataset for a matching ward name.	UC3

*FR8	The system shall display the matching ward and its available statistics.	UC3

*FR9	The system shall display an appropriate message when a requested ward cannot be found.	UC2, UC3

*FR10	The system shall display an error message when the dataset cannot be loaded.	UC1

### Non-Functional Requirements
Non-functional requirements describe the quality, performance and usability of the application.

*NFR1	Usability: The system shall provide a simple and user-friendly interface that allows users to navigate the dashboard easily.	UC1, UC2, UC3

*NFR2	Performance: The system shall load dashboard information and return ward search results within a reasonable amount of time.	UC1, UC3

*NFR3	Reliability: The system shall display appropriate error messages when the dataset cannot be loaded or requested information is unavailable.	UC1, UC2, UC3

*NFR4 Accuracy: The system shall display statistics accurately according to the information provided in the dataset.	UC1, UC2, UC3

*NFR5	Compatibility: The system shall be accessible through commonly used modern web browsers.	UC1, UC2, UC3

*NFR6: Readability	The system shall present statistics in a clear and understandable format.	UC1, UC2

