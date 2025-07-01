# DemoBlaze E-commerce Testing Suite

## Overview
This repository contains comprehensive testing documentation and artifacts for the DemoBlaze E-commerce Platform (https://www.demoblaze.com/). The project encompasses requirements analysis, user story creation, functional, usability, and regression testing, defect management, release reporting, and migration to JIRA. The goal is to ensure the platform's functionality, usability, and reliability while enhancing traceability and decision-making through structured processes.

The testing was conducted by **Rawan Ellsayed** as part of the **SprintUp - Introduction to Testing** course (Certificate ID: SPR-94131W).

## Repository Contents
The repository includes the following files and folders:
- **Requirements_Analysis/**:
  - **User_Stories.xlsx**: Defines user stories with acceptance criteria.
  - **User_Story_Issues.docx**: Lists ambiguities and improvement suggestions.
- **Test_Design/**:
  - **Test_Scenarios.xlsx**: Contains test scenarios for key functionalities.
  - **Functional_Test_Cases.xlsx**: Includes functional test cases covering edge cases and failures.
- **Testing_Execution/**:
  - **Functional_Test_Report.docx**: Summarizes test execution results.
  - **Defect_Logs.xlsx**: Logs defects identified during testing.
- **Usability_Testing/**:
  - **Usability_Report.docx**: Evaluates navigation, clarity, and accessibility.
- **Release_Management/**:
  - **Release_Report.docx**: Summarizes testing outcomes and readiness assessment.
  - **Release_Enhancements_Proposal.pptx**: Proposes enhancements for deployment.
- **Regression_Testing/**:
  - **Regression_Strategy.xlsx**: Outlines the regression testing strategy for the "Product Filters" feature.
- **JIRA_Migration/**:
  - **Excel_to_JIRA_Traceability_Screenshot.png**: Shows traceability in JIRA.
  - **Bulk_Import_CSV.csv**: Facilitates bulk import to JIRA.
- **Test Process Overview.pdf**: Describes the structured test process phases.
- **All_Tests_Issues.csv**: Lists all identified issues, including bugs and tasks.
- **downloaded.pdf**: Certificate of completion for the SprintUp testing course.
- **Project Board Screenshot**: An image of the DemoBlaze_Project board showing task statuses.

## Project Objectives
- Analyze requirements and create user stories.
- Conduct functional, usability, and regression testing.
- Manage defects and generate release reports using Excel and JIRA.
- Ensure traceability from requirements to testing and defect management.
- Enhance testing artifacts for better decision-making.

## Tools Used
- **Microsoft Excel**: Initial documentation and migration source.
- **JIRA**: Test and defect management.
- **Xray for JIRA**: Test case management.
- **Equivalence Partitioning & Boundary Value Analysis**: Test design techniques.

## Test Process Summary
The testing process follows a structured methodology:
1. **Test Planning**: Defines scope, objectives, resources, and criteria.
2. **Monitoring and Control**: Tracks progress and adjusts as needed.
3. **Test Analysis**: Identifies test conditions based on requirements.
4. **Test Design**: Creates test cases using BVA and EP techniques.
5. **Test Implementation**: Prepares test suites and environments.
6. **Test Execution**: Runs test cases and logs results.
7. **Test Completion**: Evaluates criteria and documents outcomes.

### Key Findings
- **Functional Testing**: All 5 test cases passed, but payment validation issues persist (see `Functional_Test_Report.docx`).
- **Usability Issues**: Identified high-severity issues like missing input validation (see `Usability_Report.docx`).
- **Defects**: Critical defects include invalid payment acceptance and cart interface inaccuracies (see `Defect_Logs.xlsx` and `All_Tests_Issues.csv`).
- **Regression Testing**: "Product Filters" affects product listing, cart, and checkout; automation recommended for RT_002 and RT_004 (see `Regression_Strategy.xlsx`).
- **Project Status**: The project board shows tasks like "No Validation for Payment Fields" (OPEN) and "Add Filtered Product to Cart" (IN PROGRESS) (see project board image).

## Project Board
![DemoBlaze Project Board](attachment://DemoBlaze_Project_board.png)
- **Status Overview**: Tracks tasks like login fails, payment validation, and product filtering.
- **Last Updated**: July 01, 2025, 11:25 PM EEST.

## Setup Instructions
To use or review the testing artifacts:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/demoblaze-testing-suite.git
