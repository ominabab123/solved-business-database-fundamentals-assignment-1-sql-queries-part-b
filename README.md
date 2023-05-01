Download Link: https://assignmentchef.com/product/solved-business-database-fundamentals-assignment-1-sql-queries-part-b
<br>
SPECIFICATIONS

Read the following questions carefully. You will be asked to specify SQL queries to answer these questions.

CASE STUDY

Relational Model DOCTOR PATIENT APPOINTMENT ROOM DISEASE DIAGNOSED DoctorID PatientID AppointmentID RoomNo DiseaseID DiagnosedID Surname Surname dateOfAppointment Name Name DiseaseID Given Given timeOfAppointment Level ClassificationID AppointmentID Dob Dob Done Facility* Sex Sex PatientID Joined PhoneHome DoctorID Resigned PhoneWork RoomNo CLASSIFICATION Address PhoneFax ClassificationID Suburb Address Name Postcode Suburb Phone State supervisorID Postcode

Entity-Relationship Diagram

supervises PATIENT APPOINTMENT DOCTOR DISEASE has attend diagnosed in CLASSIFICATION ROOM uses School of Business I.T. Semester 1 – 2017 Business Data Management and Analytics Page 2 of 3




<strong>QUESTIONS</strong>

You will be working with a set of tables for a Doctor’s Clinic. You can access these tables by using the CLINIC database on the mysql server (mo.bf.rmit.edu.au). You are to prepare 12 SQL query statements that will provide answers to the following 12 requests for information. 1 marks each

1. Show a list of appointments for June 2016. Provide the doctor and patients full name, disease name (if any diagnosed), date &amp; time of appointment together in this format ‘YYYY-MON-DD HH:MM’, consultant room number used, and status (i.e. Done). Show these appointments in date &amp; time order.

2. Create a view called “todays_appointments”. The view should list all appointments for the current day. Include the appointment date and time, the doctor’s name, the patient’s name and phone number, and done field. Order the view into doctor’s name, then order by the appointment time.

3. List all appointments made by patients in the suburb RICHMOND, during the 2016 year that have not been diagnosed with any diseases. Show the name of the patient and the date and time of the appointment.

4. Display the name of the patient(s), age and sex of who is/are the oldest and youngest.

5. Show a list of the consultation room numbers, along with a count of the number of times they have been used for an appointment (don’t count the appointments that have not been completed/done).

6. Show number of patients in each suburb/postcode. Provide the SQL query and a geographic VISUALISATION of the data.

7. List all disease names and a count of how many times each disease has been diagnosed at the clinic. The list is of rarely identified diseases, so show only diseases that have a diagnosis count of less than 5. Note: Zero is less than 5. Provide the SQL query and a data VISUALISATION of the results.

8. Show all the patients that have visited the clinic more than 12 times. Show at least the surname and given name of the patient.

9. Need to create a Christmas card address list. Generate a query that includes both patients and doctors data. Show the ID (patientID or doctorID), concatenate a “P” in front of patientIDs and a “D” in front of doctorIDs, address, suburb, postcode. Sort list into suburb and then name order. Only select patients that have been a patient (have an appointment) at the clinic in 2016, and only doctors that have seen a patient in the clinic in 2016. 2 marks each

10. List all doctors, that are currently active doctors of the clinic, that are female and joined in the last four (4) years. Show the name of the doctor and the name of their supervisor.

11. The following two queries are related. a) Create a view that shows a count of appointments that each doctor has attended. The view should have the following fields: doctor’s id, doctor’s name, &amp; count of appointments. b) Using the view in the previous question, show the doctor that has the minimum and maximum number of appointments. Show the name of the doctor.

12. Produce a report of your own design, write a query to solve it and a visualisation. Marks will be awarded for report design (ie. How useful is the report), complexity of the query and originality and visualisation effectiveness in conveying the result. Provide Business QUESTION and SQL solution and data VISUALISTION of the results. School of Business I.T. Semester 1 – 2017 Business Data Management and Analytics Page 3 of 3 REQUIREMENTS 12 SQL queries that answer the questions asked, based on the data model and implemented database (on mo.bf.rmit.edu.au) provided. ASSESSMENT Assessment of the data model will be based on the following areas (by the tutor): • How well the query answers the questions, in relation to the case study provided. • Understanding of data structure • Efficiency and simplicity of resulting query DEMONSTRATION Selected students will be required to attend a demonstration session where they will be asked to demonstrate and explain the queries they have written and to write several new queries for the same database. Failure to explain the queries written or the inability to write new queries will result in a FAIL mark being recorded for assignment 1. SUBMISSION • Submit SQL queries (output not required) only. • Assignment will be submitted online using the learning hub.