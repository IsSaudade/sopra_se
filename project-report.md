# Software Praktikum (SoPra) - FS25
## Milestone 1 - Project Report

### Group Information
**Group Number:** [45]

**Group Members:**
| Name | UZH Email | Student ID | GitHub Username |
|------|-----------|------------|-----------------|
| [Member 1] | [yutian.lei@uzh.ch] | [23-746-258] | [IsSaudade] |
| [Member 2] | [email2@uzh.ch] | [12-345-679] | [github-user2] |
| [Member 3] | [email3@uzh.ch] | [12-345-680] | [github-user3] |
| [Member 4] | [email4@uzh.ch] | [12-345-681] | [github-user4] |
| [Member 5] | [email5@uzh.ch] | [12-345-682] | [github-user5] |

## Project: UZH Study Buddy

### Project Description (max. 150 words)
UZH Study Buddy is a collaborative platform designed to connect University of Zurich students for academic collaboration. The platform addresses the challenge of finding compatible study partners and sharing course resources efficiently. Students can create profiles, join/create study groups for specific courses, schedule study sessions, and collaborate on documents in real-time. Study Buddy also enables resource sharing, with features for uploading, organizing, and rating lecture notes and study materials. The application integrates external services for weather forecasts and calendar synchronization to enhance the planning of study sessions. By facilitating peer connections based on courses, schedules, and study preferences, UZH Study Buddy aims to improve the academic experience, foster collaboration, and increase study productivity for UZH students.

## User Stories

### User Profile Management

#### ID: US1
**Category:** User Management  
**Story:** As a new user, I want to create an account with my university credentials so that I can access the platform's features.  
**Acceptance Criteria:**
- Users can register with their name, email, password, and major/department
- Email validation ensures only @uzh.ch email addresses can register
- Users receive a confirmation email after successful registration
- Users can log in with their credentials after registration  

**Priority:** Critical  
**Estimate:** 8h

#### ID: US2
**Category:** User Management  
**Story:** As a registered user, I want to set up my academic profile so that I can be matched with compatible study partners.  
**Acceptance Criteria:**
- Users can add their major, semester, and courses they are currently enrolled in
- Users can specify their study preferences (group/solo, online/in-person)
- Users can set their usual availability for study sessions
- Users can add skills and areas of expertise
- Profile information can be edited at any time  

**Priority:** High  
**Estimate:** 10h

#### ID: US3
**Category:** User Management  
**Story:** As a user, I want to update my online/offline status so that other users know if I'm available for study sessions.  
**Acceptance Criteria:**
- Users can toggle between "online" and "offline" status
- Status is visible to other users
- Status automatically changes to "offline" after prolonged inactivity  

**Priority:** Medium  
**Estimate:** 4h

### Study Group Features

#### ID: US4
**Category:** Study Groups  
**Story:** As a student, I want to create a study group for a specific course so that I can collaborate with peers taking the same course.  
**Acceptance Criteria:**
- Users can create a study group with a name, description, and associated course
- Creator can set group to public (anyone can join) or private (invitation only)
- Creator can set a maximum number of participants
- Group becomes searchable after creation  

**Priority:** Critical  
**Estimate:** 8h

#### ID: US5
**Category:** Study Groups  
**Story:** As a student, I want to search and join existing study groups so that I don't have to study alone.  
**Acceptance Criteria:**
- Users can search for groups by course name or code
- Users can view group details (description, members, etc.) before joining
- Users can send join requests to private groups
- Users can directly join public groups
- Users receive notifications when their join request is accepted  

**Priority:** Critical  
**Estimate:** 8h

#### ID: US6
**Category:** Study Groups  
**Story:** As a study group member, I want to communicate with my group members so that we can coordinate our study activities.  
**Acceptance Criteria:**
- Groups have a dedicated chat functionality
- Users can send text messages in the group chat
- Users can see when others are typing
- Users can share links in the chat
- Chat history is preserved for future reference  

**Priority:** High  
**Estimate:** 12h

### Study Session Planning

