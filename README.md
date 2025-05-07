# Riverside-Hospital
The design of an optimized data model using Draw.io to better structure RiverSide Hospital’s data.

![Riverside hospital](https://github.com/user-attachments/assets/a268416c-2ef2-4a70-80e6-0523316e5674)

## Overview
RiverSide General Hospital is a full-service healthcare facility committed to delivering high-quality medical care to its community. 
With specialized departments in emergency medicine, surgery, and outpatient services, the hospital meets a wide range of patient needs while maintaining a strong focus on safety and satisfaction. 
RiverSide continually works to enhance health outcomes and promote overall community well-being. Currently, the hospital relies on a flat-file data system, which presents several challenges: 
- Scalability: As data volumes increase, the system becomes slow and inefficient for performing advanced analytics.
- Integration: Data from other sources must be integrated manually, leading to delays and processing inefficiencies.

## Project Aim
This project proposes the design of an optimized data model using Draw.io to better structure RiverSide Hospital’s data, enabling faster, more reliable, and scalable analysis.

## Data Dictionary
• TransactionID
 • Date
 • Revenue Amount
 • Expenses Amount
 • DoctorID
 • Doctors_FirstName
 • Doctors_LastName
 • Doctor_Gender
 • Doctor Speciality
 • Doctor_DateOfBirth
 • Doctor_Phone
 • Doctor_Email
 • PatientID
 • Patients_FirstName
 • Patients_LastName
 • Patients_Gender
 • Patients_DateOfBirth
 • Patients_Address
 • Patients_Phoneno.
 • ProcedureID
 • ProcedureName
 • ProcedureCategory
 • ProcedureDescription
 • LocationID
 • Country
 • City
 • State
 • PostalCode

## Process
I took note of all the possible primary keys which are usually IDs like Transaction ID, Doctor ID, Patient ID, Procedure ID, and Location ID. 
Then I restructured the data by grouping them accordingly into different dimension tables with their primary keys. Created the Fact table with the foreign keys, and established connections/cardinality with the dimension tables. The end product was a well structured and optimized star schema data model.

## Star Schema Model

![Riverside Data Model](https://github.com/user-attachments/assets/9834094b-2168-4e74-92e8-4d7bc0b78e39)

## Conclusion
 The model will enable quick and accurate querying. It will also serve as a stepping stone for future analytics and decision-making.

 ![Thank you](https://github.com/user-attachments/assets/44930e29-aaa2-45a6-8ed9-334b974dde06)


