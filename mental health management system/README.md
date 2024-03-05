# Hosital-Management-System-DBMS
<b>Link</b> : git@github.com:sinchana-hk/sin.git

<pre>
Name: Sinchana H K
</pre>

Hospital Management System made for Sem 5 DBMS Course Project.<br>
Hospitals interact with a lot of people in a day and there are various activities involved in day to day operations of hospitals, for example booking of appointments, managing doctor schedules, managing patient diagnoses, managing medical histories of patients, etc. The aim of this project is to show how data related to these tasks can be made easier to manage using databases.

<b>Technologies Used:</b>
<pre>
Frontend : React.js
Backend : Node.js, Express
Database : MySQL
</pre>
<b>Patient Side Features :</b>

    1. There is a seperate interface for patients. Patients have a seperate login.
    
    2. Patients can book appointments.
    
    3. Patients can give previous medical history.
    
    4. Patients can view/update/cancel already booked appointments if necessary.
    
    5. Cancelled appointments create free slots for other patients.
    
    6. The system avoids clash of appointments with other patients. Each patient is therefore ensured his/her slot.
    
    7. Patients are able to see complete diagnosis, prescriptions and medical history.
    
    8. Patient medical history is only available to the doctor with whom the appointment is booked to ensure privacy.

<b>Doctor Side Features :</b>

    1. There is a seperate interface for doctors. Doctors have a seperate login.

    2. The system takes into consideration doctor schedules and does not allow appointments when a doctor is already busy or has a break.
    
    3. Doctors are able to access patient history and profile, and add to patient history.
    
    4. Doctors are able to give diagnosis and prescriptions.
    
    5. Doctors are able to modify diagnosis and prescriptions.

<b>Instructions to run:</b>

    1. Run "npm install" in frontend and backend directories.
    
    2. Run "npm start" first in the backend and then in the frontend directory.
    
    3. Access localhost:3000 from the browser.