#### ID: US7
**Category:** Study Sessions  
**Story:** As a study group admin, I want to schedule study sessions so that all members can prepare and attend.  
**Acceptance Criteria:**
- Admin can create study sessions with date, time, duration, and location
- Admin can set session as online or in-person
- For online sessions, a meeting link can be added
- For in-person sessions, a campus location can be specified
- Weather forecast is displayed for upcoming in-person sessions  

**Priority:** High  
**Estimate:** 8h

#### ID: US8
**Category:** Study Sessions  
**Story:** As a study group member, I want to RSVP to scheduled study sessions so that the group knows who will attend.  
**Acceptance Criteria:**
- Members can mark attendance as "Going", "Maybe", or "Not Going"
- Members can add a note with their RSVP
- Group admin can see the list of attendees
- Users can sync the session to their Google Calendar using the Google Calendar API
- Users receive reminders before sessions they've committed to  

**Priority:** Medium  
**Estimate:** 6h

### Resource Sharing

#### ID: US9
**Category:** Resource Management  
**Story:** As a student, I want to upload and share course materials so that my study partners can access them.  
**Acceptance Criteria:**
- Users can upload files (PDFs, images, documents)
- Users can associate uploads with specific courses
- Files are stored in Google Cloud Storage
- Users can add titles and descriptions to uploaded files
- System shows upload date and file size  

**Priority:** Critical  
**Estimate:** 10h

#### ID: US10
**Category:** Resource Management  
**Story:** As a student, I want to browse and search shared resources so that I can find relevant study materials.  
**Acceptance Criteria:**
- Users can browse resources by course
- Users can search resources by filename and description
- Resources can be filtered by file type, upload date, and uploader
- Resources show number of downloads and average rating
- Users can preview PDFs and images within the application  

**Priority:** High  
**Estimate:** 8h

#### ID: US11
**Category:** Resource Management  
**Story:** As a student, I want to rate and comment on shared resources so that I can help others find quality materials.  
**Acceptance Criteria:**
- Users can rate resources on a 5-star scale
- Users can leave comments on resources
- Average rating is displayed for each resource
- Comments show username and timestamp
- Users can edit or delete their own comments  

**Priority:** Medium  
**Estimate:** 6h

### Collaborative Tools

#### ID: US12
**Category:** Collaboration  
**Story:** As a study group member, I want to collaboratively edit documents with my group in real-time so that we can work together efficiently.  
**Acceptance Criteria:**
- Group members can create collaborative documents
- Multiple users can edit the same document simultaneously
- Changes are visible to all users in real-time
- Users can see who is currently editing the document
- Document history is maintained for review  

**Priority:** Critical  
**Estimate:** 16h

#### ID: US13
**Category:** Collaboration  
**Story:** As a study group member, I want to create and share flashcards with my group so that we can study together effectively.  
**Acceptance Criteria:**
- Users can create flashcard sets with questions and answers
- Flashcard sets can be associated with specific courses
- Group members can view and study all shared flashcards
- Users can mark flashcards as "mastered" or "need review"
- The system tracks progress through flashcard sets  

**Priority:** Medium  
**Estimate:** 10h

#### ID: US14
**Category:** Collaboration  
**Story:** As a group admin, I want to create and assign tasks to group members so that we can divide work effectively.  
**Acceptance Criteria:**
- Admin can create tasks with descriptions and deadlines
- Admin can assign tasks to specific group members
- Members receive notifications about assigned tasks
- Tasks show status (Not Started, In Progress, Completed)
- Members can update task status and add progress notes  

**Priority:** Low  
**Estimate:** 8h

### Additional Features

#### ID: US15
**Category:** Integration  
**Story:** As a user, I want to check the weather forecast for planned in-person study sessions so that I can prepare accordingly.  
**Acceptance Criteria:**
- System integrates with a weather API
- Weather forecast is displayed for the location and time of in-person sessions
- Forecast includes temperature and precipitation probability
- Weather updates automatically as the session date approaches  

**Priority:** Low  
**Estimate:** 4h

#### ID: US16
**Category:** Analytics  
**Story:** As a student, I want to track my study progress so that I can improve my study habits.  
**Acceptance Criteria:**
- System records time spent in study sessions
- Users can see statistics on their study patterns
- Users can set study goals and track progress
- System provides visual representations of study data
- Data is private to the individual user  

**Priority:** Low  
**Estimate:** 8h
