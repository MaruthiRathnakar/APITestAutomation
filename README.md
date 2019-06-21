# APITestAutomation
Reflektion API Test Automation 
To Run This Automation Suite, Machine should be installed with python and below packages:

1) Requests
2) pyyaml
3) pytest

PyTest Automation Suite Contents:

APIFunctions Directory contains a python module by name "ApiMethods.py" which contains all the methods which perform post, get, put and delete with required Parameters
APITests Directory contains a python module by name "test_API.py" which contains Test cases for API Automation
Variables Directory contains a yaml file (Configuration file) by name ApiVariables.yaml which contains variables like Common base url,body and headers

Steps for Test Execution:

1) Download the package to your desired location
2) Open Command Prompt and change directory to the location where Automation Suite is downloaded
3) Run the Pytest command "pytest -q --html=pytest_report.html APITests/test_API.py"

Sample Execution Example :
1) Assume Reflektion package is downloaded and placed in C:\Users\Administrator location
2) Open Command Prompt and CD to C:\Users\Administrator\Reflektion
3) Run the PyTest Command "pytest -q --html=pytest_report.html APITests/test_API.py"

Output :
   Report will be generated and stored at the location C:\Users\Administrator\Reflektion
   Report name will be pytest_report.html

