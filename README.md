<img src="MU.jpg" width="100">
<img src="FElogo.jpeg" width="100">
<img src="deplogo.jpg" width="100">

# Software Engineering
Prof. Amr Thabet<br />
Assist. Lec. Shimaa Hagras<br />
<br /><br /><br />
# Charity System Analysis <br />

<br />
## Intro <br />
We all have volunteered someday. As volunteers, we saw that the regular systematic management system of charities devours a lot of time and effort. As a Software Engineering student, we tried to analyze charities' management systems. In the future, we plan to make a fully automated system. We Know that a charity is a gigantic system that has a lot of departments, operations, and people. All these components interact with each other in a very complicated way. So, we made a lot of constraints and tried to minimize the system to its core working blocks as this is V1.0 of this analysis. We also plan to extend this analysis when our experience gets more powerful.

<br /><br />

##Description:<br />
A system that handles the operations inside a charity, going from the management head to the employees, and handling the donations and volunteering process to benefit the cases it observes and/or explores. It handles (the finances between the management and employees), (logistics requesting funds), and (logistics exploring to find new rightful cases to help). It also handles the status of the cases that have already been helped to make sure that these cases get the attention they need.
<br /><br />

##User documentation:
I. End-users:
a. Volunteers
b. Donors
c. Cases
II. Admin users:
a. Management
<br /><br />
##Our system building blocks:
• Donors: people who donate money or any other thing. they may set a date
for a monthly donation.
• Volunteers: who works under the auspices of management.
• Management: paid or not. they are almost in charge of all things.
• Cases: any situation that charity can help with. It can by a mankind, mosque
or a whole village.
• Logistics: almost anything management do.
• Finance: in charge of handling all resources.
Our Analysis Constrains:
AS we previously mentioned, we have made a lot of constrains,
ignored a lot of department and operations, and merged a lot of roles and
departments. In this section we will give examples of this constrains.
Ignored Departments:
• HR
• PR
• Media
• Partnerships
Some of our Constrains:
• Management does exploration.
• Management may have no salary.
• Age and gender may be null.Process of finding cases and helping them:
• Firstly, the management needs to find a case that matches the criteria of
cases that would require help.
• Secondly, the management sends back the information of the to handle
the scouting process to see if the case is eligible for the charities' efforts of
helping.
• Thirdly, If the case is eligible (under the standard criteria), the
management department approves the process of help, hence, requesting
the material it would need to start helping (money, food, clothes, etc...)
from the finances department.
• Fourthly, the management starts gathering supplies that were requested
in the logistics operations, then starts to assess the man-power it needs to
start gathering volunteers that are willing to help from the department
assigned to that specific case.
• Finally, a team consists of managements (Multiple*) and volunteers are
assigned to this case with a date and time to start the final step of the
process, coming back with a status of the case after helping, let that be
(NEEDS FURTHER ATTENTION, NEEDS CHECKUP EVERY (time), CLOSED).


![alt text](Charity_sys_class_digram.svg  "Class Digram Text 1" )

<br /><br /><br />

![alt text](Charity_sys_Use_Case_digram.svg "Case Digram Text 1")
<br /><br /><br />

![alt text](Charity_sys_activity_digram.svg "Activity Digram Text 1")
<br /><br /><br />

![alt text](Charity_Sys_Sequence_digram.svg "Sequence digram Text 1")


