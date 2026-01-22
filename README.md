# Web Application Automation Bot – UiPath (Modern Design)

## Project Overview

This project automates a web-based data entry process using UiPath Modern Design Experience.
The bot reads input data from an Excel file and submits it into a web application form dynamically, with proper exception handling and logging.

The automation follows real-world RPA best practices such as configuration management using UiPath Orchestrator Assets and structured workflow design.

## Business Use Case

Manual web form filling is time-consuming and error-prone.
This automation eliminates repetitive manual work by:

* Reading structured data from Excel
* Automatically entering data into a web application
* Ensuring consistency, accuracy, and efficiency

## Technologies & Tools Used

* UiPath Studio (Modern Design Experience)
* UiPath Orchestrator (Text Asset)
* Web Automation (Modern UI)
* Excel Automation (Modern Excel)
* Exception Handling and Logging

## Functional Workflow

1. Fetches website URL from UiPath Orchestrator using a Text Asset
2. Reads input data from an Excel file
3. Opens the web application in a browser
4. Iterates through each record from Excel
5. Enters data dynamically into the web form
6. Submits the form and logs the transaction status
7. Handles system exceptions gracefully

## Project Structure

```
WebAutomationBot_Modern
│── Main.xaml
│── Data
│   └── Input.xlsx
│── Screenshots
│── README.md
```


## Orchestrator Configuration

* Asset Name: WebBot_URL
* Asset Type: Text
* Purpose: Externalize web application URL for easy configuration


## Key Features

* Uses UiPath Modern Activities only
* Dynamic selectors for web elements
* Excel-driven automation
* Try–Catch based exception handling
* Configurable URL using Orchestrator Asset
* Informative logging for monitoring and debugging


## Outcome

* Successfully automated repetitive web data entry tasks
* Improved accuracy and processing speed
* Built a scalable and maintainable automation workflow

## Learning Outcomes

* Hands-on experience with UiPath Modern Design
* Web automation using dynamic selectors
* Orchestrator asset integration
* Real-world RPA workflow structuring


## Author

Arthidevi R
Aspiring RPA Developer | UiPath | Automation Enthusiast

