## Theatre Scheduling Overview

1. Theatre scheduling is the process of scheduling surgeries and managing surgical calendars.  
2. The resources involved are a patient, a surgeon or surgical team and an operating room. 
3. In a clinical setting, surgeries will be scheduled during a clinical visit, so that the patient can be advised when to go to the hospital.
4. During a clinic visit, a surgeon would create an operative plan, then look to schedule the surgery.  And possibly even move to schedule the admissions appointment.  
5. Surgeries are not a type of visit, rather an event that occurs during an admission visit.  However, surgeries are similar to visits in the sense that a patient would have an "appointment" for a surgery.
6. Accordingly, when a surgery is scheduled, the corresponding admission visit may be scheduled.  
7. Ideally, both the surgery and the admission are scheduled during a clinic visit, however, this may not always be possible.  Financial arrangements, for example, may be required before a committment to surgery is made.   
8. Surgeons and other hospital staff therefore need to be able to schedule surgery and admission visits "outside" of a clinical visit.
9. Surgeons and supporting hospital staff need to be able to view surgical calendars in a timely manner, and make adjustments as needed.  They would review schedules in the context of a day, week or month, for a given resource (surgeon, surgical team) and proceudre location (ie. operating room).
10. To assist in managing unschedule surgeries, hospital staff would like to be able to locate any planned surgeries that are NOT yet scheduled.
11. A "planned surgery" is manifest as an active operative plan.
12. A scheduled surgery is a type of appointment, somewhat similar to a visit appointment (but not exactly the same)


**Notes:**

* Surgery dates will be seen on the operative plan.
* Scheduled surgery dates will also be seen on the OPD visit report.
 




## Jobs to be Done (JTBD)


#### When: A surgeon is planning an operation during a visit (Doctor)

**I want to:**  Schedule surgery for the patient during the visit.   I would like the surgery appointment to be seen when viewing the operative plan.

 
**So I can:** Ensure that surgery is properly planned and scheduled, ideally before the patient leaves the clinic.

*** 
 
#### When: a hospital staff is managing surgical calendars  (Doctor, Nurse) 

**I want to:**  View and update surgical appointments by viewing surgical appointments for a given time period (day, week, month) for a given surgeon or surgical team, for a given operating room, or any combination thereof.  


**So I can:** Effectively manage surgeon time and/ or hospital resources.

*** 
 
#### When: hosptial staff is seeking to schedule a surgery  (Doctor, Nurse) 

**I want to:**  View a surgical calendar, and add the surgery appointment.   


**So I can:** So I can schedule the surgery, and possibly admissions visit for the patient.


*** 

###UX notes:

* a schedule surgery button on the patient apppointment tab is ideal
* the appointment main menu should be changed to Scheduling
* under Scheduling, a menu pick for Surgical Appointments should be added.





**************************************** 

### Data Elements

**Notes**: 

* A surgical appointment is somewhat similar to a visit appointment


Each surgical appointment will have:

1. Patient ID  
2. Patient Last name 
3. Patient First Name 
4. Begining DateTime of surgery
5. Ending DateTime of surgery
6. Physician (aka surgeon or surgical team)
7. Procedure Location
