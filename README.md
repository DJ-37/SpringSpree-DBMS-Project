# SpringSpree DBMS Project 
## Introduction
* In this project, I have designed a database management system using Python ( SQLAlchemy toolkit ) and MySQL to store information about the annual cultural festival of NIT Warangal, SpringSpree. This database was created with the aim of smoothly conducting SpringSpree as well as to analyse the data for improving the festival in the coming years. 
* The database will contain personal details of attendees provided by the attendee at the time of purchasing the ticket. Each attendee may provide the name, age, gender, email, phone number, location and the days of the fest they plan to attend. This data can be used to allow entry for the attendees on appropriate days based on ticket purchase, to send updates and promotion material via email or text and to conduct demographic analysis for expanding marketing reach.  
* The database also contains information about the various events and ‘proshows’ aka concerts including the venue of the event, the day(s) on which they will be conducted, starting and ending time and sponsoring brand(s). Information regarding stalls set up by the brands will also be documented. 
* The database stores details of each organizer which helps in coordinating the programs. This includes the unique id, name, year of study, course pursued, branch, role and phone number. The database also stores the event(s) managed by the organizer. 
* The database records information of the participants of competitive events. Participants can compete in multiple events. The data consists of distinct participant id, name, institute, phone number, location, days of accommodation and the event(s) in which they are participating. 

## List of Tables 
* Attendees
* AttendeeDays
* Events
* EventDays
* EventsOrganiser
* EventSponsors
* FestClubCodes
* FestClubs
* FestTeam
* Subteams
* Participants
* ParticipantEvents
* Proshows
* Sponsors
* Stalls
* Venue

## ER Model Assumptions
*	An attendee can buy only one ticket to SpringSpree and is uniquely identified by his/her TicketID. 
*	The attendee can attend either the first day (D1), second day (D2) or both days of the festival
*	The festival is comprised of multiple events and ‘proshows’ conducted in venues across the campus
*	Events are organized by an organizer from the fest team and optionally along with a club member of the appropriate club. 
*	Participants can officially register for one more competitive event, either as a solo participant or as a group
*	These events may be sponsored by a company or brand. Sponsors belong to different categories depending on the amount sponsored. Stalls might also be set up by these companies for different purposes.
*	Each day of the festival has two proshows by performers. These are also managed by organizers from the fest team.

## ER Diagram and Relationship Schema
![ERD_RS_Final](https://github.com/user-attachments/assets/12897f75-848a-4f96-9f97-39fd83bfa558)

### For further details or to contact, please refer the database specification document in the repository
