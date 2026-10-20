# YOUTH OFFENDERS IN BRISTOL WARD: AN INTERACTIVE DATA VISUALIZATION WEB APPLICATION

## Business Case

### Problem statement
The availability of open data provides opportunities to explore social issues and understand differences between geographical areas. However, raw statistical datasets can be difficult for users to interpret, particularly when comparing multiple areas or examining how recorded figures change over time. 
This project proposes the development of an interactive HTML web application using the Youth Offenders in Bristol by Ward dataset. The dataset contains records covering reporting periods from 2016/17 to 2025/26, providing information that can be explored to identify differences between Bristol's wards and patterns across the available reporting periods. 
The proposed application will address the challenge of interpreting and comparing the available statistics by presenting the information through appropriate charts, graphs and summaries. Users will be able to compare recorded figures and rates between wards, select different reporting periods and explore patterns within the dataset through an interactive interface. 
The aim is to make the information more accessible and easier to understand for students, researchers and other interested members of the public. The application will focus on accurately presenting the available data while acknowledging its limitations, including any missing or inconsistent values. It will support the exploration of recorded statistics but will not assume that observed patterns establish the causes of youth offending or predict future outcomes. 

### Business benefits
The proposed Youth Offenders in Bristol by Ward web application will provide a more accessible and interactive way to explore youth-offending statistics across Bristol. By transforming the supplied dataset into visual representations, the application aims to make the information easier to understand, compare and interpret. 
The anticipated benefits of the application include the following: 
1. Improved Data Visualisation 
The application will present statistical information through charts, graphs and summaries. This will help users interpret the data without having to examine every row of the original dataset manually. 
2. Easier Comparison Between Wards 
Users will be able to compare the recorded youth-offending figures and rates across different wards in Bristol. This will make differences between geographical areas easier to identify and investigate. 
3. Exploration of Patterns Over Time 
Because the supplied dataset contains reporting periods from 2016/17 to 2025/26, the application will allow users to explore how the available statistics differ across those periods. This may help users identify patterns or changes in the recorded figures, subject to the completeness and consistency of the data. 
4. Improved Accessibility of Information 
Presenting the statistics through a clear and user-friendly interface will make the dataset easier to explore for users who may not have experience working directly with spreadsheets or analysing raw data. 
5. Support for Education and Research 
Students, researchers and other interested users may use the application to explore the available statistics, compare wards and develop questions for further investigation. The application will provide a visual means of exploring the data rather than requiring users to process the original dataset manually. 
6. Efficient Data Exploration 
Interactive features, such as selecting a ward or reporting period, will help users focus on the information relevant to their interests. This could reduce the effort required to locate and compare particular figures within the dataset. 
Overall, the proposed application aims to improve the usability and interpretability of the supplied youth-offending statistics. Its value will depend on the accuracy of the data presentation, the usefulness of its interactive features and how effectively users can understand the information displayed. 

### Options Considered
Before developing the proposed application, it is important to consider alternative ways of presenting and exploring the Youth Offenders in Bristol by Ward dataset. Evaluating different solutions will help determine which approach is most suitable for the project's objectives, available resources and intended users.
Three possible solutions have been identified.
Option A: Using the Original Spreadsheet
The first option is to retain the dataset in its original spreadsheet format. Users would access the data through a spreadsheet application and manually examine the records to compare wards and reporting periods.
Advantages:
•	Requires little or no additional development.
•	Preserves the original data structure.
•	Allows users familiar with spreadsheets to inspect individual records.
Disadvantages:
•	Users may need to examine numerous rows to identify relevant information.
•	Comparing multiple wards and reporting periods may require additional manual work.
•	Users without spreadsheet or data-analysis experience may find the information difficult to interpret.
•	The presentation is less interactive and visually accessible than a purpose-built dashboard.
Option B: Creating a Static Report
The second option is to create a report containing charts, graphs and written summaries derived from the dataset. The report could be produced as a PDF document or another fixed-format publication.
Advantages:
•	Presents statistical information in a structured and visually clear format.
•	Allows readers to understand key findings without examining the raw dataset.
•	Can be distributed easily as a document.
•	Requires less interactive functionality than a web application.
Disadvantages:
•	Users cannot dynamically change the displayed reporting period or ward unless multiple views are prepared in advance.
•	Exploring specific combinations of wards and reporting periods may be difficult.
•	Updating the report when the underlying data changes may require producing a new version.
•	Users have limited opportunities to explore the data beyond the information selected by the report's author.
Option C: Developing an Interactive HTML Web Application
The third option is to develop an interactive HTML web application that presents the dataset through charts, graphs, summaries and user-controlled filters.
Users would be able to explore available reporting periods, compare statistics between Bristol's wards and investigate patterns in the recorded data through a single interface.
Advantages:
•	Enables interactive exploration of the dataset.
•	Allows users to compare wards and reporting periods more conveniently.
•	Presents statistical information through visualizations that may be easier to understand than raw tables.
•	Can combine several visualization types and interactive features within one application.
•	Provides opportunities to improve the interface and add features as development progresses.
Disadvantages:
•	Requires development, testing and maintenance.
•	May require additional JavaScript libraries to implement charts and interactive features.
•	Incorrect data processing or poorly designed visualizations could misrepresent the statistics.
•	The application must be designed to handle missing values and differences in data completeness across reporting periods.
Comparison of the Alternatives
The three options differ in their interactivity, development requirements and ability to support exploration of the dataset.
The original spreadsheet is the simplest option to maintain, but it places more responsibility on users to interpret the information. A static report improves the presentation of selected findings but offers limited opportunities for users to investigate the data independently. An interactive HTML web application requires more development effort but provides greater flexibility for comparing wards and exploring reporting periods.
Preferred Solution
The interactive HTML web application is the preferred option for this project because it aligns with the objective of making youth-offending statistics easier to explore, compare and interpret.
The application will combine visual presentation with interactive features, allowing users to investigate the available data rather than being restricted to predefined tables or charts. HTML, CSS and JavaScript are proposed as the core technologies for developing the interface and its interactive functionality.
The final choice will be further justified through the evaluation of relevant selection criteria, including functionality, usability, development effort and suitability for the project requirements.


