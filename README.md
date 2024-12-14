# Tally Connect
## Table of Contents
- [About the Project](#about-the-project)
- [Milestones](#milestones)
    - [Milestone 1](#milestone-1)
    - [Milestone 2](#milestone-2)
    - [Milestone 3](#milestone-3)
    - [Milestone 4](#milestone-4)
- [Presentation](#presentation)


# About the Project
Tally Connect is a mobile and web application aimed at enhancing the student and community experience by connecting users with local events and volunteer opportunities in the Tallahassee area. Designed with students in mind, the app enables users to easily browse, sign up for, and participate in various activities. The platform provides comprehensive event details, including descriptions, dates, times, locations, and volunteer requirements.

Event organizers can efficiently create, manage, and update their listings, streamlining the event management process while reducing administrative and marketing costs. Through Rattler Link, students and residents alike can stay informed about events in their city, and easily find ways to become more active in their local community. With a user-friendly interface, Rattler Link simplifies the process of discovering and joining events, whether for social engagement, or volunteering.

# Milestones
In this section we summarize each milestone and link to a more detail document of artifacts for each.

## Milestone 1

## SWOT Analysis
SWOT Analysis: Community Volunteer & Event App

Strengths:
Centralized Platform: The app provides a single, convenient space where students can find all volunteer opportunities and community events in Tallahassee, eliminating the need to search through different apps or having to hear about an event of their interest by word of mouth.
Increased Visibility for Events: By consolidating events into one platform, a wider audience is gained, especially from those who do not frequently check traditional channels for events.
Revenue Generation Potential: the potential for paid advertising or premium listings could generate income from event organizers or local businesses, as well as revenue for the app.
Student Engagement: Encourages stronger ties between students and the community and is a platform that is catered towards students.

Weaknesses:
Limited Initial User Base: The app’s primary target audience, students, may not initially adopt the platform, leading to low engagement rates during the early stages of deployment.
Dependence on Local Organizations: The app’s success depends heavily on local organizations actively posting their events. If event organizers don’t post on the app, there won’t be use for it.
Technological Barriers: Not all students or event organizers may be comfortable navigating mobile or web-based platforms, limiting the app's reach.

Opportunities:
Institutional Support: Potential for collaboration with local universities and local institutions for funding, sponsorships, and official endorsement, which could help with user adoption and visibility, especially this being a project started by students.
Expansion to Other Cities: After establishing success in Tallahassee, the platform could be expanded to other college towns for more students to get involved in their college town communities.
Partnership with Local Businesses: The platform can be sponsored by the schools’ or organizations who are participating in the app.

Threats:
Competition: Larger, well-established platforms like Facebook Events, Eventbrite, or local community websites could pose competition, making it harder to gain and retain users.
Low User Adoption: The app may not retain users; overtime people may return to other social media platforms to promote their events.
Technological Issues: Bugs, crashes, or poor user experience may discourage users from fully transitioning to the app or may require expensive fixes.





## Milestone 2

## Use Cases

### Use Case 001: Search for Events
Brief Description
This use case starts with a user using keywords/filters to search for specific events to participate in. 

Actors
Primary Actor: User

Pre-Conditions
The customer must have keywords of what they are looking for or a date/time/name of the event/organizer. 

Basic Flow
1.     The user opens the app.
2.     The user navigates to the search bar within the app.
3.     The user enters keywords or enters specific days they are looking for.
4.     The system will search the database using the user’s specific information.
5.     The related queries will be outputted to the user. 
 
    Alternate/Exception Flows
   1.     If the user does not have any keywords or dates to search for, a list of all the current events on the app will be outputted to the user. 
2.     If no matching events are found based on the user's search criteria, the system will display a message stating, "No events found."
 
    Post Conditions
The user will receive specific event listings that match their search criteria, including relevant details such as the event name, date, time, location, and a brief description. The user will also have the option to save or sign up for any of the events listed.
 
### Use Case 002: Sign-Up for Events

Brief Description
This use case starts with a user signing up for events they wish to participate in within the app. This interaction allows the user to secure their spot at the event and ensures that the event organizer has an accurate count of participants. Additionally, users have the ability to unregister from events if their plans change.
 Actors
 
Primary Actor: User
 
 Pre-Conditions
 The user must be logged into the app and must have selected an event to sign up for.  
 
 Basic Flow 
 
1.     The user navigates to the events page on the app.
2.     The user chooses an event they wish to sign up for
3.     The user clicks the “Sign Up” button, and a checkmark will show up.
4.     The system displays a confirmation message to the user
5.     A confirmation message is sent to the user’s email, and the event is added to the user’s calendar.

 Alternate/Exception Flows
1.     If the event has a capacity and it is reached, the system will display a message stating, "This event is fully booked. Please check other events."
2.     If the user cancels the sign-up process before confirmation, the system will discard the sign-up and return to the event details page.

 Post Conditions
The user will be successfully signed up for the event and added to the event’s participant list. The user will receive confirmation of their participation, and the event’s available slots (if applicable) will be updated accordingly to update the event organizers as well.
 
 
### Use Case 003: Manage Events

Brief Description
This use case involves a user (business or organization) managing an event they have listed on the app. The user has the ability to create, modify, or delete the details of the event, as well as remove the event entirely after posting it to the application’s event board.. 

Actors
Primary Actor: User
Secondary Actor: system 

Pre-Conditions
The user must be logged into the app and must be associated with a company or organization. Additionally, the user must have an event to manage.

Basic Flow
1.     The user navigates to their profile on the app.
2.     The user selects the option to create a new event listing or manage an existing event. 
3.     If creating a new event, the user fills out the required fields, including event name, location, hosting organization, date and time, event type (local event or volunteer opportunity), and the number of participants (if applicable).
4.     The system validates the input fields.
5.     The system displays a confirmation message to the user.
6.     An event post is created for the user and posted publicly to the app’s event board.
7.     The user has the option to view the event on the board and can choose to further manage it if necessary.
 

Alternate/Exception Flows
1.     If any of the required fields are left blank, the system will display an error message: “Please fill out all required fields before submitting.”
2.     If the user cancels the posting process before submission, the system will discard the sign-up and return to the event details page.
3.     If the user attempts to delete an event, the system will prompt for confirmation: “Are you sure you want to delete this event?” If confirmed, the event will be removed from the event board; if not, the user will remain on the event management page
 

Post Conditions
The user will have successfully created, modified, or deleted an event listing, and the changes will be reflected on the app’s event board. The user will also have the option to view and manage their events in the future.
 
 
### Use Case 004: Send Notifications

Brief Description
This use case starts the process by which the system automatically sends alerts to users for events they have signed up for. These alerts can include reminders about upcoming events, event details changes, or event organizers' important notifications. The alerts help ensure that users remain informed and engaged with the events they have committed to attending. 

Actors
Primary Actor: System
Secondary Actor: User 


Pre-Conditions
The user must be logged into the app and have signed up for at least one event. Notifications must be enabled on the user’s profile.

Basic Flow
1.     The system identifies all users who are signed up for upcoming events.
2.     The system checks the event dates and times against the current date and time to determine which alerts are due. 
3.     For each user with an upcoming event, the system generates a reminder alert, event type (local event or volunteer opportunity), and the number of participants (if applicable).
4.     The system sends the alert to the user’s registered email address and/or through in-app notifications.
5.     The system logs the alert in the user’s activity history for record-keeping.

   Alternate/Exception Flows
1.     If a user has not provided an email address or enabled notifications, the system will only send alerts through in-app notifications, if applicable. 
2.     If the user does not enable notification, the user will not receive alerts.
 

Post Conditions
The user will receive alerts regarding the events they have signed up for, which keeps them informed about event reminders and changes. The system maintains a record of sent alerts for future reference.
 

## Use Case Diagram
[Use-Case-Diagram.drawio.pdf](https://github.com/user-attachments/files/18134004/Use-Case-Diagram.drawio.pdf)

##Detailed Requirements Document

For our app where students can view and sign up for volunteer opportunities and events, some functional requirements could include:
•	User Registration and Login: Students and event organizers must be able to create accounts and log in.
•	Event Listings: The app must display a list of available events with details like description, date, time, location, and number of volunteers needed.
•	Search and Filter: Users should be able to search for events based on categories like location, date, or type of event (e.g., volunteer, educational, etc.).
•	Event Sign-Up: Students must be able to sign up for events directly through the app.
•	Event Management for Organizers: Event organizers should be able to create, update, and manage their events, including editing details or closing sign-ups when full.
•	Notifications: Users should receive notifications for upcoming events, sign-up confirmations, or changes in event details.

Some non-functional requirements for your app might include:
•	Performance: The app should load event listings within 2 seconds, even with a large number of events.
•	Scalability: The system must be able to handle a large number of users and events without performance degradation.
•	Security: User data, such as personal information and event participation, should be securely stored and transmitted (e.g., encryption).
•	Usability: The app should have an intuitive and user-friendly interface, making it easy for students and organizers to navigate.
•	Availability: The app must be available and operational 99.9% of the time.
•	Compatibility: The app should be compatible with both Android and iOS platforms, as well as various web browsers for the web version.

## Work Breakdown Structure WBS

![Picture1](https://github.com/user-attachments/assets/a32d0f04-7ab5-49e9-934a-e30ffa852a22)
![Picture2jpg](https://github.com/user-attachments/assets/07a4ce38-29bf-4535-a598-4fc430b31376)



## Milestone 3

## Wireframe
![wireframe](https://github.com/user-attachments/assets/b56076f2-bb08-4bc9-9dee-8068d5626b9b)

## Style Guide
![styleguide](https://github.com/user-attachments/assets/0d9fc75c-88b2-49e7-b4b6-4dbabc225c18)


## Milestone 4

## DFD
![DFD drawio](https://github.com/user-attachments/assets/97745ede-7797-421c-a13f-69f47789f146)

## Database & DB Dictionary
### USERS COLLECTION
| Property              | Type            | Description                                             |
|------------------------|-----------------|---------------------------------------------------------|
| `_id`                 | ObjectId        | Unique identifier for each user.                       |
| `name`                | String          | Full name of the user.                                 |
| `email`               | String          | Email address of the user.                             |
| `password`            | String          | Password for user authentication.                      |
| `phone`               | String          | Contact number of the user.                            |
| `profile_picture`     | String          | URL or path to the user's profile picture.             |
| `role`                | String          | Role of the user (`student`, `admin`, or `organizer`). |
| `registered_events`   | Array<ObjectId> | List of event IDs the user is registered for.          |
| `notifications_enabled` | Boolean       | Whether the user has enabled notifications.            |

---

### EVENTS COLLECTION
| Property             | Type            | Description                                             |
|-----------------------|-----------------|---------------------------------------------------------|
| `_id`                | ObjectId        | Unique identifier for each event.                      |
| `title`              | String          | Title of the event.                                    |
| `description`        | String          | Detailed description of the event.                    |
| `category`           | String          | Category of the event (e.g., `Community Service`).     |
| `date`               | Date            | Date of the event.                                     |
| `time`               | String          | Time of the event.                                     |
| `location`           | String          | Address or venue of the event.                        |
| `organizer_id`       | ObjectId        | Reference to the organizer's user ID.                 |
| `participants`       | Array<ObjectId> | List of user IDs registered for the event.            |
| `max_participants`   | Number          | Maximum number of participants allowed.               |
| `status`             | String          | Status of the event (`Upcoming`, `Ongoing`, `Completed`). |

---

### NOTIFICATIONS COLLECTION
| Property     | Type       | Description                                             |
|--------------|------------|---------------------------------------------------------|
| `_id`        | ObjectId   | Unique identifier for each notification.               |
| `user_id`    | ObjectId   | Reference to the user receiving the notification.       |
| `event_id`   | ObjectId   | Reference to the event the notification is about.       |
| `message`    | String     | Content of the notification.                            |
| `sent_at`    | Date       | Timestamp when the notification was sent.               |
| `type`       | String     | Type of notification (`Reminder`, `Change Alert`).      |

---

### EVENT MANAGEMENT LOGS COLLECTION
| Property       | Type       | Description                                             |
|-----------------|------------|---------------------------------------------------------|
| `_id`          | ObjectId   | Unique identifier for each log entry.                  |
| `event_id`     | ObjectId   | Reference to the related event.                        |
| `action`       | String     | Action performed (`Created`, `Modified`, `Deleted`).   |
| `performed_by` | ObjectId   | Reference to the user who performed the action.        |
| `timestamp`    | Date       | Date and time the action was performed.                |

---

### VOLUNTEER OPPORTUNITIES COLLECTION
| Property       | Type            | Description                                             |
|-----------------|-----------------|---------------------------------------------------------|
| `_id`          | ObjectId        | Unique identifier for each volunteer opportunity.       |
| `name`         | String          | Name of the opportunity.                               |
| `description`  | String          | Detailed description of the opportunity.               |
| `requirements` | Array<String>   | List of requirements for the opportunity.              |
| `event_id`     | ObjectId        | Reference to the related event.                        |
| `location`     | String          | Address or venue of the opportunity.                   |
| `date`         | Date            | Date of the opportunity.                               |


# Presentation

https://github.com/user-attachments/assets/3a3eb558-42ef-41b2-8e3f-cdfba6689c46


