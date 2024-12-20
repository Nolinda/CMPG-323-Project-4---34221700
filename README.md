# CMPG-323-Project-4---34221700
# Overview
This project automates the User Acceptance Testing (UAT) process for the NWU Tech Trends Telemetry Portal. It uses Robotic Process Automation (RPA) to mimic human interaction with the web application, performing repetitive data entry and validation tasks that are typically handled manually during UAT. By automating the UAT process, the bot ensures efficiency, accuracy, and speed in testing input data and validating expected outcomes before the solution is deployed to production.

# Functional Requirements
# The UAT automation bot is designed to:
1. Input Data Entry: Enter test dataset values into the appropriate fields on the web application.
2. Record Verification: Verify that new records are created and displayed as expected after submission.
3. Output Validation: Ensure that the output of the test matches the expected output.
4. Error Handling: Report any discrepancies between actual and expected results, indicating areas that need further review before deployment.
How to Use the Bot

# Before using the bot, ensure the following:
1. UiPath Studio/Robot Installed: The bot has been developed using UiPath and requires UiPath Studio or the UiPath Robot to execute.
2. Access to the Web Application: Ensure the NWU Tech Trends Telemetry Portal is accessible, and the test environment is ready.
3. Test Dataset: A test dataset containing input and expected output data should be prepared for the UAT process.
   
# Steps to Run the Bot
Open the UiPath Project: Clone the GitHub repository and open the project in UiPath Studio.

Navigate to the UAT_Automation.xaml file.
# Input the Test Data:

Place the test dataset in the designated folder (/Data/TestData.xlsx).
Ensure the dataset has columns matching the fields of the web application (e.g., Date Onboarded, Client Name, etc.).
# Run the Automation:

Execute the bot by running the Main.xaml file or deploying it through UiPath Orchestrator.
The bot will begin entering data into the web application and verifying that records are added successfully.

#Output Verification:

After the automation completes, the bot will generate a report (/Reports/UAT_Report.xlsx) detailing the test results, including:
1. Input Data: What was entered into the application.
2. Expected Output: The expected result for each test case.
3. Actual Output: The actual result generated by the web application.
4. Status: Whether each test passed or failed.
   
# Error Handling and Logs
If an error occurs during execution, the bot will log the issue and capture a screenshot.
The logs are saved in /Logs/ExecutionLogs.txt for review.
# Conclusion
The UAT automation bot for the NWU Tech Trends Telemetry Portal is designed to streamline and automate the acceptance testing process, ensuring all necessary test cases are executed efficiently and with consistent results. By leveraging RPA, stakeholders can focus on more complex testing while the bot handles repetitive tasks.
