<img src="MU.jpg" width="100">
<img src="FElogo.jpeg" width="100">
<img src="deplogo.jpg" width="100">

# Software Engineering
Prof. Amr Thabet<br />
Assist. Lec. Shimaa Hagras<br />
<br /><br /><br />
# Charity System Analysis <br />

<br /><br />

## Intro: <br />
We all have volunteered someday. As volunteers, we saw that the regular systematic management system of charities devours a lot of time and effort. As a Software Engineering student, we tried to analyze charities' management systems. In the future, we plan to make a fully automated system. We Know that a charity is a gigantic system that has a lot of departments, operations, and people. All these components interact with each other in a very complicated way. So, we made a lot of constraints and tried to minimize the system to its core working blocks as this is V1.0 of this analysis. We also plan to extend this analysis when our experience gets more powerful.

<br /><br /><br />

## Description:<br />
A system that handles the operations inside a charity, going from the management head to the employees, and handling the donations and volunteering process to benefit the cases it observes and/or explores. It handles (the finances between the management and employees), (logistics requesting funds), and (logistics exploring to find new rightful cases to help). It also handles the status of the cases that have already been helped to make sure that these cases get the attention they need.
<br /><br /><br />

## User documentation:
I. End-users:<br />
a. Volunteers<br />
b. Donors<br />
c. Cases<br /><br />
II. Admin users:<br />
a. Management<br />
<br /><br />

## Our system building blocks:<br />
• Donors: people who donate money or any other thing. they may set a date
for a monthly donation.<br />
• Volunteers: who works under the auspices of management.<br />
• Management: paid or not. they are almost in charge of all things.<br />
• Cases: any situation that charity can help with. It can by a mankind, mosque
or a whole village.<br />
• Logistics: almost anything management do.<br />
• Finance: in charge of handling all resources.<br />
<br /><br />
## Our Analysis Constrains:
AS we previously mentioned, we have made a lot of constrains,
ignored a lot of department and operations, and merged a lot of roles and
departments. In this section we will give examples of this constrains.<br />
<br />
Ignored Departments: <br />
• HR <br />
• PR <br />
• Media <br />
• Partnerships<br /><br />
Some of our Constrains: <br />
• Management does exploration. <br />
• Management may have no salary. <br />
• Age and gender may be null. <br />
<br /><br />
## Process of finding cases and helping them:<br />
• Firstly, the management needs to find a case that matches the criteria of
cases that would require help.<br /><br />
• Secondly, the management sends back the information of the to handle
the scouting process to see if the case is eligible for the charities' efforts of
helping.<br /><br />
• Thirdly, If the case is eligible (under the standard criteria), the
management department approves the process of help, hence, requesting
the material it would need to start helping (money, food, clothes, etc...)
from the finances department.<br /><br />
• Fourthly, the management starts gathering supplies that were requested
in the logistics operations, then starts to assess the man-power it needs to
start gathering volunteers that are willing to help from the department
assigned to that specific case.<br /><br />
• Finally, a team consists of managements (Multiple*) and volunteers are
assigned to this case with a date and time to start the final step of the
process, coming back with a status of the case after helping, let that be
(NEEDS FURTHER ATTENTION, NEEDS CHECKUP EVERY (time), CLOSED).<br /><br />

<br /><br />

## Class Diagram:<br />


![alt text](Charity_sys_class_digram.svg  "Class Digram Text 1" )

<br /><br /><br />


## Use Case Diagram:<br />
![alt text](Charity_sys_Use_Case_digram.svg "Case Digram Text 1")
<br /><br /><br />

## Activity Diagram:<br />
![alt text](Charity_sys_activity_digram.svg "Activity Digram Text 1")
<br /><br /><br />

## Sequence Diagram:<br />
<br />
![alt text](Charity_Sys_Sequence_digram.svg "Activity Digram Text 1")
<br /><br /><br />

## Risk Analysis:<br />
<br />
Types of predicted Risks:<br />
1.	Strategic.<br />
2.	Operational.<br />
3.	Hazard.<br />
4.	Financial.<br />
5.	Technical.<br /><br />
Available Solutions:<br />
1.	Avoid: eliminate cause of risk.<br />
2.	Mitigate: reduce probability or impact of risk.<br />
3.	Accept: continency plans for risk.<br />
4.	Transfer: have third party take on responsibility for risk.<br /><br />

Risks:

![alt text](risks.png "Activity Digram Text 1")


<br /><br /><br />


## Contributors: <br />
Ahmed Yasser Fathi Othman<br />
Moaz Mohammed Samy <br />
<br /><br /><br /><br /><br /><br />

