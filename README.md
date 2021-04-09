#CS 499 Senior Project
Project Assignment
Patient Information Management System (PIMS)#

##Rationale##
Hospitals must maintain current information on all patients in the hospital as well as those recently released.  This information has to be readily available to a number of hospital personal such as doctors, nurses, office staff, and volunteers. 
The objective of this project is to develop a system which will maintain detailed information on all patients in the hospital and those who were in the hospital but have now been released.  Records must be maintained for a five-year period.  To protect the privacy of patients users of the system will have access to information only on a “need to know” basis. 

##Features##
The features listed below shall be included in the software.
1.	Users of the system must have a user name and password to log in to the system.
2.	Users accounts shall be one of four types: Physician, Medical Personnel, Office Staff, and Volunteers.
3.	Doctors and Medical Personnel (nurses, etc.) shall have access to all available information on a patient.  Office Staff shall have access to information required to identify a patient and to information regarding insurance.  Volunteers shall only have access to the name and room number of a patient, if the patient is restricted as to the number of visitors, and a list of approved visitors.
4.	A user may search for a patient by first name or last name.  If the exact spelling of a name is not known the user may enter a partial spelling and end with an asterisk, e.g. MAR* will locate all persons whose first name begins with MAR.  All patients fitting the search criteria shall be displayed in a list.  The user may then select the correct individual from the list.
5.	Users may log on to the system from any computer connected to the hospital intranet.
6.	The entire system shall have an appropriate Graphical User Interface.
7.	Information maintained on each patient shall consist of the following: Last name, first name, middle name, mailing address (street, city, state, zip), home phone number, work phone number, mobile phone number, names and phone numbers of two persons to contact in case of emergencies, date and time of admittance, reason for admission, family doctor, location (facility, floor, room number, bed number), date and time of discharge, doctor’s treatment notes, nurse’s treatment notes, prescriptions (name, amount, schedule) administered while in the hospital, scheduled procedures, insurance carrier, insurance policy information (account number and group number), billing information (itemized list of charges and amounts), amount paid, amount owed, amount paid by insurance.
8.	Doctors shall be able to enter additional notes on treatment, prescriptions, and scheduled procedures.
9.	Medical Personnel shall be able to view doctors’ treatment notes, prescriptions, and scheduled procedures and enter treatment notes for nurses.
10.	Office Staff shall be able to view and update any information on a patient not related to medical treatment.
11.	Volunteers shall have access to the names and locations of patients.
12.	The system shall be capable of printing a variety of reports for a single patient or summary reports on all patients.

Constraints
Users may run the program on a PC under Windows. 
Program must be robust -- Assume most users are not computer-knowledgeable. 
The system should be able to recover from errors, particularly input mistakes.
