## Incident Reporting

1. Incidents are reported by hospital staff, reviewed by CQI (continuous quality improvement) staff, investigations are conducted, recommendations are made and tracked, finally, the incident is closed. 
2. Nominal states of an incident are reported > active > follow-up > closed 
3. Incidents need to be assigned a configurable catagory and category item.  Configuration of these itmes is an Administration function
4. When a reportable incident occurs within a hospital, an incident report should be completed in a timely manner, and can be created by any staff member, with the exception of Sentinel events, which are completed by clinical leadership.  
5. Sentinel events are incidents of a most serious nature.  A sentinel event typical must be reported to clinical and possibly hospital leadership within some timeframe (e.g. 24 hours)  
6. Addtional information containing details for all sentinel events must be provided as a follow-up activity, typically time-bound (e.g. 5 business days)  
7. Select incidents, may require follow-up activities such as conducting investigations, completing assessments, determining HARM scores, making recommendations etc. 
8. Select incidents may have directly impacted a patient.  A link to the patients data in the system would be used to facilitate investigation and review of the incident.   
9. CQI staff will identify incidents requiring further investigation.    
10. CQI staff will review the results of investigations, and then be able to close an incident.  
11. CQI staff will review all incidents, but may chose to close some without further investigations.  
12. Incidents will be reported at some frequency (monthly, quarterly) typically to a management or leadership team.
13. At this time, there are 2 groups of users requiring separate permissions  1) uses that will enter, view and possibly update their own incidents.  2) users that manage all incidents in the hospital. 
14. The datetime and user who last updated an incident should be visible. 
15. A site configuration containing an email address needs to be available for the destination of sentinal event notifications. 
16. Reporting of incidents by department, and by category is required.   
17. Additonal reports of select incidents (filtering by date ranges, department, and category), showing details of the incident are also required.  




## Jobs to be Done (JTBD)


#### When: A reportable incident occurs  (hospital staff)

**I want to:**  
 
1. Create a new incident  
2. Complete all required fields
 
**So I can:** Facilitate the reporting and investigation of hospital incidents

*** 
 
#### When: Reviewing incidents I created  (hospital staff) 

**I want to:**
   
1. quickly view all incidents I created  
2. update an incident if needed


**So I can:** monitor the status of incidents I have entered

***
 
#### When: Investigating an incident  (hospital staff) 

**I want to:**
   
1. Update the incident with any new information
1. upload and attach files as part of the investigation

**So I can:** Facilitate the timely investigation of incidents

*** 

#### When: A sentinel event occurs (nurse manager, doctor, medical records officer)

**I want to:**  Create a new incident to notify executive leadership immediately 
 
**So I can:** Adhere to hospital policy and procedures on sentinel event

Note:  will need a configurable email address for notification
 
*** 

#### When: Following-up on a sentinel event  (nurse manager, doctor, medical records officer) 

**I want to:**  Update the incident to provide additional information to clinical leadership within N business days

**So I can:** Provide timely information to aid in the investigation of events


***
 
#### When: Managing incidents (nurse manager, doctor, medical records officer, CQI Staff) 

**I want to:** Easily view all incidents, filtering and sorting using:

1. a given time period
2. incident status
3. incident type 

**So I can:**

1. review new incidents
2. identify incidents for further review and investigation
3. monitor and track the progress of incident investigations
4. monitor and track the progress of sentinel events 

*** 

#### When: Reviewing and Investigating an incident (CQI staff)

**I want to:**  

1. request additional information for an incident  
2. add additional forms to be completed, as appropriate
3. notify personnel to provide additional information on a incident
 
**So I can:** properly investigate incidents and make recommendations to improve quality of care

 
*** 


#### When: Managing incidents(CQI staff) 

**I want to:**
 
1. close incidents that are complete  
2. update any non-closed incident  
3. reopen incidents if needed


**So I can:** Properly manage incidents to improve the quality of care

***




****************************************

### Data Elements

**Notes**: 

* Incidents could be supplemented by one or more custom forms


####Incident - General information


1. Incident ID  (auto)
1. Entered by   (user name)
1. DateTime Created   (auto)
1. DateTime of last update   (auto)
1. Updated By  (auto)
1. Sentinel Event (checkbox)
1. DateTime of incident
2. Department   
1. Category of Incident
1. Category Item of Incident
1. Patient Name Impacted   (optional)
1. Patient ID Impacted   (optional) 
1. Description
1. Status of incident  


####Addtional Information for each incident (presented in tabs)

1. List of Notes.   Each Note contains:
    1. Date of Note creation
    2. Who created the note
    3. Note text.   (large text field)
1. The Notes list would show the date, who and some of the Note in the row for each note.  Edit and Delete buttons on each note row.
1. List of Attachements.  Each attachment contains
    1. Date of attachement
    1. Who added the attachment (user name)
    1. Title of the attachment (short text field)
    1. Attached file
1. The Attachment list would show the date, who and title of the attachment in each row.  Edit and Delete buttons on each note row.
    	 

####Current Incidents List page

1. The current incidents page would show a list of incidents (if permissions are granted).
1. Each row in the list would show:
    1. Date of incident
    2. Department
    3. Category
    4. Category Item
    5. Status
    6. Edit and Delete button (delete is protected by a pop-up)
1. Each column in the list can be sorted
1. Filters are on the date entered, entered by (user), category, category item and status columns 
	 
      

****************************************

### Permissioning

1. Only two permissions (or levels) are required.
1. First is:
    1. to create incidents
    2. view only incidents I created
    3. Update only the Description, Category, Category Item and Patient of incidents I created.  No other data items can be edited or updated.
    4. This first permission would not allow you to delete
1. The second permission set gives full edit, update and delete capabilities to any and all incidents in the system.   This set of permissions would be used by a very small group of individuals in the hospital responsible for investigating and managing incidents.
 
