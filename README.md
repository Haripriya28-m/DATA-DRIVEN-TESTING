# DATA-DRIVEN-TESTING

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HARIPRIYA M

*INTERN ID*: CT08WN211

*DOMAIN*: AUTOMATION TESTING

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

🧪 Data-Driven Testing Using Selenium & Apache POI
📌 Project Overview
This project demonstrates data-driven testing using Selenium WebDriver with Java. The test script automates the login process for a web application by reading multiple sets of test data (usernames and passwords) from an Excel file. This approach helps in efficiently testing various input combinations without modifying the test code.

⚙️ Tech Stack
Programming Language: Java

Automation Framework: Selenium WebDriver

Testing Framework: TestNG / JUnit (based on what you used)

Excel Handling Library: Apache POI

Build Tool: Maven (if used)

🗂️ Project Structure

data-driven-testing/
│
├── src/
│   └── test/java/
│       └── LoginTest.java           # Test class with login automation
│
├── testdata/
│   └── LoginData.xlsx               # Excel file with test credentials
│
├── pom.xml                          # Maven dependencies (if used)
├── README.md                        # Project documentation
└── .gitignore                       # Ignored files/folders
📋 Features
Reads login credentials from an Excel sheet

Iterates through each row of data to perform automated login

Validates login success or failure

Uses Apache POI for reading Excel data

🚀 How to Run
Clone the repository:

git clone https://github.com/Haripriya28-m/DATA-DRIVEN-TESTING.git
Open the project in your preferred IDE (e.g., IntelliJ or Eclipse).

Add necessary libraries (Selenium, Apache POI, TestNG/JUnit) via pom.xml or manually.

Place the Excel file (LoginData.xlsx) inside the testdata folder.

Run the LoginTest.java class as a TestNG or JUnit test.

📎 Sample Test Data
Username	Password
testuser1	pass123
invaliduser	wrongpass
demoUser	demo@123

# OUTPUT
![Image](https://github.com/user-attachments/assets/6c69af52-42ad-4952-bcfb-c19144a0947a)
