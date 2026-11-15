2.SYSTEM REQUIREMENT

2.1	Stakeholder identification & Requirement Gathering
To ensure the conceptual design of CatCare IoT Feeding Machine on Campus effectively resolves stray cat feeding and sanitation challenges within Universiti Malaysia Terengganu (UMT), requirements were gathered from primary campus stakeholders.



Identified Stakeholder

i.	Campus Administration/Maintenance Team (UMT)  
 Responsible for system configuration, overall machine health monitoring, user account management, and maintaining campus facility hygiene standards.

ii.	 Student Volunteers/Animal Care Club
 Operational users in charge of monitoring dispenser levels, configuring feeding time, starting manual feeding, and refilling alerts.
















Requirement Gathering

i.	Semi-Structured Interviewing
   Conducted with student volunteers and campus facility representatives to highlight challenges associated with manual feeding, food wastage, and monitoring.

ii.	 Audit and Documentation Trail
   All interview notes, requirements checklist, and virtual meetings held through Google Meet have been documented in the GitHub repository maintained by the team (CatCare-IoT-Feeding-Machine-in-Campus-Group-8) under the evidence and meeting minutes folders.

iii.	 Field Study of Campus
   Identification of locations on campus where stray cats gather in higher numbers (cafeteria areas and hostel corridors of UMT). Determine optimal conceptual station placement and campus Wi-Fi availability.















	2.2 Functional Requirements
Functional requirements specify the vital processes and functionalities the CatCare IoT Feeding Machine web management system and the hypothetical IoT-based hardware system must exhibit when taking in inputs, processing them, and producing outputs.
User Authentication & Role-Based Access Control	The system allows registered Campus Administrators and Student Volunteers to log in to their accounts using their username and password.
	The system divides users into two roles which is Admins can manage accounts and machine maintenance, while Volunteers can handle schedules, manual feeding, and system monitoring.
Automated Feeding Schedule Management	Users can set the amount of dry cat food for each scheduled feeding time.
	Users can  create, view, update, and delete automatic feeding schedules

 Manual Remote Dispense Control	The manual control button for feeding should be provided in the system, through which volunteers can immediately feed the animals during off-hours

 IoT Sensor Monitoring & Live Dashboard	Display real time dry food and water container levels on the web dashboard.
	Monitor and display the online/offline operational status of each feeding station.
Alert & Notification	The system shall trigger a low-level visual alert whenever food or water capacity falls below 15%.




