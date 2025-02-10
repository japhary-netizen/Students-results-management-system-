
# Student Result Management System

## Overview
This system is designed to manage and track student results, generate reports, and send SMS notifications to parents about their child's academic performance. It allows educators to input student results and provides an automated way to notify parents about their child's position and grade through SMS.

## Features
- **Student Registration**: Register students in the system with their personal details.
- **Result Entry**: Teachers can enter students' exam results and grades.
- **Position Calculation**: Automatically calculates student positions based on their grades.
- **SMS Notifications**: Sends SMS notifications to parents about their child's position and grades using a GSM modem.

## TECH STACK USED
Hardware: 
  - GSM modem for SMS notifications.
## front end: 
html,css
## back end: php
## Database server: Apache MySQL

## how to run the codes
1. **download and extract the zipped folder, extract all the file
2. **place the file in htdocs folder
3. # start phpMyadmin#: and create new databasae with the name businda_school
4. # go to import tab in phpMyadmin:
5. and import the database file which is in the sql folder in the extracted folder
6. # add new tab in your browser and type the address "localhost/secondary_schools_management_system/

7. **Database Setup**:
   - Create a MySQL database and import the schema.
   - Update database connection settings in the configuration file (`config.php` or `config.py`).

8. **SMS Setup**:
   - Configure your GSM modem or SMS API (for this case gammu was used during testing as an SMS gateway) settings in the SMS notification module.
   - Ensure your GSM modem is connected and set up for use.

9. **Configuration**:
   - Edit the configuration files to set the appropriate values for your school and academic year.
   - Ensure that the GSM modem is properly configured to send SMS.

10. **Run the system**:
   - Start the backend server and ensure the system is running properly.
   - You can now enter student results and test SMS notifications.

## SMS Notification Example
Once the results are entered, the parent will receive an SMS with the following format:

```
Dear Parent, Your child [Student Name] is ranked [Position] with a grade of [Grade] in [Subject]. Best regards, [School Name].
```

## Troubleshooting

- **SMS Not Sending**: Ensure your GSM modem is properly connected and configured.
- **Database Connection Issues**: Double-check your database credentials and ensure the server is running.
- **Result Calculation**: Verify that the grades are entered correctly and the system is calculating positions as expected.

## Future Features
- Integration with email notifications.
- Report generation for both students and parents.
- Mobile app version for real-time results access.

## License
This project is licensed under the MIT License.
# images ![Screenshot (7)](https://github.com/user-attachments/assets/2c39c502-ba95-4a41-a01d-74fd23e27179)
![Screenshot (8)](https://github.com/user-attachments/assets/cbdc6b83-1397-496a-bba0-e1535fc50373)
![Screenshot (6)](https://github.com/user-attachments/assets/352d2b31-8db8-430c-af33-099e3bff9407)
![Screenshot (5)](https://github.com/user-attachments/assets/24b1d249-7be5-4144-8673-e3751338a390)
