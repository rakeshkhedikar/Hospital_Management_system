# Hospital_Management_system #

This is a basic HTML page that appears to be a Hospital Management System with a simple user interface. Here's an overview of what the HTML and JavaScript code does:

1. The HTML structure is straightforward:

    • It includes a title, "Hospital Management System."

    • It defines some basic CSS styles for the body, a container, and buttons.

    • Inside the container, it contains a heading, four buttons (Add Patient, Display Patients, Edit Patient, Discharge Patient), and a 'div' element with the id 
     "output" where patient information will be displayed.

2. The JavaScript code defines some functions and an array 'patients to store patient records.

3. generatePatientID(): This function generates a unique Patient ID based on the number of patients already in the system.

4. addPatient()': When the "Add Patient" button is clicked, this function prompts the user to input patient information (first name, last name, date of birth, contact number, admission date, and ward number). It then generates a unique Patient ID and creates a new patient object with this information, which is added to the 'patients' array. An alert message confirms that the patient has been added.

5. `displayPatients 0 deg : When the "Display Patients" button is clicked, this function clears the content of the "output' div and then displays the information of all patients in the 'patients' array. If there are no patients, it displays a message indicating that there are no patients in the system.

6. `editPatient()': When the "Edit Patient" button is clicked, this function prompts the user

    to enter a Patient ID. It searches for the patient with that ID in the 'patients' array and allows the user to update the first name and last name of the patient. An alert message confirms the successful update, or if the patient is not found.

7. `dischargePatient()': When the "Discharge Patient" button is clicked, this function prompts the user to enter a Patient ID, searches for the patient with that ID, and removes the patient from the 'patients' array. An alert message confirms the successful discharge, or if the patient is not found.

This is a basic example, and a real-world hospital management system would be more complex and include more features and data validation. 

