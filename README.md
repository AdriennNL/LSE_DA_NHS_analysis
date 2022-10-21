Assignment Course2 - NHS analysis

**Assignment activity 2:** <br>
There are 106 number of locations. <br>
The top five locations with the highest number of appointments are:<br>
  •NHS North West London ICB - W2U3Z            <br>
  •NHS North East London ICB - A3A8R    <br>          
  •NHS Kent and Medway ICB - 91Q                  
  •NHS Hampshire and Isle Of Wight ICB - D9Y0V    <br>
  •NHS South East London ICB - 72Q     <br>           
There are 4 service settings:<br>
  •Primary Care Network<br>
  •General Practice<br>
  •Extended Access Provision<br>
  •Other<br>
There is 1 context type:<br>
  •Care Related Encounter<br>
There are 16 national categories:<br>
  •Patient contact during Care Home Round<br>
  •Planned Clinics<br>
  •Home Visit<br>
  •General Consultation Acute<br>
  •Structured Medication Review<br>
  •Care Home Visit<br>
  •Clinical Triage<br>
  •Planned Clinical Procedure<br>
  •Care Home Needs Assessment & Personalised Care and Support Planning<br>
  •General Consultation Routine<br>
  •Service provided by organisation external to the practice<br>
  •Unplanned Clinical Activity<br>
  •Social Prescribing Service<br>
  •Non-contractual chargeable work<br>
  •Group Consultation and Group Education<br>
  •Walk-in<br>
There are 2 appointment status:<br>
  •Attended<br>
  •DNA<br>
<br>
Merging of the 3 files does not make sense because:<br>
- granularity is not the same of the files (ar file in on date level)<br>
- the number of appointments is not the same on days level (data integrity)<br>

**Assignment activity 3:** <br>
Appointments were scheduled between 1st od January 2020 and 30th of June 2022. <br>
General Practice service setting reported the most appointments in North West London from 1 January to 1 June 2022.<br>
In the month of November 2021 had the highest number of appointments.<br>
Display the total number of records per month:<br>

![image](https://user-images.githubusercontent.com/108824849/197208551-f36138bb-e318-48e1-8649-5f0bd69249f8.png)


**Assignment activity 4:** <br>

Visualisations indicating the number of appointments per month for service settings:<br>
![image](https://user-images.githubusercontent.com/108824849/197209959-71670f25-368c-4412-ad84-477dc5f6f047.png)
![image](https://user-images.githubusercontent.com/108824849/197209976-85fcdd89-0caf-45f1-9ad4-36e696e50f4c.png)

Appointments related to General Practice are the most, it is more than 20M per month. Unfortunately there were a lot of unmapped categories in 2021 (between 800k and 1.3M), and it is still at 800k level in 2022 per month. The amount of appointment related to Primary Care Network is increasing: since August 2021 to June 2022 is almost doubled. 

Visualisations indicating the number of appointments per month for context types:<br>

![image](https://user-images.githubusercontent.com/108824849/197210058-3a3e9657-a16b-4829-b01c-126dd3e16f13.png)
![image](https://user-images.githubusercontent.com/108824849/197210077-8483f4c4-9ea8-4e4f-9acf-7a3c3d2195d6.png)

Looking at the context type, the most appointments are booked regarding the Care Related Encounter (between 20 and 25M per month). There are monthly around 2.5M inconsistent mapping and about 1M unmapped context type, which is decreasing. 

Visualisations indicating the number of appointments per month for national categories:<br>
![image](https://user-images.githubusercontent.com/108824849/197210856-9a5ebd55-e853-4d74-aa44-259d6b4e75e1.png)
![image](https://user-images.githubusercontent.com/108824849/197210872-040666ea-6045-4d44-a2ea-87ea9bd19599.png)

Looking at the national category, the most appointments are booked regarding the General Consultation Routine (between 8 and 10M per month), following General Consultation Acute (between 4M and 6M pe month), and Clinical Triage (about 4M per month).

