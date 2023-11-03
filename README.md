# Team 5 MIST 4610 Group Project 1
## Group Name:

39217 Group 5


## Team Members: 

Megan Gentles [@megangentles] (https://github.com/megangentles)

Kilpatrick, Lindsay @lindsaykilpatrick

Phelps, Aaron @aaronphelps

Trivedi, Hailey @haileytrivedi

Solipuram, Sahana @sahanasolipuram 

Sawyer, Paige @paigesawyer


## Problem Description:

The objective is to create a comprehensive relational database for an emergency healthcare clinic dedicated to providing critical medical services. The database must efficiently manage patient information, medical staff, administrative staff, emergency records, equipment, facility details, insurance and billing, emergency contacts, scheduling, security, training, and incident reporting. Patients are linked to their records, medical staff to patients, administrative staff to billing and appointments, emergency records to patients and staff, equipment to facilities, insurance and billing to patients, emergency contacts to patient records, scheduling to patients and staff, and security to staff records. The database aims to streamline data management, reporting, and operational needs in this healthcare setting.

## Data Model:

Explanation of data model: 

Our team has put in a lot of hard work to create a comprehensive data model for the healthcare system. We've really focused on understanding the different aspects of healthcare and making sure our model covers everything. At the heart of our model, we've got the 'Patient' entity because we recognize just how important patients are in the healthcare world. This entity includes all the key information about a patient, like their ID, name, date of birth, contact details, and insurance info.

Then, we've taken a deep dive into the 'Medication' entity, understanding how vital medications are. Our data model goes into detail, capturing information like medication ID, name, dosage, prescription info, and even where it comes from and its cost. To connect patients with their medications, we've introduced the 'Prescription' entity. This part of the model covers prescription details, including the ID, the medication, the patient, when it was prescribed, how it should be taken, and how to store it properly. Insurance is another big piece of the puzzle, so we've created the 'Insurance' entity. This part of the model manages all the insurance details, like policy info and coverage dates.

Doctors are crucial, and we've got a 'Doctors' entity that makes sure we know who's who in the healthcare world, with their ID, name, and specialization. Facilities are where patient care happens, so we've got a 'Facility' entity that keeps track of each facility's info. Appointments are the links between patients, doctors, and facilities, so we've created the 'Appointment' entity to keep all the details in one place.

We're also managing the lifeline of healthcare, and medical equipment, with the 'Equipment Inventory' entity. This helps us keep tabs on all the equipment, like its ID, where it's located, and when it was bought. Our 'Support Staff' entity recognizes the essential roles played by support staff members. We've also focused on referrals, which are key in healthcare, through the 'Referral' entity. Diagnostics are crucial, and our 'Laboratory Tests' entity ensures we've got that covered. It's linked to patients and doctors, making sure we have a full picture. Medical history is deeply personal, so we've made sure to capture it using the 'Medical History' entity. It's linked directly to the patient for a more personalized approach.

Our data model has been created through collaboration, considering the specific needs and requirements of our client. It's designed to handle everything, from patient care to medication management, diagnostics, and appointment scheduling, ensuring a seamless healthcare system. It's been a labor of love, and we're confident it'll make a real difference in the healthcare landscape.





<img width="631" alt="Screenshot 2023-11-03 at 2 46 34 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/518da1f0-de85-48a7-a3aa-e3c47af88fea">


## Data Dictionary:

<img width="805" alt="Screenshot 2023-11-03 at 3 31 18 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/ae9ce74d-d56c-4b68-8900-4a9665d7fe45">

<img width="809" alt="Screenshot 2023-11-03 at 3 31 38 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/eef9c409-74d0-4a60-b853-8947d4b6cecd">

<img width="809" alt="Screenshot 2023-11-03 at 3 31 56 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/0158b241-bd16-46f2-8f4b-3b1556444778">

<img width="804" alt="Screenshot 2023-11-03 at 3 32 14 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/f7529fc3-a023-4d0d-88a5-98ff34ed7d10">

<img width="800" alt="Screenshot 2023-11-03 at 3 32 38 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/9b92b1dc-d654-415d-af84-3ac7d6e329a4">

<img width="798" alt="Screenshot 2023-11-03 at 3 32 57 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/8358e73f-7dee-4c28-a8dd-c04b42f3e554">

<img width="794" alt="Screenshot 2023-11-03 at 3 33 20 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/34b47b0f-a0e7-4b3b-b052-2b9ae4d960eb">

<img width="787" alt="Screenshot 2023-11-03 at 3 33 35 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/ce66dee8-c6ce-48c1-be1b-b92a09a7486b">

<img width="778" alt="Screenshot 2023-11-03 at 3 33 59 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/320d8dac-188d-47e6-bc82-9efb1107cfd7">

<img width="778" alt="Screenshot 2023-11-03 at 3 34 22 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/bd0e7591-f031-4ae3-a97f-42d3f8310a3e">

<img width="806" alt="Screenshot 2023-11-03 at 3 34 40 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/dc5a60ff-a27d-4ba6-ab8c-f3b6da0a577c">

<img width="806" alt="Screenshot 2023-11-03 at 3 34 56 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/dd388080-5e84-4afa-b9eb-7ff4f74b902b">


## Queries:

<img width="713" alt="Screenshot 2023-11-03 at 3 23 04 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/5fd5df46-cbe7-450c-a121-e22059e926d4">

### Query 1:
Lists the total cost of each medication with the most expensive medication at the top and the least expensive at the bottom. This query allows managers to see which medications are the most expensive so they can properly prescribe patients to ensure their healthcare will be able to cover the expense. This also can help doctors determine if there is a cheaper option that they may be able to substitute for the patient. 

<img width="628" alt="Screenshot 2023-11-03 at 3 10 50 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/a338f1df-0985-4163-a956-f01661d0a7b3">


### Query 2:
 List the total cost of equipment at each facility. This query provides relevant information for the accounting and finance departments that manage the network of healthcare facilities. It is vital that they stay up to date on the total cost of equipment that they have in their inventory. This also allows them to see where costs can be reduced or if there is extra room in the budget.
 
 <img width="477" alt="Screenshot 2023-11-03 at 3 12 36 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/4f20559c-9d33-41f4-8d00-127ff6a84d99">


### Query 3:
List the doctors' names who have not given a referral in January of 2023. This query is useful to an employee at the healthcare clinics because it shows which doctors are actively referring to other practices. This might show biases among doctors or show the severity of cases that that doctor is treating. Some facilities and companies may want to give more or less referrals than others.

<img width="628" alt="Screenshot 2023-11-03 at 3 14 26 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/40285ee2-62cf-4bcd-b0d8-295d012e4536">


### Query 4:
List the patientID for any patients that received an inconclusive test result. This query is important, as it is vital to track the inconclusive test results, as many of those patients will need to be tested again. This query allows the doctor to see which patients had an inconclusive test result all in one place. 

<img width="321" alt="Screenshot 2023-11-03 at 3 15 05 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/0e4cfa9e-6f5e-4184-a557-62d2c14d79fb">


### Query 5:
Lists the number of patients a doctor is assigned to only for those doctors that see more than 5 patients as well as lists the number of support staff a doctor has only for those doctors with more than 1 support staff member. This can help managers determine whether some doctors need more support than others and if they need to allocate fewer patients to a specific doctor and allocate more to another doctor. 

<img width="633" alt="Screenshot 2023-11-03 at 3 15 49 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/1c7982de-6ea1-4a16-b97f-08bfe0285244">


### Query 6:
Lists out the name of the medication and the cost per unit expressed as a percentage of the total cost per unit of all medications. This query allows managers to see which medications account for the most amount of cost. It gives a representation of how expensive a medication is relative to the total amount spent on medications. 

<img width="675" alt="Screenshot 2023-11-03 at 3 16 31 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/fd875a01-8077-45cf-ba3e-8124ad826e14">


### Query 7:
List the number of medications that are low cost (less than $10 per unit), average cost (between $10 and $50 per unit), and high cost (greater than $50 per unit). This query shows how many medications they prescribe that would be considered low cost, average cost, or high cost. This can help managers determine whether they need to find a better balance between low, average, and high so they can serve each and every type of customer based on their financial needs. 

<img width="636" alt="Screenshot 2023-11-03 at 3 18 22 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/4d8bfee4-334d-499f-8619-af5296e6d340">


### Query 8:
List the tests that occurred in August of 2023 and those tests that result in prescriptions that cost the patient more than the average cost of medication per unit. This query shows managers a monthly view (specifically August) when a patient has to spend more on their medication than average. This can show the managers how many tests may result in an expensive medication prescription for a patient and can help them project how many more ‘expensive’ prescriptions will be made in the following month. 

<img width="630" alt="Screenshot 2023-11-03 at 3 19 33 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/9250b023-8516-4460-8bad-775b0be756ec">


### Query 9:
List the patient name, insurance name, prescription ID, and number of medications for each patient who was born in 1997. This query could be important if a manager was looking for a specific patient who was born in 1997 but did not know their name or ID number. This query shows important information that a doctor or office assistant might want to know about a patient when talking to them over the phone or checking them into the clinic.

<img width="635" alt="Screenshot 2023-11-03 at 3 20 25 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/af72dfa5-f164-45c3-8085-e98fdb89d2ac">


### Query 10: 
List the equipment ID, equipment name, and the percentage of total equipment cost for all facilities. This query allows the manager to see the cost of a specific piece of equipment in relation to the total cost of all equipment in all of the facilities. This could be important when deciding which equipment needs more money allocated as part of the maintenance budget or which pieces of equipment are more costly in general.

<img width="633" alt="Screenshot 2023-11-03 at 3 21 05 PM" src="https://github.com/haileytrivedi/MIST4610-Group-Project-1/assets/149614680/5f8d36b6-54fe-4afe-bbf0-3f8f48fcc2f7">


## Database Information
