## Operative Plan
Note: this material was originally in the OPD requirements document.  See also the requirements document for Operation Report.

1. An operative plan (aka Surgical or Operation plan) is used by a doctor to note what procedures are planned for a specific surgery and other related information to facilite the surgery. 
2. It is created BEFORE surgery, typically during or as a result of a clinical encounter with the patient.  This is in contrast to an Operation Report, which is completed AFTER surgery to document the actual results and details of the event.
3. At this time, there is only a need to support one active Operative Plan per patient.
4. However, patients may have a number of surgeries, each one preceded by an Operative Plan.   
5. Therefore, Operative Plans require a state or status field, with the options being Planned, Completed and Dropped. 
6. Patients may have an Operative Plan created, and then never return for the surgery.  After some time, those plans could be moved to a Dropped status.
7. Although the Operative plan may be created during a visit, it is more appropriately associated with the patient directly.   It should therefore be easily accessable using a link in the patient header.
8. Normally a plan is Completed when an Operation Report is created. (ie. planned becomes actual)




## Jobs to be Done (JTBD)

### Summary

#### *Doctor:* Planing a surgery for a patient
#### *Doctor:* Reviewing a patient who is going to have surgery



#### When: A planning an operation for a patient (Doctor)

**I want to:**
 
1. Verify the Diagnosis
2. Describe the operation overall
3. Select the procedures to be performed
4. Schedule the operation date and time, if possible
5. Make additional notes


 
**So I can:** Capture the surgical plan for the patient with the diagnosis


***

#### When: Reviewing a patient who is going to have surgery (Doctor)

**I want to:**
 
1. Locate the patient and the operation plan
2. Review and update the plan elements as needed
3. Save the updated plan


**So I can:** Ensure the plan is accurate and up-to-date.  

***


### Data Elements

**Notes**: 

* this report can be supplemented with a custom form
* once created, the plan can be edited, up until the point that it is completed.


####Operation Plan

1. Patient ID  
2. First Name 
3. Last Name
4. Diagnosis (pre-populated with the active diagnosis, and can be edited)
5. Operation Description (free form text)
6. Procedure List  (one or more selections from the list of procedures in the system)
7. Case complexity - Planned ( free form text)
8. Surgery Date ( optional, may be set later )
9. Surgeon
10. Instructions upon Admission - such as enter requrests for Labs, x-rays, blood.  (free form text) 
11. Additional Notes
12. Custom Form (optional)
