Assignment Course2 - NHS analysis

**Assignment activity 2:** <br>

There are 106 number of locations. <br>

The top five locations with the highest number of appointments are:<br>
  •NHS North West London ICB - W2U3Z <br>
  •NHS North East London ICB - A3A8R <br> 
  •NHS Kent and Medway ICB - 91Q <br> 
  •NHS Hampshire and Isle Of Wight ICB - D9Y0V<br>
  •NHS South East London ICB - 72Q  <br>           

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

Currently about 91% of the appointments are attended, rest are not attended (4%) or unknown (5%).<br>

Merging of the 3 files does not make sense because:<br>
- granularity is not the same of the files (ar file in on date level)<br>
- the number of appointments is not the same on days level (data integrity)<br>

**Assignment activity 3:** <br>
Appointments were scheduled between 1st od January 2020 and 30th of June 2022. <br>
General Practice service setting reported the most appointments in North West London from 1 January to 1 June 2022.<br>
In the month of November 2021 had the highest number of appointments.<br>

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

Number of appointments per day in the summer: <br>
![image](https://user-images.githubusercontent.com/108824849/197211440-725fda62-bc0a-4809-bcc7-a58dcb3f09b7.png)
![image](https://user-images.githubusercontent.com/108824849/197211461-89ca9681-7e2f-4ef1-afe7-c253770439b3.png)

Number of appointments per day in the autumn: <br>
![image](https://user-images.githubusercontent.com/108824849/197211549-67d843ba-5608-4a03-b63e-515d6b7e69af.png)
![image](https://user-images.githubusercontent.com/108824849/197211566-53c5de1d-a0d5-4526-a97b-40c3a9cdd092.png)

Number of appointments per day in the winter: <br>
![image](https://user-images.githubusercontent.com/108824849/197211620-ce3ac235-bdf8-4f8a-b66d-f2aacf2705f9.png)
![image](https://user-images.githubusercontent.com/108824849/197211659-4b27dd64-7da4-4a12-a4a6-6483d2688005.png)

Number of appointments per day in the spring: <br>
![image](https://user-images.githubusercontent.com/108824849/197211725-542a62d3-0279-4f3b-8139-aa7f33c03b25.png)
![image](https://user-images.githubusercontent.com/108824849/197211754-79f0c2ec-d3af-4be5-bbde-15821d591f0a.png)

In all seasons is the pattern the same. Low at the weekends, and Monday is the busiest day of the week in all categories.  

**Assignment activity 5:** <br>

Top 20 trending hashtags:<br>
![image](https://user-images.githubusercontent.com/108824849/197213028-944bd8c5-64e7-42c4-bb39-5d0e4735eda8.png)
![image](https://user-images.githubusercontent.com/108824849/197213250-50e06742-412c-43fa-9d41-7ce8540bf07b.png)
![image](https://user-images.githubusercontent.com/108824849/197213273-09fd55a1-e4c1-4506-bf39-66ec39e0e08a.png)

This analysis does not add value directly to this specific project, but it does show its potential: <br>
NHS can utilise tweets:<br>
-	Great way to increase the visibility of customers’ tweets / trending topics.<br>
-	It is a great way to find out the reactions of people to an event as it happens, whether it’s entertainment or breaking news, or COVID. <br>
-	Creating polls, and maybe even paying for advertising to increase the reach of NHS.<br>

**Assignment activity 6:** <br>

Total number of visits per month:<br>
![image](https://user-images.githubusercontent.com/108824849/197217085-97b8b4fb-d89b-4716-afea-89d62f51a22e.png)

Busiest month are October, November and March. This is on high level. Below, a more deep dive.<br>

![image](https://user-images.githubusercontent.com/108824849/197217235-c9da5cd9-a1bf-41a8-902f-8c5bf5221bf9.png)

The NHS can accommodate a maximum of 1,200,000 appointments per day, and since the number of appointments are lower than that, they do not have to look at increasing staff levels. <br>
There is adequate staff and capacity in the networks, utilization is low, they can do minimum 200k more per day in the busy months and 400k more in the low months like December-January and February. <br>

The healthcare professional types over time:<br>
![image](https://user-images.githubusercontent.com/108824849/197217503-d5580a54-3fb4-427d-9868-7fc42061d0cf.png)

The trend per professional type is similar: Summer and Winter months are low for both; November is the highest for Other Practice stuff; March is the highest months for GP. But the trend for both is the same: Sept-Oct-Nov are high following low winter months; March is high following lower April and summer months. 

Graphical representation for whether visits are attended:<br>

![image](https://user-images.githubusercontent.com/108824849/197237828-ab6e03f2-7d76-4ff1-ae5a-ceede80ab605.png)
![image](https://user-images.githubusercontent.com/108824849/197237847-1d1af586-b952-4d54-abfb-69879cc20993.png)

The pattern for the 2 different healthcare professional stays the same, but if we zoom into the not attended chart: There are way higher amount of visits that are not attended in the Other Practice stuff category.  And the most not attended visits are in November. 

Changes in terms of appointment mode and the busiest months:<br>

![image](https://user-images.githubusercontent.com/108824849/197241052-7ab4692d-7a66-4e5b-8244-6558dae4694c.png)
![image](https://user-images.githubusercontent.com/108824849/197242622-2907bcd7-3fea-4313-9ffc-2286dafddb7a.png)
![image](https://user-images.githubusercontent.com/108824849/197241073-5b15da4e-7729-4730-9661-68c90582306b.png)

As you see in the first chart above the face-to-face visits are the most, and the busiest months for that appointment mode is  October and November.  The video and home visit are flat month to month. Looking at the telephone visits, the highest is march and very low in April. Interesting finding is that the face-to-face visit has a high amount of not attend visits in October (more than 1.2M in one month) . Also, the telephone visit has a constant 200k per month non attended visit. 

Trends in time between booking and appointment:<br>

![image](https://user-images.githubusercontent.com/108824849/197247296-54ace718-a05d-454d-9eac-33b08d7b6d88.png)

The majority of the appointments are in the same day category, followed by ‘2 to 7 days’ and ‘8 to 14 days’.  The busiest month for the same day is March, while for the 2 to 7 days’ and ‘8 to 14 days’ is the October month. 

Comparing the various service settings:<br>

![image](https://user-images.githubusercontent.com/108824849/197247457-cfe372c4-e791-4a2b-80dd-b9723f9cfd73.png)
![image](https://user-images.githubusercontent.com/108824849/197247485-42639669-76f1-41d2-8806-a99ee768722c.png)

The biggest monthly spread, with other words the biggest variation in the amount of visits from month to month is at General Practice. The difference is 3.4m. There is also a lot of unmapped appointments: between 800k and 1.3m. The other categories has relatively stable amount of appointment from month to months and the spread is not as huge.   