### Expected Risks
The development of the proposed Youth Offenders in Bristol by Ward: An Interactive Data Visualization Web Application will involve both financial and non-financial costs. These costs must be considered during the planning stage to determine whether the proposed solution is practical and achievable within the project's available resources.
Development Costs
The application is planned to be developed using HTML, CSS and JavaScript. These technologies can be used without purchasing software license, helping to minimize the direct financial cost of development. A standard web browser and a suitable code editor can be used to develop and test the application.
Data Costs
The project will use the existing Youth Offenders in Bristol by Ward dataset. If the dataset remains freely available from its original source, no purchase cost will be required. Time will still be needed to inspect, clean and prepare the data for use in the application.
Hosting and Deployment Costs
During development, the application can be tested locally on a computer, avoiding the need for paid hosting. If the project needs to be published online, a suitable hosting service may be required. The final cost will depend on the hosting option selected and the project's deployment requirements.
Time and Resource Costs
Although the proposed technologies may be free to use, development will require time for planning, data preparation, interface design, implementation, testing and documentation. This represents a non-financial cost because time and effort must be allocated to complete the project successfully.
Contingency
A contingency allowance should be considered to accommodate unexpected expenses or changes in requirements. The project lecture suggests that a contingency of approximately 25–30% may be added to estimated costs. Since the project is expected to use free development tools and may not require paid hosting, the direct financial costs are expected to be low. Any contingency allowance should therefore be calculated once the actual costs have been identified.
Overall, the proposed application is expected to be relatively inexpensive to develop because it will use existing data and commonly available web technologies. The main resources required will be the time and effort needed to prepare the data, design the application, test its functionality and complete the project documentation. The final cost estimate will depend on the tools and deployment arrangements selected.

## Project Scope

The project involves designing and developing an interactive web application that presents youth-offending statistics across the wards of Bristol. The application will use the available *Youth Offenders in Bristol by Ward* dataset and display the information through charts, graphs and other visual representations to make the data easier to understand.

The system will include the following features and components:

- **Data source:** Use the available dataset containing youth-offending statistics for Bristol's wards.
- **Data visualisation:** Present the available statistics through appropriate charts and graphs.
- **Ward comparison:** Allow users to compare statistics between different wards.
- **Reporting periods:** Allow users to explore the reporting periods available in the dataset.
- **User interaction:** Provide a simple interface for selecting and exploring the available data.
- **Web technologies:** Use HTML, CSS and JavaScript to develop the application.
- **User accessibility:** Design a clear, user-friendly interface that can adapt to different screen sizes.
- **Data presentation and accuracy:** Ensure that the displayed information reflects the source dataset and acknowledge relevant data limitations.
- **System maintenance:** Allow the maintainer to update or revise the application when necessary.

The project will focus on visualising and exploring existing statistical data. It will not identify individual offenders, determine the causes of youth offending or predict future offending levels.

### Context Diagram

The context diagram illustrates the proposed web application and its relationship with users, the maintainer, the data source, the technologies used and other relevant system considerations.

<img width="1536" height="1024" alt="image pro" src="https://github.com/user-attachments/assets/c5b03fd7-3241-40d3-bb03-fceed942b0d8" />

