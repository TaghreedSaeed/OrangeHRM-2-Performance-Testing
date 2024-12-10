# OrangeHRM-2-Performance-Testing
This JMeter test plan is designed to evaluate key user interactions on the OrangeHRM Demo Application. It includes actions from landing on the page to logging out, with specific time-based functions and dynamic data handling.

# Test Actions
1-Landing Page
Simulates visiting the OrangeHRM landing page.

2-Login
Authenticates the user with valid credentials.

3-Get My Info Page
Retrieves the user's personal information page.

4-Update My Info Action
Updates user details using data from the provided CSV file.

5-Logout
Logs the user out of the application.

# Test Data
Data File: data_taskSHT.csv
Location: D:\Users\Performance\Data\data_for_shifttime_task.
Purpose: Used in the "Update My Info Action " step for dynamic data inputs.

# File Structure
recording_1.jmx: The JMeter test plan file.

data_taskSHT.csv: Data file for updating user information.

scripts/: Directory for storing test scripts.
