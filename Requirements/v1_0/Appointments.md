## Appointment Overview - IN PROGRESS

1. Patient appointments can be for visits of various types (clinic, admission, etc.)
2. Patients may be private or charity
3. In this document, clinic is broadly defined as any outpatient doctor / patient encounter.
4. Some clinic appointments may simply be for a given day, with no specific time. 
5. A method to categorize different clinics in the same physical building is required. For example: new patient clinic, clubfoot clinic, private clinic in the same physical building or campus
6. Patients may be assigned to specific doctors at time of appointment, or may not.
7. The receptionist role typically manages appointment lists for clinics.  They will need to be able to easily view and update the appointment list for a given day, for a given clinic, for a given doctor.
8. When patients come for the appointment, the appointment will need to be satisfied, and a corresponding visit created (see OPD requirements)
9. Doctors will want to manage their appointments, and will need to easily view and update their appointment lists.
10. Ward personnel will want to manage admissions appointments, and need to easily view and update those appointment lists.



## Jobs to be Done

#### When: A patient calls for an appt to a clinic (receptionist)

**I want to:**  

1. capture or update the essential patient demographic information
2. schedule the appointment by noting:
3. date and time
4. clinic location
5. doctor to be seen (optional)
6. reason for the visit 


**So I can:** 

1. properly manage clinical operations
2. ensure proper clinical resource needs
3. ensure the patient has a quality clinic visit

***

-#### When: A patient calls for an appt to a clinic (receptionist)

**I want to:**  

1. capture or update the essential patient demographic information
2. schedule the appointment by noting:
3. date and time
4. clinic location
5. doctor to be seen (optional)
6. reason for the visit 


**So I can:** 

1. properly manage clinical operations
2. ensure proper clinical resource needs
3. ensure the patient has a quality clinic visit

***


managing the appointments for a clinic day
- For a specific clinic, view  appointments scheduled for that day
- update the appointments as needed
-keep the list as accurate as possible
-avoid over-booking (or under-booking) the clinic that day






Doctor/ Nursing Role



managing a doctor's time for patient appointments
- review and update a doctor's appointment list for a day or week
-properly manage the doctor's schedule
-properly manage patients appointments


managing hospital admissions and patient uptake
- review and update the admission visits for a day or week
-properly manage the admissions process
-ensure proper admission for each patient, by ensuring any doctor's orders or instructions have been addressed.







********************************

### Data Elements

**Notes**: 

Note: assumption is that Patient IDs are always hyperlinks to the patient record, and users can return from viewing a patient back to the appointment.


At this time, clinic location could be sufficient to differentiate different clinics held in the same location.  

####Clinic appointment: details

1. Patient ID
2. First Name
3. Last Name
4. Gender
5. Age
6. DateTime of appointment
7. Appointment Status
8. Reason for visit
9. Patient type (private, charity)
10. Doctor to be seen (optional)Clinic location/type   


####Clinic appointments: calendar week view
Selection (filter) is for a given week, a specific doctor, or a specific clinic location
Appointment is placed on the correct date, contains a hyperlink to appointment details
Time blocks can be 15 or 30 min.  So, the exact datetime is kept, but on the view, snap to the nearest block (15 or 30min)


1. First Name
2. Last Name
3. Doctor to be seen




####Clinic appointments: list view
Selection (filter) is for a given day or week, a specific doctor, or a specific clinic location.   (and combinations of these)
Sort capabilities are needed for: doctor


1. ID
2. First Name
3. Last Name
4. Age
5. Gender
6. Reason for visit
7. Doctor  (to be seen)
8. Check-in (button)
