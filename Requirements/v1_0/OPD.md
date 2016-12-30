## OPD

1. OPD refers to the  OutPatient Department or Clinic within a hospital.  
2. Functionality is needed to easily and quickly register new and existing patients for outpatient clinic services on a given day.  
3. Personnel need to be able to easily view all patients active in the clinic.   
4. Personnel need to effectively process the patients, by being able to sort by visit type, whom seeing, etc. 
5. Doctors need to easily locate the patient they are seeing at that time.   Searching for the patient using demographic info is too tedious. 
6. Doctors then need to enter their notes and quickly generate orders for images, labs, meds, and schedule surgery (including a operative plan)
7. Before specific services are provided (eg, X-ray) payment prior to service may be required
8. Lab, Image and Pharmacy personnel need to easily see the open requests for patients in the clinic. 
9. Doctors will generate a clinical visit report for the patient.   It may include instructions and scheduled admissions date
10. Before patients leave the clinic and check-out, financial arrangements (payment) need to be addressed.
11. If follow-up visits, admission or referrals are required, these need to be confirmed (scheduled) before the patient leaves the clinic that day.
12. Information gathered during clinical visits should be leveraged to facilitate the admissions process.




## Jobs to be Done (JTBD)



#### When: A new patient arrives in the clinic (Receptionist)

**I want to:**
 
1. Quickly capture their essential demographic information.
2. Choose their visit type
3. Choose the doctor they will be seeing
4. Note if they had an appt or are a walk-in


 
**So I can:** Quickly add them to the clinic waiting list for that day.

Notes:

1. Essential Demographic info means a subset of the full demographic set of fields.
2. If patient had an appointment, it is now fulfilled, and a new visit created from the appt.
3. Patients with appts are somehow differentiated from walk-ins

***


#### When: An existing patient arrives in the clinic (Receptionist)

**I want to:**
 
1. Verify and update (if needed) their demographic information
2. Choose their visit type
3. Choose the doctor they will be seeing
4. Note if they had an appointment or are a walk-in

 
**So I can:** Quickly add them to the clinic waiting list for that day.


***



#### When: Any patient is discharged by the doctor from a clinic visit (Receptionist)

**I want to:**
 
1. Verify doctor's orders have been satisfied (labs. X-rays, etc.)
2. Verify any future visits have been scheduled (if needed), and schedule them if not
3. Verify that surgery has been scheduled (if needed), and schedule if needed
4. Print a clinic visit report and give it to the patient.  

 
**So I can:** Check out the patient from the clinic for the day and close the visit


Note: This report may also serve as the form they will present when coming back for admission


***


#### When: A private clinic patient is to be discharged from the clinic that day (Receptionist)

**I want to:**
 
1. Review all charges for the clinic visit
2. Edit, add, delete any charges for the visit
3. inform the patient of their financial responsibility

 
**So I can:** Ensure that all costs for treatment for that clinic visit are covered


Note: In addition to the generic discharge job above

***

#### When: The next patient in the clinic is to be seen (Nurse)

**I want to:** select the next patient to be seen by reviewing:

1. the list of active patients in-clinic
2. arrival times
3. patients with appointments vs walk-ins

 
**So I can:** Get the patient into surgery ASAP


*** 


#### When: Interviewing/examining a patient in the clinic (Nurse)

**I want to:** capture:

1. chief complaint or reason for visit
2. history of present illness
3. History and Physical information
4. known allergies
5. medications currently on
6. relevant medical history
7. vitals

 
**So I can:** Facilitate and support a diagnosis by the doctor


***


#### When: Examining a patient in the clinic during an initial visit (Doctor)

**I want to:** 

1. Quickly find the patient in the system
2. Review the H&P information
3. Update any information 
4. Order any needed Labs
5. Order any needed X-Rays
6. Make a diagnosis
7. Determine a course of treatment

 
**So I can:** Treat the condition


*** 



#### When: It is determined that surgery is needed for the patient being examined (Doctor)

**I want to:** Create a operative plan that includes:

1. a description of the operation planned
2. a list of one or more procedures planned
3. any required equipment
4. any  pre-op instructions for time of admission, such as labs, images or blood
5. Schedule the admission and surgey date/times  OR note that surgery needs to be scheduled

 
**So I can:** plan for the operation 

Note: if dates are not scheduled by the doctor during the encounter, the receptionist may try to schedule dates with the patient before they leave the clinic that day.  Alternately, surgery may be scheduled at some later time, including the admissions visit.

*** 



#### When: A patient in the clinic requires urgent surgery (Doctor)

**I want to:** Admit them immediately

 
**So I can:** Get the patient into surgery ASAP


*** 

#### When: An outpatient procedure is advised for the patient being examined (Doctor)

**I want to:**

1. record the procedure performed
2. record chargeable items
3. record any medications used
4. record any additional notes


**So I can:** 

1. properly record patient treatment
2. record information to help determine the proper cost of treatment

***  


#### When: I am reviewing a patient prior to surgery, outside of clinic (Doctor)

**I want to:**

1. Update information and orders associated with the patient
2. Revise the operation plan if required  

 
**So I can:** review and refine the treatment of the patient 

*** 

#### When: I am ready to service the next request (Lab / Image / Pharmacy Techs)

**I want to:**  

1. review the list of open requests
2. select the appropriate next request, using the datetime entered and any doctor's notes as a guide to priority
 
**So I can:** 

1. ensure that I service requests in the appropriate order and timeliness
2. inform the doctor/nurse that the request has been completed, with any appropriate notes.


****************************************

### Data Elements

**Notes**: 
Assumption is that Patient IDs are always hyperlinks to the patient record, and users can return from viewing a patient back to the original page


####Essential Demographic information

1. Patient ID
2. First name
3. Last name
4. Date of Birth
5. Gender
6. phone #
7. Contact name      (contact is a friend or relative)
8. Contact phone #
9. Note


#### Clinic Visit Page: Lite Demographic

1. First name
2. Last name
3. Date of Birth
4. Gender
5. CURE ID


####Clinic Visit Page: Visit Essentials

1. Reason for Visit / Chief complaint.
2. Previous Diagnosis listed (if available) and add new diagnosis button
3. Visit type
4. Visit location
5. Visit date
6. Outstanding orders notification  - (same as list screen)


####Clinic Active Visit List 
sort and filter on: Visit Type, Doctor, Appt flag    (and combinations of these)


**Each row has:**

1. Patient ID
2. First Name
3. Last Name
4. Age
5. Gender
6. Visit type
7. Arrival DateTime
8. Had appointment Flag  (patient had a scheduled appt)
9. Doctor (or who is seeing the patient)
10. Checkout (button)
11. Order Indicator  (flag is an order is outstanding)


