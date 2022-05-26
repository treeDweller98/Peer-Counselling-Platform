<img src="./media/image18.png" style="width:2.79938in;height:2.79938in"
alt="logo_iub.png" />

**Independent University, Bangladesh**

**Department of Computer Science & Engineering**

**CSE 307: System Analysis and Design**

**Spring 2022**

**Term Project**

<img src="./media/image9.png"
style="width:2.12229in;height:2.12229in" />

HealthyMind

A Peer Counselling Platform

**Fahim Ahmed**  
2022409

**Suhaila**

1910496

**Mir Shafayat Ahmed**

1910456

**Table of Contents**

**[1. Introduction](#introduction) 5**

**[2. History leading to project
request](#history-leading-to-project-request) 5**

**[3. Problems, opportunities](#problems-opportunities) 6**

> [Problems and Solutions](#problems-and-solutions) 6
>
> [Opportunities](#opportunities) 6

**[4. Project goal and objectives](#project-goal-and-objectives) 7**

**[5. Product Description](#product-description) 8**

**[6. System Context diagram](#system-context-diagram) 8**

**[7. Hardware detail (Include Rich
Picture)](#hardware-detail-include-rich-picture) 9**

**[8. Key Technical Features of
Software](#key-technical-features-of-software) 9**

**[9. Information Gathering methods (At least three
methods)](#information-gathering-methods-at-least-three-methods) 10**

> [Questionnaires:](#questionnaires) 10
>
> [Interviews:](#interviews) 10
>
> [JAD sessions:](#jad-sessions) 10
>
> [Samples](#samples) 11
>
> [1. Questionnaire Sample](#questionnaire-sample) 11
>
> [2. Interview Questions](#interview-questions) 12
>
> [3. User Stories of the New System](#user-stories-of-the-new-system)
> 13

**[10. Major functionalities offered by the
system](#major-functionalities-offered-by-the-system) 14**

**[11. Use Case Diagram](#use-case-diagram) 15**

> [User Initiation System](#user-initiation-system) 15
>
> [Notification System](#notification-system) 15
>
> [Chat System](#chat-system) 16
>
> [Report Handling System](#report-handling-system) 16
>
> [Questionnaire System](#questionnaire-system) 17
>
> [User Management System](#user-management-system) 17

**[12. Normal and Alternate Scenarios](#normal-and-alternate-scenarios)
18**

> [User signup](#user-signup) 18
>
> [Reported notifications](#reported-notifications) 19
>
> [Have conversations in chat](#have-conversations-in-chat) 20
>
> [View flagged conversation report
> details](#view-flagged-conversation-report-details) 21
>
> [Make Questionnaire](#make-questionnaire) 22
>
> [View Volunteer Profile](#view-volunteer-profile) 23

**[13. Functional Requirements](#functional-requirements) 24**

> [User Initiation System](#user-initiation-system-1) 24
>
> [Notification System](#notification-system-1) 24
>
> [Chat System](#chat-system-1) 24
>
> [Report Handling System](#report-handling-system-1) 24
>
> [Questionnaire System](#questionnaire-system-1) 24
>
> [User Management System](#user-management-system-1) 24

**[14. Non-Functional Requirements](#non-functional-requirements) 25**

> [Privacy](#privacy) 25
>
> [Security:](#security) 25
>
> [Cost:](#cost) 25
>
> [Usability:](#usability) 25
>
> [Misc.](#misc.) 25

**[15. Entity Relationship Diagram](#entity-relationship-diagram) 26**

**[16. Logical Data Flow diagram](#logical-data-flow-diagram) 27**

> [Diagram 0](#diagram-0) 27
>
> [User Initiation System](#user-initiation-system-2) 28
>
> [Logical Dataflow: Existing](#logical-dataflow-existing) 28
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed) 28
>
> [Notification System](#notification-system-2) 29
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed-1) 29
>
> [Chat System](#chat-system-2) 30
>
> [Logical Dataflow: Existing](#logical-dataflow-existing-1) 30
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed-2) 30
>
> [Report System](#report-system) 31
>
> [Logical Dataflow: Existing](#logical-dataflow-existing-2) 31
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed-3) 31
>
> [Questionnaire System](#questionnaire-system-2) 32
>
> [Logical Dataflow: Existing](#logical-dataflow-existing-3) 32
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed-4) 32
>
> [User Management System](#user-management-system-2) 33
>
> [Logical Dataflow: Proposed](#logical-dataflow-proposed-5) 33

**[17. Physical Data Flow diagram](#physical-data-flow-diagram) 34**

> [User Initiation System](#user-initiation-system-3) 34
>
> [Notification System](#notification-system-3) 34
>
> [Chat System](#chat-system-3) 35
>
> [Report System](#report-system-1) 35

**[18. Activity diagrams](#activity-diagrams) 36**

> [Activity: User Initiation System](#activity-user-initiation-system)
> 36
>
> [Activity: Volunteer signup System](#activity-volunteer-signup-system)
> 37
>
> [Activity: Report Notification
> System](#activity-report-notification-system) 38
>
> [Activity: Chat Notification
> System](#activity-chat-notification-system) 39
>
> [Activity: Chat System](#activity-chat-system) 40
>
> [Activity: Report System](#activity-report-system) 41
>
> [Activity: Questionnaire System](#activity-questionnaire-system) 42

**[19. Sequence diagrams](#sequence-diagrams) 43**

> [User Initiation System](#user-initiation-system-4) 43
>
> [User sign up](#user-sign-up) 43
>
> [Notification System](#notification-system-4) 43
>
> [Reported Notification](#reported-notification) 43
>
> [Chat System](#chat-system-4) 44
>
> [Have Conversations](#have-conversations) 44
>
> [Report System](#report-system-2) 44
>
> [View Reported Conversation](#view-reported-conversation) 44
>
> [Questionnaire System](#questionnaire-system-3) 45
>
> [Edit Questionnaire](#edit-questionnaire) 45

**[20. Communication diagrams](#communication-diagrams) 46**

> [User Initiation System](#user-initiation-system-5) 46
>
> [User sign up](#user-sign-up-1) 46
>
> [Notification System](#notification-system-5) 46
>
> [Reported Notification](#reported-notification-1) 46
>
> [Chat System](#chat-system-5) 46
>
> [Have Conversations](#have-conversations-1) 46
>
> [Report System](#report-system-3) 47
>
> [View Reported Conversation](#view-reported-conversation-1) 47
>
> [Questionnaire System](#questionnaire-system-4) 47
>
> [Make questionnaire](#make-questionnaire-1) 47

**[21. Class diagrams](#class-diagrams) 48**

**[22. State-chart diagrams.](#state-chart-diagrams.) 49**

> [Client class](#client-class) 49
>
> [Volunteer class](#volunteer-class) 49
>
> [Chat class](#chat-class) 50
>
> [Report class](#report-class) 50
>
> [Leave Application class](#leave-application-class) 51
>
> [Questionnaire class](#questionnaire-class) 51

**[23. CRUD matrix](#crud-matrix) 52**

> [User Initiation System](#user-initiation-system-6) 52
>
> [Chat System](#chat-system-6) 52
>
> [Report System](#report-system-4) 53
>
> [Questionnaire System](#questionnaire-system-5) 53

**[24. Structure English pseudo code for the
system](#structure-english-pseudo-code-for-the-system) 54**

> [User Initiation System](#user-initiation-system-7) 54
>
> [Notification System](#notification-system-6) 55
>
> [Having Conversations](#having-conversations) 56
>
> [Handle Reports](#handle-reports) 57
>
> [User Management](#user-management) 58
>
> [Questionnaire Management](#questionnaire-management) 59

**[25. Prototype the user interface](#prototype-the-user-interface) 60**

> [User Signup](#user-signup-1) 60
>
> [Volunteer Application](#volunteer-application) 60
>
> [User Login](#user-login) 61
>
> [Chat](#chat) 61
>
> [Chat Client List (visible to volunteers
> only)](#chat-client-list-visible-to-volunteers-only) 62
>
> [Chat Schedule](#chat-schedule) 62
>
> [Chat Questionnaire](#chat-questionnaire) 63
>
> [Add Custom Questionnaire (visible to volunteers
> only)](#add-custom-questionnaire-visible-to-volunteers-only) 63
>
> [Chat Notification](#chat-notification) 64
>
> [Report Chat](#report-chat) 64
>
> [Report Management](#report-management) 65
>
> [AI-flagged Report Details](#ai-flagged-report-details) 65
>
> [Manually-flagged Report Details](#manually-flagged-report-details) 66
>
> [Report-handling wizard](#report-handling-wizard) 66
>
> [Leave Application List](#leave-application-list) 67
>
> [Leave Application Details](#leave-application-details) 67
>
> [Admin Add Questionnaire](#admin-add-questionnaire) 67

**<u>Section 1:</u>**

# **1. Introduction**

HealthyMind is a non-profit organisation aimed at providing peer-support
services to people of all ages. It is run by a group of mental health
professionals, supervising a team of volunteers who counsel clients over
an internet messaging service. Clients register for the service and are
assigned a volunteer. Both parties remain anonymous to one another. Once
connected, they can have conversations and receive counselling and
support. At present their operations are small in scale; employing only
a dozen or so volunteers, each connected to around five clients.

# **2. History leading to project request**

The organisation uses Facebook Messenger to provide their services. All
operations are conducted manually. Volunteer applications, client
registration, assigning volunteer to client are all done by knocking the
organisation on their Facebook page and requesting to answer the
appropriate questionnaire on Google Forms. Both requests and responses
have to be checked and approved periodically - leading to long wait
times and tedium for all parties involved. This manual and fragmented
nature of the existing system is hampering their vision of expanding
their operations.

Also of note is that the organisation has recently had to deal with a
breach of confidentiality between a client and their assigned
volunteer - the cause of which was determined to be a limitation of
their operating procedures and the messaging platform being used.
Supervision is difficult and a robust system for reporting (and dealing
with reports of) inappropriate behaviour is unfortunately absent in that
platform since it was never designed for such a task.

Hence HealthyMind approached us with their problems - asking for a
dedicated, all-in-one software solution automating their day-to-day
activities.

# **3. Problems, opportunities**

## ***Problems and Solutions***

|     | Problem                                                                                               | Solution                                                                                                                                                                                                                        |
|-----|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     | Manual, tedious registration process that involves going to another site. May discourage signing up.  | User initiation will be handled within the application in a guided manner. Users will not be taken to another site.                                                                                                             |
|     | Anonymity difficult to maintain due to Facebook being used                                            | User details will only be visible to supervisors in the new system.                                                                                                                                                             |
|     | Confidentiality cannot be maintained as one volunteer’s messages are not kept isolated from another’s | Each volunteer will have completely separate accounts so this limitation of the previous messaging platform will not apply. Only supervisors will have access to chat logs, and only after a report has been filed by the user. |
|     | Supervising a large number of chats unfeasible                                                        | AI will be employed to moderate chats. Alerts will be sent to supervisors if inappropriate activity is detected.                                                                                                                |
|     | Reporting conversations is done manually via google forms                                             | Reporting can be done within the chat application window.                                                                                                                                                                       |
|     | Pending reports have to be periodically by supervisors.                                               | Urgent alerts will be sent to the supervisor whenever a conversation is reported. All pending reports can be seen in the supervisor’s dashboard.                                                                                |
|     | Reports have to dealt with manually                                                                   | List of possible actions can be seen in the dashboard and handing can be done directly from there                                                                                                                               |
|     | Various mental health assessment questionnaires have to be taken off-site                             | Editable questionnaires will be integrated into the application so users can have a seamless experience.                                                                                                                        |
|     | Questionnaires have to be manually handed out.                                                        | Questionnaires can be scheduled and set by supervisors and volunteers. These are to be automatically distributed to clients and the responses can be accessed in a convenient manner from their dashboards.                     |
|     | Conversations have to be manually scheduled/agreed upon by parties                                    | Scheduling and notification system will be integrated in the chat application itself.                                                                                                                                           |

## ***Opportunities***

-   No similar all-in-one platform currently exists.

-   User convenience will be unparalleled.

-   AI-based supervision would ensure confidentiality.

-   Automation will reduce supervisor workloads and will allow them to
    > work more efficiently.

-   Volunteer management (leaves, signup, assigning) can be done via
    > this application.

-   Chat application will be purpose-designed for this organisation’s
    > needs so it can better guarantee confidentiality.

-   Due to questionnaires etc. being integrated into the chat
    > application, the new system can give a much more cohesive and
    > unified experience.

-   Confidentiality and convenience will attract a large number of
    > users.

-   Automation will allow the organisation to scale up their operations.

# **4. Project goal and objectives**

> HealthyMind aims to provide cost free service to the users ranging
> from all ages. This website is designed to provide a safe space and
> learning environment for people without fear of judgement,
> misunderstanding, harassment or abuse. It carves out a way for
> promotion of mental health through service, advocacy, and education.
> It offers a very efficient , smooth, and comfortable website to use
> (from home) as well as an excellent platform that is accessible for
> all people (including disability).
>
> One of the advantages is that the users can easily navigate through
> the platform with minimum effort where the service can be available
> 24/7. In addition, the platform is structured in a way ensuring
> confidentiality of both client and volunteer through high monitoring
> by the employees to ensure a safe and secure environment for both the
> parties.

**<u>Section 2:</u>**

# **5. Product Description**

1.  **Product summary**

> It is a platform in which people from all around Bangladesh can
> connect and share their inner thoughts while being anonymous to a peer
> support volunteer. The volunteers can also apply with just a few steps
> by signing up and uploading their resume. The administration is
> updated from time to time of the ongoing activities on the website.
> Moreover, they can maintain and have an overview of all the users at
> any preferable time they want.
>
> Furthermore, after the volunteers and clients have successfully
> registered and are part of HealthyMind, they can start communicating
> with each other with proper security and privacy ensured on both ends
> and also set up schedules if they wish. On the other hand, The
> volunteer has an option to even reject a request for chat and clients
> can also wish to reassign the volunteer. To maintain security and
> privacy, an AI chat moderator is incorporated in the system which will
> detect any inappropriate images or messages sent in the chat log and
> immediately notify the supervisor.
>
> To summarise, the platform will help increase awareness of mental
> health and people will be more willing to share their problems.

2.  **Product Stakeholders**

-   Client

-   Admin

-   Supervisor

-   Volunteer

# **6. System Context diagram**

<img src="./media/image30.png"
style="width:9.44291in;height:5.98611in" />

# **7. Hardware detail (Include Rich Picture)**

**Frontend**:

-   Smartphone, PC or Laptop

-   Internet connection capable of smooth browsing experience

-   A Web Browser or an Android or iOS app.

**Backend:**

-   Servers capable of handling 1000 users concurrently hosted by a
    > cloud service provider.

-   At least 100MB of storage allocated per user.

-   A relational database - MySQL.

-   A language like Python that is capable of handling thousands of
    > requests every second.

<img src="./media/image24.png"
style="width:8.54167in;height:5.69444in" />

# **8. Key Technical Features of Software**

-   JavaScript will be the main frontend language as it allows for
    > making Web Apps that can easily be made into Native apps for
    > Android and iOS. Ensuring compatibility.

-   Compute-Heavy tasks like Image Manipulation and Natural Language
    > Processing are offloaded to powerful servers, hence allowing for
    > older smartphones to use the service.

-   AI model inappropriate content detection is incorporated in the
    > system to detect inappropriate chat messages.

-   Backend uses Django/Python for ease of maintainability.

-   End-to-end encryption of all chat messages using SHA256 to ensure
    > privacy.

-   User authentication code system to ensure sensitive data is not
    > revealed.

-   OTP 2FA used for signup/login

**<u>Section 3:</u>**

# **9. Information Gathering methods (At least three methods)**

Upon a cursory examination of the organisation, we settled for several
interactive data gathering messages for this project. Due to the small
size of the organisation, sampling a large pool of members was not an
option. The decentralised/virtual nature of the organisation, plus the
need for maintaining strict confidentiality did not permit us the
ability to sit down and observe organisation members carrying out their
day to day tasks in their own environment. Information gathering was
carried out in phases:

-   ## ***Questionnaires:*** 

> To gather preliminary information about their requirements,
> questionnaires were emailed to all the volunteers and supervisors
> working under the organisation, plus a few willing clients of the
> organisation. The questionnaire had a small description of the new
> system to give them some context. Responses were submitted via Google
> Forms.

-   ## ***Interviews:*** 

> Our interviewer carried out background research by taking notes of the
> facebook page of the organisation, their blog and their press releases
> detailing the policies, values and vision of the organisation.
>
> We decided to individually interview the vice president (who is also a
> former supervisor), a peer support volunteer and two willing clients.
> Interview questions were mailed out a week in advance to prepare the
> interviewees. The interview was conducted virtually as each individual
> was situated at different places. Each session lasted approximately an
> hour.
>
> The objective of the interview was to find out how they worked, their
> software requirements, what they wish to achieve with the new system,
> the resource budget etc. Beside the specific interview questions,
> interviewees were encouraged to elaborate on their questionnaire
> answers, tell us stories about their time with the organisation, voice
> their personal concerns with the old and new system and their opinions
> on certain policies and requirements of the organisation.

-   ## ***JAD sessions:*** 

> At a later date following the conclusion of the interviews, we sat
> down together with all the interviewees for four consecutive days to
> discuss the functionalities and UI of the system.
>
> After an hour-long orientation session, led jointly by our senior
> analyst and the organisation’s vice president, we first wrote down the
> user stories of the existing system, and decided upon the logical
> workflow. We raised concerns about some of their requirements (namely,
> the extent of the AI moderator’s abilities) - the cost, workability
> and practicality made certain requirements unfeasible with their
> budgetary constraints and our limited expertise. They were
> understanding and we settled upon a scalable system that would allow
> easy integration with the components that they may wish to add in the
> future.
>
> Once the workflow and requirements were tweaked to satisfaction, the
> new user stories were written up and the entirety of the last day was
> spent drawing up the user interface. Here the clients of the
> organisation had particular inputs about its ease of use, which was
> incorporated into the final prototype.
>
> Samples for the questions and the user stories generated are attached
> below.

## Samples

### 1. Questionnaire Sample

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th><blockquote>
<p><strong>Choose your position:</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>Supervisor</p>
</blockquote></li>
<li><blockquote>
<p>Client</p>
</blockquote></li>
<li><blockquote>
<p>Volunteer</p>
</blockquote></li>
<li><blockquote>
<p>Other</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><blockquote>
<p><strong>How long have you been involved with the
organisation?</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>Less than 6 months</p>
</blockquote></li>
<li><blockquote>
<p>6 months to 1 year</p>
</blockquote></li>
<li><blockquote>
<p>1 to 2 years</p>
</blockquote></li>
<li><blockquote>
<p>More than two years</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><blockquote>
<p><strong>What device(s) do you currently use to access the service?
(Check all that apply)</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>Tablet</p>
</blockquote></li>
<li><blockquote>
<p>Laptop</p>
</blockquote></li>
<li><blockquote>
<p>Smartphone</p>
</blockquote></li>
<li><blockquote>
<p>Desktop</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><blockquote>
<p><strong>How much time do you spend using the service every
week?</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>More than 5 hours</p>
</blockquote></li>
<li><blockquote>
<p>1-3 hours</p>
</blockquote></li>
<li><blockquote>
<p>Less than 1 hour</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><blockquote>
<p><strong>Rate your satisfaction with the current system (on a scale of
1-10): _______</strong></p>
</blockquote></th>
</tr>
<tr class="odd">
<th><blockquote>
<p><strong>How much are you willing to adapt to the new
system?</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>Very willing</p>
</blockquote></li>
<li><blockquote>
<p>Somewhat willing</p>
</blockquote></li>
<li><blockquote>
<p>Neutral</p>
</blockquote></li>
<li><blockquote>
<p>Unwilling</p>
</blockquote></li>
<li><blockquote>
<p>Very unwilling</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th><blockquote>
<p><strong>Which is most important?</strong></p>
</blockquote>
<ul>
<li><blockquote>
<p>Confidentiality</p>
</blockquote></li>
<li><blockquote>
<p>Clienty safety</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th><blockquote>
<p><strong>Explain your role in the organisation.</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
</blockquote></th>
</tr>
<tr class="header">
<th><blockquote>
<p><strong>How effective do you find the current system at its task of
providing/receiving counselling?</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>Why?</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
</blockquote></th>
</tr>
<tr class="odd">
<th><blockquote>
<p><strong>What would make it easier for you to more effectively use the
service?</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
</blockquote></th>
</tr>
<tr class="header">
<th><blockquote>
<p><strong>Briefly describe 3 worst aspects about the current system in
your opinion.</strong></p>
</blockquote>
<ol type="1">
<li><blockquote>
<p>_____________________________________________________</p>
</blockquote></li>
<li><blockquote>
<p>_____________________________________________________</p>
</blockquote></li>
<li><blockquote>
<p>_____________________________________________________</p>
</blockquote></li>
</ol></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

\* only questions shown here, no instructions etc.

### 2. Interview Questions

| **Supervisor/Vice President Interview Questions (arranged in a funnel to extract maximum information)** |
|---------------------------------------------------------------------------------------------------------|
| A short rundown of how the current system works.                                                        |
| Why is there a need for a new system?                                                                   |
| What are your biggest concerns regarding the current system?                                            |
| What improvements/changes are required to the current system?                                           |
| How well is the coordination within the organisation?                                                   |
| What challenges do you face maintaining client confidentiality? How do you currently mitigate them?     |
| How do the supervisors currently take action after receiving reported contents?                         |
| What are your thoughts on employing an AI to moderate chats?                                            |
| What are the organisation’s future plans regarding scalability?                                         |
| How much can the organisation spend for this software acquisition?                                      |
| How much is the maintenance budget?                                                                     |
| How many people can the organisation dedicate towards keeping this system running day-to-day?           |

| **Volunteer Interview Questions (arranged in a pyramid to ease them into opening up)** |
|----------------------------------------------------------------------------------------|
| How often do you counsel the clients?                                                  |
| How many clients do you regularly take on per month?                                   |
| How is the overall experience while interacting with the clients?                      |
| How efficient is it to use the current system?                                         |
| What are the drawbacks of the current system                                           |
| What can be done to bring improvement to the current system?                           |
| What issues have arised in the organisation - tell stories.                            |
| How well are the privacy and security maintained of the clients?                       |
| What are the concerns about the system voiced by the clients and volunteers?           |
| What things should remain unchanged in the current system?                             |
| What issues did they face with the supervisor and client                               |

| **Client Interview Questions**                                                       |
|--------------------------------------------------------------------------------------|
| Why did you choose this organisation?                                                |
| What is the best part of the current system in your opinion?                         |
| Are there any new features you want to see added?                                    |
| How easy is it to navigate through the system?                                       |
| How can the current system be made much easier?                                      |
| Are you comfortable with the current system’s privacy and security system? Explain.  |
| Have you experienced any inappropriate situations? If yes, what did you do about it? |
| What would make you feel more comfortable using this service?                        |

### 3. User Stories of the New System

**Welcome new user**

Show users a short welcome message and tell them about the service, how
it works, who it’s for, and how to get started.

**Sign up new user**

Users sign up by entering their name, email and optionally other
personal details. To maintain confidentiality, personal details can only
be accessed by Supervisors under special circumstances.

**Serve mental health questionnaire**

Immediately after signing up, all users are served a short questionnaire
to assess their current mental health, what they are expecting and their
preferences (if any).

**Request conversation**

A new user requests an anonymous conversation with a trained peer
support specialist after filling out the questionnaire.

**Poll peer support specialists**

Questionnaire responses are used to automatically rank available
specialist best fit for the requesting user. The system sends
notifications to the top 3 best fit specialists. If none respond within
a given period, notifications are sent to the next 3 and so on.

**Accept/Reject conversation request**

A peer support volunteer receives notification for a conversation
request. They examine the user's questionnaire responses and can choose
to accept or pass the request.

**Connect user and specialist**

Upon accepting the request, a chat thread is created where the user can
anonymously converse with the specialist. Both parties are given
pseudonyms by the system to ensure neither identity is revealed.

**Chat**

Users can only be connected to one volunteer at a time with whom they
can exchange messages (texts, images) at any time. Users get new message
notifications.

**AI moderated chat**

AI checks every image and link sent for inappropriate content. If found
to be inappropriate, the message is censored until the user gives
consent to view. Censorship events are logged (visible to supervisor of
this chat) and if a threshold number of these events occur, the chat is
automatically reported to the supervisor.

**Report conversation**

If a user is made to feel uncomfortable, they may choose to report the
conversation to have it checked by a Supervisor. User fills in a form
detailing their reasons for reporting

**Schedule chat**

Users in a chat can set schedules and the other party can agree/disagree
on the timing. If agreed, the application sends an alert reminding of
the scheduled chat. If disagreed, the user can offer a different time
and the other party can agree/disagree to that,

**Serve checkup questionnaires**

Bi-monthly questionnaires are served to all connected users to assess
the change in their mental health. Users can also express their
satisfaction/dissatisfaction with the specialist here. Periodically
examined by supervisors.

**Create/Answer custom questionnaire**

Volunteers can create customised questionnaires in chat for users to
answer.

**Peer support specialist dashboard**

Peer support specialists volunteering at the organisation are given
their own accounts. Log in to view conversations, questionnaire
responses and available requests.

**Supervisor dashboard**

Supervisors can view which users are connected to the volunteers under
them, along with the time spent active in each conversation.
Questionnaire responses of each connected user can be monitored from
here.

**View reported conversations**

Supervisors can check the entire chat history of reported conversations.
They may write responses to the reporting user in a special chat thread
that can be archived by the supervisor once resolved.

**View reported conversation chat**

Supervisors may view the entire chat log of conversations reported
manually. For AI-flagged chats, they must first request permission from
users and can only view if given by client.

**Reassign volunteer**

Supervisors may reassign a different volunteer to a user manually. They
may also reassign volunteers after a report.

**Ban client**

If reported for inappropriate behaviour or breach of terms, supervisors
may ban a client for a period of time. The client will be unable to send
messages in this period.

**Set questionnaire**

Administrator of the service can create/set the various questionnaires
served to users through the questionnaire creation wizard in their
dashboard

# **10. Major functionalities offered by the system**

-   Send and Receive chat messages (Chatting).

-   AI Chat moderator detects inappropriate contents.

-   Accepting volunteers.

-   View user related graphs and profiles.

-   Request to chat with a Volunteer.

-   Manually report chats.

-   Signup, Login, Ban/Removing Users.

-   Create and edit questionnaires.

-   Leave Application for Volunteers.

-   Report handling for Supervisors.

-   Edit user profiles and questionnaire responses.

# **11. Use Case Diagram**

## ***User Initiation System***

<img src="./media/image19.png"
style="width:6.78646in;height:4.34529in" />

## ***Notification System***

<img src="./media/image55.png"
style="width:6.85938in;height:3.88459in" />

## ***Chat System***

<img src="./media/image54.png"
style="width:7.46729in;height:5.57643in" />

## ***Report Handling System***

<img src="./media/image29.png"
style="width:7.17348in;height:7.11386in" />

## ***Questionnaire System***

<img src="./media/image26.png"
style="width:9.44291in;height:6.68056in" />

## ***User Management System***

<img src="./media/image46.png"
style="width:9.44291in;height:6.29167in" />

# **12. Normal and Alternate Scenarios**

<table>
<colgroup>
<col style="width: 59%" />
<col style="width: 1%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name :</strong></p>
<h2 id="user-signup">User signup</h2></th>
<th><strong>UniqueID: INIT01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area:</strong> User Signup page</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s):</strong> Client</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder :</strong> Supervisor,
volunteer</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description :</strong> Users are able to
register into the system.</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event:</strong> Click on Signup
button on the website</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type :</strong> External</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>Click on the Signup button</p>
</blockquote></li>
</ol></th>
<th colspan="2">Sign up form</th>
</tr>
<tr class="odd">
<th><ol start="2" type="1">
<li><blockquote>
<p>Complete the personal information section and click on the next
button</p>
</blockquote></li>
</ol></th>
<th colspan="2">Sign up form and personal details</th>
</tr>
<tr class="header">
<th><ol start="3" type="1">
<li><blockquote>
<p>Completes answering the questionnaires and clicks on the next
button.</p>
</blockquote></li>
</ol></th>
<th colspan="2">Questionnaire form, responses, preferences</th>
</tr>
<tr class="odd">
<th><ol start="4" type="1">
<li><blockquote>
<p>Read and agree to the Terms and conditions by clicking on the
checkbox. And clicks on signup</p>
</blockquote></li>
</ol></th>
<th colspan="2">Response and sign up form</th>
</tr>
<tr class="header">
<th><ol start="5" type="1">
<li><blockquote>
<p>System automatically sends request for chat to the volunteer</p>
</blockquote></li>
</ol></th>
<th colspan="2">Request</th>
</tr>
<tr class="odd">
<th colspan="3"><blockquote>
<p><strong>Alternative Scenario</strong></p>
</blockquote></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>User clicks on Sign Up.</p>
</blockquote></li>
<li><blockquote>
<p>Fills all the information required.</p>
</blockquote></li>
<li><blockquote>
<p>Clicks on submit but fails and shows “Already account created”.</p>
</blockquote></li>
<li><blockquote>
<p>User is redirected to the login page.</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Preconditions :</strong></p>
<ul>
<li><blockquote>
<p>Have an internet connection.</p>
</blockquote></li>
<li><blockquote>
<p>Complete each section at a time to proceed next.</p>
</blockquote></li>
<li><blockquote>
<p>Users might not be fully registered yet.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>User has successfully registered</p>
</blockquote></li>
<li><blockquote>
<p>User will be able to fully use the features of the system</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>User profile details have been properly registered in the system</p>
</blockquote></li>
<li><blockquote>
<p>User can view the signup page</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Success Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>User can request for volunteer</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Minimum Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>The profile details have been saved</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Requirements Met:</strong></p>
<ul>
<li><blockquote>
<p>Users are allowed to create new profiles and request for
volunteers.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Outstanding Issues :</strong></p>
<ul>
<li><blockquote>
<p>Can users log from different devices at the same time?</p>
</blockquote></li>
<li><blockquote>
<p>Can the users log back and complete the registration procedure or
start all over again?</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 58%" />
<col style="width: 0%" />
<col style="width: 40%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name :</strong></p>
<h2 id="reported-notifications">Reported notifications</h2></th>
<th><strong>UniqueID: NOTIF01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area :</strong> Notification System</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s) :</strong> Supervisor</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder :</strong> Client and Volunteer</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description :</strong> The notifications
received by the supervisor when malicious content is detected.</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event :</strong> Malicious text or
images detected by AI chat moderator</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type :</strong> Temporal</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>Logs into the system</p>
</blockquote></li>
</ol></th>
<th colspan="2">User ID and password</th>
</tr>
<tr class="odd">
<th><ol start="2" type="1">
<li><blockquote>
<p>Clicks on the notification button</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="header">
<th><ol start="3" type="1">
<li><blockquote>
<p>Views the notifications</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th><ol start="4" type="1">
<li><blockquote>
<p>Clicks on the notification and directed to the report page</p>
</blockquote></li>
</ol></th>
<th colspan="2">Report page</th>
</tr>
<tr class="header">
<th><ol start="5" type="1">
<li><blockquote>
<p>Responses to the report</p>
</blockquote></li>
</ol></th>
<th colspan="2">Report page</th>
</tr>
<tr class="odd">
<th colspan="3"><blockquote>
<p><strong>Alternative Scenarios</strong></p>
</blockquote></th>
</tr>
<tr class="header">
<th><blockquote>
<p>Report notification</p>
</blockquote>
<ol type="1">
<li><blockquote>
<p>Send notification to the supervisor.</p>
</blockquote></li>
<li><blockquote>
<p>Waits for few days for action</p>
</blockquote></li>
<li><blockquote>
<p>Resend the notification to another supervisor.</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Preconditions</strong></p>
<ul>
<li><blockquote>
<p>Must be logged into the website to view notification.</p>
</blockquote></li>
<li><blockquote>
<p>Users must have a good internet connection to get notifications
without any delay.</p>
</blockquote></li>
<li><blockquote>
<p>Users must be logged in as supervisor to be able to view the reported
notification.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>Supervisors receive notification and are directed to the report
detail page.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>User has a browser and a valid password and user ID.</p>
</blockquote></li>
<li><blockquote>
<p>User is logged into the system to view notification.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Success Guarantee:</strong></p>
<ul>
<li><blockquote>
<p>Supervisor can view the report detail page.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Minimum Guarantee</strong></p>
<ul>
<li><blockquote>
<p>Notification reached the supervisor's end.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Requirements Met :</strong></p>
<ul>
<li><blockquote>
<p>Supervisor can receive the reported notification.</p>
</blockquote></li>
<li><blockquote>
<p>Can receive notification without any delay.</p>
</blockquote></li>
<li><blockquote>
<p>Can instantly access the report detail page on clicking the
notification.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Outstanding Issues :</strong></p>
<ul>
<li><blockquote>
<p>Should the users be aware of the notification when not logged into
the system?</p>
</blockquote></li>
<li><blockquote>
<p>Can users delete the notifications?</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 59%" />
<col style="width: 1%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name:</strong></p>
<h2 id="have-conversations-in-chat">Have conversations in chat</h2></th>
<th><strong>UniqueID: CHA 01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area</strong>: Chat system</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s):</strong> Client, Volunteer, AI
moderator</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder:</strong> Supervisor</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description:</strong> Clients and volunteers can
have conversations over chat which is moderated by an AI moderator.</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event:</strong> Client or volunteer
sends a text or image in the chat window.</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type:</strong> External</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>Open chat window to view latest chat log</p>
</blockquote></li>
<li><blockquote>
<p>Enter text in chat box</p>
</blockquote></li>
<li><blockquote>
<p>Press send to send text</p>
</blockquote></li>
<li><blockquote>
<p>AI moderator verifies text does not contain blacklisted links</p>
</blockquote></li>
<li><blockquote>
<p>Receiver reads text delivered to them.</p>
</blockquote></li>
</ol></th>
<th colspan="2"><p>messages</p>
<p>anonymised sender information</p>
<p>message text</p></th>
</tr>
<tr class="odd">
<th><strong>Extensions or Alternative Scenarios</strong></th>
<th colspan="2"></th>
</tr>
<tr class="header">
<th><p><strong>Sending Images</strong></p>
<ol type="1">
<li><blockquote>
<p>Click on “Add image” button</p>
</blockquote></li>
<li><blockquote>
<p>Select image on device</p>
</blockquote></li>
<li><blockquote>
<p>Press send to send image</p>
</blockquote></li>
<li><blockquote>
<p>Image is compressed on device before sending off to server</p>
</blockquote></li>
<li><blockquote>
<p>AI moderator checks image for inappropriate content</p>
</blockquote></li>
<li><blockquote>
<p>Image is delivered to receiver</p>
</blockquote></li>
</ol>
<p><strong>Unblur Censored Image</strong></p>
<ol type="1">
<li><blockquote>
<p>AI blurs out images it considers inappropriate.</p>
</blockquote></li>
<li><blockquote>
<p>Warning message is displayed to user</p>
</blockquote></li>
<li><blockquote>
<p>User clicks “unblur image”</p>
</blockquote></li>
<li><blockquote>
<p>Request confirmation from user</p>
</blockquote></li>
<li><blockquote>
<p>Display image to user if confirmation received</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Preconditions:</strong></p>
<ul>
<li><blockquote>
<p>The volunteer is connected to this client by accepting their chat
request.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>Messages sent have been received by the other party</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>Neither party is banned by a supervisor.</p>
</blockquote></li>
<li><blockquote>
<p>Sender is logged in to the web or mobile application.</p>
</blockquote></li>
<li><blockquote>
<p>Receiver logs in (to view received messages).</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Success Guarantee:</strong></p>
<ul>
<li><blockquote>
<p>Message is delivered to the receiver’s device and is read.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Minimum Guarantee:</strong></p>
<ul>
<li><blockquote>
<p>Sent message has reached the server and been saved.</p>
</blockquote></li>
<li><blockquote>
<p>“Message censored” message shown.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Requirements Met:</strong></p>
<ul>
<li><blockquote>
<p>Exchange messages in chat via the server.</p>
</blockquote></li>
<li><blockquote>
<p>Volunteers and clients are kept anonymous to each other.</p>
</blockquote></li>
<li><blockquote>
<p>Employ AI to censor inappropriate images.</p>
</blockquote></li>
<li><blockquote>
<p>Images censored by the chat moderator AI can be unblurred with user
permission.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Outstanding Issues:</strong></p>
<ul>
<li><blockquote>
<p>Automatically resend messages that failed to be sent due to network
issues etc.?</p>
</blockquote></li>
<li><blockquote>
<p>Max size of text and image?</p>
</blockquote></li>
<li><blockquote>
<p>Can users delete sent texts?</p>
</blockquote></li>
<li><blockquote>
<p>Implement reply-in-thread feature?</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 60%" />
<col style="width: 0%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name:</strong></p>
<h2 id="view-flagged-conversation-report-details">View flagged
conversation report details</h2></th>
<th><strong>UniqueID: REP 01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area</strong>: Report Handling</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s):</strong> Supervisor</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder:</strong> Client, Volunteer</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description:</strong> Supervisor sees the user
or AI generated chat report details and decides what to do.</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event:</strong> Supervisor receives
“Conversation Reported” notification.</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type:</strong> External</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>Open Reported Conversation Overview page to view pending reports
table for this supervisor.</p>
</blockquote></li>
<li><blockquote>
<p>Latest reports are at the top of the table.</p>
</blockquote></li>
<li><blockquote>
<p>Click View Details to see details of the users and the
conversation</p>
</blockquote>
<ol type="1">
<li><blockquote>
<p>AI reported conversations have logs of previous moderation
events.</p>
</blockquote></li>
<li><blockquote>
<p>Manual reports have information filled in by the user in the report
form.</p>
</blockquote></li>
</ol></li>
<li><blockquote>
<p>Click “Handle Report” to open the report-handling wizard and take
appropriate action.</p>
</blockquote></li>
</ol></th>
<th colspan="2"><p>list of reported conversations</p>
<p>moderation events log</p>
<p>Report Conversation form responses</p></th>
</tr>
<tr class="odd">
<th><strong>Extensions or Alternative Scenarios</strong></th>
<th colspan="2"></th>
</tr>
<tr class="header">
<th><p><strong>View Entire Chat-log</strong></p>
<ol type="1">
<li><blockquote>
<p>To view the entire chat log of the manually reported conversation,
click “View Chat-log”.</p>
</blockquote></li>
<li><blockquote>
<p>Re-enter supervisor’s private access code in the popup.</p>
</blockquote></li>
<li><blockquote>
<p>2FA text sent to supervisor’s phone.</p>
</blockquote></li>
<li><blockquote>
<p>Upon identity verification, the supervisor is given access to view
the chat.</p>
</blockquote></li>
<li><blockquote>
<p>Access remains for a limited time.</p>
</blockquote></li>
</ol>
<p><strong>Request Permission to View Chat-log</strong></p>
<ol type="1">
<li><blockquote>
<p>Click “View Chat-log” of an AI-generated report.</p>
</blockquote></li>
<li><blockquote>
<p>Display “You do not have permission” message</p>
</blockquote></li>
<li><blockquote>
<p>Click “Request Access from Client”.</p>
</blockquote></li>
<li><blockquote>
<p>Re-enter supervisor’s private access code in the popup.</p>
</blockquote></li>
<li><blockquote>
<p>2FA text sent to supervisor’s phone.</p>
</blockquote></li>
<li><blockquote>
<p>Upon identity verification, type a message to users detailing why
permission is being requested.</p>
</blockquote></li>
<li><blockquote>
<p>The request with the message is delivered to the users.</p>
</blockquote></li>
<li><blockquote>
<p>Await permission given/declined notification to view chat.</p>
</blockquote></li>
</ol></th>
<th colspan="2">chat logs</th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Preconditions:</strong></p>
<ul>
<li><blockquote>
<p>Supervisor has entered his private access code after logging in to
view this page.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>Report Handling wizard has been started.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>Only the supervisor knows their specific access code so that no
unauthorised access occurs.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Success Guarantee:</strong></p>
<ul>
<li><blockquote>
<p>Supervisor has seen all the necessary report details to come to a
conclusion about handling it</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Minimum Guarantee:</strong></p>
<ul>
<li><blockquote>
<p>Supervisor can see the list of pending reports</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Requirements Met:</strong></p>
<ul>
<li><blockquote>
<p>View list of reported conversations.</p>
</blockquote></li>
<li><blockquote>
<p>Supervisor can see details of reported conversations such as user
information, conversation statistics, AI moderation logs.</p>
</blockquote></li>
<li><blockquote>
<p>Supervisor can ask for permission from users to view chat logs in
case of AI-filed reports.</p>
</blockquote></li>
<li><blockquote>
<p>Supervisors can access chat logs of manually reported conversations
for a limited period of time.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Outstanding Issues:</strong></p>
<ul>
<li><blockquote>
<p>What to do if supervisor identity cannot be verified</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 59%" />
<col style="width: 1%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name :</strong></p>
<h2 id="make-questionnaire">Make Questionnaire </h2></th>
<th><strong>UniqueID: QUT01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area:</strong> Admin Dashboard</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s):</strong> Admin and Supervisor</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder :</strong> Volunteer and client</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description :</strong> User is able to create a
new questionnaire or edit the previous one</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event:</strong> Click on the
questionnaire form</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type :</strong> External</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol start="6" type="1">
<li><blockquote>
<p>Click on the Questionnaire Tab</p>
</blockquote></li>
</ol></th>
<th colspan="2">Admin page</th>
</tr>
<tr class="odd">
<th><ol start="7" type="1">
<li><blockquote>
<p>View questionnaire form</p>
</blockquote></li>
</ol></th>
<th colspan="2">Questionnaire template</th>
</tr>
<tr class="header">
<th><ol start="8" type="1">
<li><blockquote>
<p>Click on any question to add or remove question</p>
</blockquote></li>
</ol></th>
<th colspan="2">Questionnaire form</th>
</tr>
<tr class="odd">
<th><ol start="9" type="1">
<li><blockquote>
<p>Click on publish to make the questionnaire visible</p>
</blockquote></li>
</ol></th>
<th colspan="2">Admin page</th>
</tr>
<tr class="header">
<th colspan="3"><blockquote>
<p><strong>Alternative Scenario</strong></p>
</blockquote></th>
</tr>
<tr class="odd">
<th><ol type="1">
<li><blockquote>
<p>Search questionnaire using ID</p>
</blockquote></li>
<li><blockquote>
<p>Click on edit button</p>
</blockquote></li>
<li><blockquote>
<p>Add/delete the questions in questionnaire</p>
</blockquote></li>
<li><blockquote>
<p>Click on draft button to store only</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Preconditions :</strong></p>
<ul>
<li><blockquote>
<p>Have an internet connection.</p>
</blockquote></li>
<li><blockquote>
<p>Must be logged in as Admin/Supervisor</p>
</blockquote></li>
<li><blockquote>
<p>There might be an existing questionnaire</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>User has successfully added a new questionnaire</p>
</blockquote></li>
<li><blockquote>
<p>Other users can view/use the questionnaire</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>User can view the questionnaire page</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Success Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>Clients can answer and view the new questionnaire form</p>
</blockquote></li>
<li><blockquote>
<p>Volunteers can use the questionnaire form</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Minimum Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>New questionnaire has been created</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Requirements Met:</strong></p>
<ul>
<li><blockquote>
<p>Admin is allowed to create and store new questionnaires</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Outstanding Issues :</strong></p>
<ul>
<li><blockquote>
<p>Can the admin have unlimited access in creating questionnaires
without any time constraints?</p>
</blockquote></li>
<li><blockquote>
<p>Can the admin re-edit the questionnaire immediately?</p>
</blockquote></li>
<li><blockquote>
<p>Do the admins need any approval from other admins before publishing
the new questionnaire?</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 59%" />
<col style="width: 1%" />
<col style="width: 39%" />
</colgroup>
<thead>
<tr class="header">
<th colspan="2"><p><strong>Use Case Name :</strong></p>
<h2 id="view-volunteer-profile">View Volunteer Profile</h2></th>
<th><strong>UniqueID: UM01</strong></th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Area:</strong> Volunteer profile page</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Actors(s):</strong> Volunteer</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Stakeholder :</strong> Supervisor,
Client,Admin</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Description :</strong> Users can view their own
profile details and edit</th>
</tr>
<tr class="odd">
<th colspan="3"><strong>Triggering Event:</strong> Click on Profile
button</th>
</tr>
<tr class="header">
<th colspan="3"><strong>Trigger Type :</strong> External</th>
</tr>
<tr class="odd">
<th><strong>Steps Performed (Main Path)</strong></th>
<th colspan="2"><strong>Information for steps</strong></th>
</tr>
<tr class="header">
<th><ol type="1">
<li><blockquote>
<p>Click on the profile button.</p>
</blockquote></li>
</ol></th>
<th colspan="2">Profile page</th>
</tr>
<tr class="odd">
<th><ol start="2" type="1">
<li><blockquote>
<p>View the profile details.</p>
</blockquote></li>
</ol></th>
<th colspan="2">User data</th>
</tr>
<tr class="header">
<th><ol start="3" type="1">
<li><blockquote>
<p>Click on the questionnaire button</p>
</blockquote></li>
</ol></th>
<th colspan="2">Profile page</th>
</tr>
<tr class="odd">
<th><ol start="4" type="1">
<li><blockquote>
<p>View questionnaire</p>
</blockquote></li>
</ol></th>
<th colspan="2">Questionnaire form</th>
</tr>
<tr class="header">
<th><ol start="5" type="1">
<li><blockquote>
<p>Click on edit button on profile page</p>
</blockquote></li>
</ol></th>
<th colspan="2">Request</th>
</tr>
<tr class="odd">
<th><ol start="6" type="1">
<li><blockquote>
<p>Edit the profile</p>
</blockquote></li>
</ol></th>
<th colspan="2">Profile form</th>
</tr>
<tr class="header">
<th><ol start="7" type="1">
<li><blockquote>
<p>Click on save button</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th colspan="3"><blockquote>
<p><strong>Alternative Scenario</strong></p>
</blockquote></th>
</tr>
<tr class="header">
<th><ol start="5" type="1">
<li><blockquote>
<p>User clicks on Sign Up.</p>
</blockquote></li>
<li><blockquote>
<p>Fills all the information required.</p>
</blockquote></li>
<li><blockquote>
<p>Clicks on submit but fails and shows “Already account created”.</p>
</blockquote></li>
<li><blockquote>
<p>User is redirected to the login page.</p>
</blockquote></li>
</ol></th>
<th colspan="2"></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Preconditions :</strong></p>
<ul>
<li><blockquote>
<p>Have an internet connection.</p>
</blockquote></li>
<li><blockquote>
<p>Must be logged in</p>
</blockquote></li>
<li><blockquote>
<p>Have permission to edit</p>
</blockquote></li>
<li><blockquote>
<p>Not a banned user</p>
</blockquote></li>
<li><blockquote>
<p>The user is already registered</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Postconditions:</strong></p>
<ul>
<li><blockquote>
<p>User can view profile</p>
</blockquote></li>
<li><blockquote>
<p>Can edit any detail if the user wishes</p>
</blockquote></li>
<li><blockquote>
<p>The new edit is visible</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Assumptions:</strong></p>
<ul>
<li><blockquote>
<p>User has a profile</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Success Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>Users can successfully view all details of their account.</p>
</blockquote></li>
<li><blockquote>
<p>Users can successfully edit and save the profile details.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Minimum Guarantee :</strong></p>
<ul>
<li><blockquote>
<p>The profile details is displayed</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="header">
<th colspan="3"><p><strong>Requirements Met:</strong></p>
<ul>
<li><blockquote>
<p>Users are allowed to view and edit accounts.</p>
</blockquote></li>
</ul></th>
</tr>
<tr class="odd">
<th colspan="3"><p><strong>Outstanding Issues :</strong></p>
<ul>
<li><blockquote>
<p>Can a banned user view their account?</p>
</blockquote></li>
<li><blockquote>
<p>Are there any restrictions on the number of times a user can
edit?</p>
</blockquote></li>
</ul></th>
</tr>
</thead>
<tbody>
</tbody>
</table>

# **13. Functional Requirements**

##  ***User Initiation System***

1.  Client inputs personal information, completes a questionnaire to be
    > a registered member.

2.  Login with email and password.

3.  Clients can request for volunteer

4.  Interested people can apply for volunteer positions by uploading the
    > required documents and signing up.

5.  The chosen volunteer will be sent an email regarding the
    > confirmation of their selection.

6.  Selected volunteers will have to activate their account (which will
    > be created by the administrator) using email

7.  Volunteers can be able to accept/reject requests of clients.

## ***Notification System***

1.  System sends notification/request to the best fit Volunteer.

2.  Clients get notified about the selection of new volunteer after
    > request

3.  Volunteers and clients receive notification of unread chat messages
    > while they are away.

4.  System sends notification to both volunteers and clients of their
    > scheduled session ahead of time.

5.  Supervisor receives notification for any AI flagged chats

6.  System notifies the supervisor of a new reported chat made by a
    > client or volunteer.

7.  Admin receives notification of a new submitted request for leave
    > application made by employees

8.  Volunteers receive notification of the decision to leave.

## ***Chat System***

1.  Exchange texts and images in chat. Volunteers and clients are kept
    > anonymous to each other.

2.  Set chat schedules..

3.  AI censors images and links deemed inappropriate, logs censorship
    > events.

4.  Give permission to unblur censored images/links by the chat
    > moderator AI.

##  ***Report Handling System***

1.  Manually report inappropriate behaviour in chat.

2.  AI automatically reports chat if the threshold number of
    > inappropriate images sent.

3.  View manual and AI-generated reports of inappropriate behaviour.

4.  View chat logs and questionnaire responses of reported chats.

5.  View logs of censorship events, along with censored images. Report
    > false positives.

6.  Send a message to reporting and reported users to explain how the
    > report has been dealt with.

7.  Ban a user for an amount of time following inappropriate behaviour.

8.  Reassign a volunteer in a chat.

## ***Questionnaire System***

1.  Create a new questionnaire.

2.  Edit previous questionnaire.

3.  Can view questionnaire responses.

4.  Users can insert responses to the questionnaires.

5.  Both responses and questionnaires can be stored.

6.  Create a new newsletter and publish.

7.  Users can edit questionnaire responses.

## ***User Management System***

1.  View Volunteer-Client Statistics.

2.  Users can view and edit profile information.

3.  Clients can delete their account.

4.  Supervisors can ban or remove volunteer accounts.

5.  Admin can view system statistics.

6.  Volunteers can view their statistics.

7.  Volunteers can apply for leave applications.

8.  Supervisors can approve/reject leave applications.

# **14. Non-Functional Requirements**

-   ## ***Privacy***

    -   Identifying information of clients should only be visible to
        > authorised personnel of the organisation and only under
        > special circumstances.

    -   Volunteers and clients should be anonymous to one another.

    -   Screenshot-prevention feature in chat window.

    -   Chat logs accessible to supervisors only in case of reports.

-   ## ***Security:***

    -   End to end encryption of chats.

    -   Encrypted storage of all user data in servers.

    -   Store only the bare minimum user data in servers.

-   ## ***Cost:***

    -   Compress all images on the user end to minimise server
        > bandwidth/storage requirements.

    -   Should not contain proprietary components that may incur
        > expensive licensing fees.

    -   Back-end must run on a cloud server provider’s budget-tier plan.

-   ## ***Usability:***

    -   Mobile app with simple, intuitive UI with the bare minimum of
        > features to prevent confusion.

    -   Tooltips for every interactive UI element.

    -   Always-accessible tutorial/overview of the service built into
        > the app - informs clients of how to use it and how the service
        > works, along with simple and clear explanations of the privacy
        > policies they can expect.

    -   Cheerful UI design with soothing colours.

    -   Darkmode support.

    -   UI must accommodate for users with visual (including colour
        > blindness) or auditory impairments.

    -   Supports both English and Bangla.

    -   Chatting must be instantaneous; minimal lag.

-   ## ***Misc.***

    -   Must be fully open source for the sake of transparency.

    -   Must be easily auditable to ensure confidentiality of user data
        > is being maintained.

    -   Apps must respect user privacy - no ads, no data gathering or
        > unnecessary device permissions.

    -   Maintainable by a small team.

    -   Not dependent on third party developer’s components, as
        > long-term support may not be guaranteed with those.

**<u>Section 4:</u>**

# **15. Entity Relationship Diagram**

<img src="./media/image7.png"
style="width:9.44291in;height:7.04167in" />

# **16. Logical Data Flow diagram**

## ***Diagram 0***

<img src="./media/image32.png"
style="width:9.44291in;height:6.45833in" />

## ***User Initiation System***

### **Logical Dataflow: Existing**

<img src="./media/image47.png"
style="width:7.79688in;height:5.09867in" />

### 

### **Logical Dataflow: Proposed**

<img src="./media/image48.png"
style="width:8.04688in;height:5.8555in" />

## ***Notification System***

### **Logical Dataflow: Proposed**

<img src="./media/image14.png"
style="width:9.44291in;height:5.80556in" />

## ***Chat System***

### **Logical Dataflow: Existing**

<img src="./media/image36.png"
style="width:8.34537in;height:5.00517in" />

### **Logical Dataflow: Proposed**

<img src="./media/image12.png"
style="width:9.44291in;height:6.86111in" />

## ***Report System***

### **Logical Dataflow: Existing**

<img src="./media/image23.png"
style="width:7.48438in;height:4.4211in" />

### **Logical Dataflow: Proposed**

<img src="./media/image15.png"
style="width:9.44291in;height:7.73611in" />

## ***Questionnaire System***

### **Logical Dataflow: Existing**

<img src="./media/image42.png"
style="width:7.47396in;height:6.74479in" />

### **Logical Dataflow: Proposed**

<img src="./media/image52.png"
style="width:7.32813in;height:6.03845in" />

## ***User Management System***

### **Logical Dataflow: Proposed**

### <img src="./media/image41.png"
style="width:7.74729in;height:5.95567in" />

# **17. Physical Data Flow diagram**

## ***User Initiation System***

<img src="./media/image35.png" style="width:8.935in;height:4.98958in" />

## 

## ***Notification System***

<img src="./media/image38.png"
style="width:8.27205in;height:6.16368in" />

## ***Chat System***

<img src="./media/image22.png"
style="width:8.26292in;height:5.86818in" />

## 

## ***Report System***

<img src="./media/image4.png"
style="width:8.43229in;height:7.07537in" />

# **18. Activity diagrams**

## ***Activity: User Initiation System*** 

<img src="./media/image65.png"
style="width:8.65104in;height:7.31571in" />

## ***Activity: Volunteer signup System***

<img src="./media/image44.png"
style="width:8.81771in;height:9.72184in" />

## ***Activity: Report Notification System***

<img src="./media/image40.png"
style="width:8.83094in;height:6.08854in" />

## ***Activity: Chat Notification System***

<img src="./media/image56.png"
style="width:8.89376in;height:9.26563in" />

## ***Activity: Chat System***

<img src="./media/image57.png"
style="width:9.31809in;height:6.67815in" />

## ***Activity: Report System***

<img src="./media/image43.png"
style="width:9.67211in;height:7.48921in" />

## ***Activity: Questionnaire System***

<img src="./media/image51.png"
style="width:9.44291in;height:9.19444in" />

# **19. Sequence diagrams**

## ***User Initiation System***

### ***User sign up***

### <img src="./media/image33.png"
style="width:8.81521in;height:3.82026in" />

## 

## ***Notification System***

### ***Reported Notification***

<img src="./media/image37.png"
style="width:8.71604in;height:4.54167in" />

## ***Chat System***

### **Have Conversations**

## <img src="./media/image5.png"
style="width:9.44291in;height:4.72222in" />

##  *Report System*

###  **View Reported Conversation**

<img src="./media/image3.png"
style="width:9.44291in;height:5.18056in" />

## *Questionnaire System*

### **Edit Questionnaire**

<img src="./media/image34.png"
style="width:6.79089in;height:7.73749in" />

# **20. Communication diagrams**

## ***User Initiation System***

### **User sign up**

<img src="./media/image6.png"
style="width:9.44792in;height:1.81691in" />

## ***Notification System***

### **Reported Notification**

<img src="./media/image11.png"
style="width:7.53917in;height:3.59008in" />

## ***Chat System***

### **Have Conversations**<img src="./media/image10.png"
style="width:9.44291in;height:4.09722in" />

## 

## ***Report System***

### **View Reported Conversation**<img src="./media/image27.png"
style="width:8.29514in;height:4.75576in" />

## ***Questionnaire System***

### **Make questionnaire**

<img src="./media/image13.png"
style="width:7.87327in;height:3.16355in" />

# **21. Class diagrams**

<img src="./media/image25.png"
style="width:9.44291in;height:10.30556in" />

# **22. State-chart diagrams.**

## ***Client class***

<img src="./media/image17.png" style="width:6.5in;height:4in" />

## ***Volunteer class***

<img src="./media/image59.png" style="width:6.5in;height:7.47621in" />

## ***Chat class***

<img src="./media/image1.png"
style="width:7.39583in;height:4.91697in" />

## 

## ***Report class***

<img src="./media/image28.png"
style="width:6.77762in;height:6.14504in" />

## ***Leave Application class***

<img src="./media/image49.png"
style="width:7.79938in;height:3.26691in" />

## ***Questionnaire class***

<img src="./media/image31.png"
style="width:7.98708in;height:3.14736in" />

# **23. CRUD matrix**

## ***User Initiation System***

| **Activity**                        | **Client** | **Volunteer** | **Admin** | **Supervisor** | **AI Chat Moderator** |
|-------------------------------------|------------|---------------|-----------|----------------|-----------------------|
| Enter Client Personal Details       | U          |               |           |                |                       |
| Create Client Account               | C          |               |           |                |                       |
| Complete signup questionnaire       | U          |               |           |                |                       |
| User log in                         | R          | R             | R         | R              |                       |
| Upload Volunteer Documents          |            | U             |           |                |                       |
| Enter Volunteer Application Details |            | U             |           |                |                       |
| View New Volunteer Application      |            |               | R         | R              |                       |
| Accept/Reject Volunteer             |            |               | U         | U              |                       |
| Create Applicant Account            |            |               | C         | C              |                       |
| Send Notification                   | C          |               |           | CU             | CU                    |
| Deliver Notification                | RU         |               |           | R              |                       |
| Volunteer request                   | C          |               |           |                |                       |

## 

## ***Chat System***

| **Activity**                  | **Chats** | **UserRecords** | **Reports** | **CensorLogs** |
|-------------------------------|-----------|-----------------|-------------|----------------|
| Report Conversation           | R         | R               | C           | R              |
| View Report Details           |           |                 | R           | R              |
| Write Report-Handling Message |           |                 | RU          |                |
| Request Chat-log Access       | U         | R               | RU          |                |
| Grant Chat-log Access         | U         |                 | RU          |                |
| View Chat-log                 | R         |                 |             |                |
| Ban/Reassign                  |           | RU              | RU          |                |

## 

## 

## 

## ***Report System***

| **Activity**   | **Chats** | **CensorLogs** | **Notifications** |
|----------------|-----------|----------------|-------------------|
| Send Message   | CRU       |                |                   |
| Load Messages  | R         |                |                   |
| Censor Message | R         | CR             |                   |
| Schedule Chat  |           |                | C                 |
| Unblur Message | U         |                |                   |

## ***Questionnaire System***

| **Activity**                 | **Questionnaire** |
|------------------------------|-------------------|
| Create questionnaire         | C                 |
| View questionnaire           | R                 |
| Edit questionnaire responses | RU                |
| Edit questionnaire           | U                 |
| Publish questionnaire        | CU                |

**<u>Section 5:</u>**

# **24. Structure English pseudo code for the system**

## ***User Initiation System***

<img src="./media/image16.png"
style="width:6.24324in;height:11.81004in" />

## ***Notification System***

<img src="./media/image21.png"
style="width:7.47352in;height:8.4311in" />

## ***Having Conversations***

<img src="./media/image2.png"
style="width:8.29986in;height:8.40448in" />

## ***Handle Reports***

<img src="./media/image20.png"
style="width:8.45492in;height:11.45656in" />

## ***User Management***

<img src="./media/image39.png"
style="width:9.44291in;height:11.27778in" />

## ***Questionnaire Management***

<img src="./media/image8.png"
style="width:9.44291in;height:13.41667in" />

# **25. Prototype the user interface**

## ***User Signup***

<img src="./media/image61.png"
style="width:7.69558in;height:4.31775in" />

## ***Volunteer Application***

<img src="./media/image64.png"
style="width:7.80609in;height:4.37305in" />

## ***User Login***

<img src="./media/image58.png"
style="width:8.02372in;height:4.49692in" />

## ***Chat*** 

<img src="./media/image50.png"
style="width:8.24479in;height:4.6269in" />

## ***Chat Client List (visible to volunteers only)***

<img src="./media/image67.png"
style="width:8.14346in;height:4.56558in" />

## ***Chat Schedule***

<img src="./media/image63.png"
style="width:8.08854in;height:4.53921in" />

## ***Chat Questionnaire***

<img src="./media/image60.png" style="width:7.94255in;height:4.451in" />

## 

## ***Add Custom Questionnaire (visible to volunteers only)***

<img src="./media/image71.png"
style="width:7.84567in;height:4.4072in" />

## ***Chat Notification***

<img src="./media/image62.png"
style="width:7.75048in;height:4.34683in" />

## 

## ***Report Chat***

<img src="./media/image72.png"
style="width:7.77604in;height:4.36462in" />

## 

## ***Report Management***

<img src="./media/image70.png"
style="width:7.41146in;height:4.15357in" />

## ***AI-flagged Report Details***

<img src="./media/image66.png"
style="width:7.53187in;height:4.22027in" />

## 

## ***Manually-flagged Report Details***

<img src="./media/image68.png"
style="width:7.68229in;height:4.31429in" />

## 

## ***Report-handling wizard***

<img src="./media/image53.png"
style="width:7.74614in;height:4.34909in" />

## ***Leave Application List***

<img src="./media/image69.png"
style="width:7.05729in;height:3.96049in" />

## ***Leave Application Details***

<img src="./media/image45.png"
style="width:7.37206in;height:4.13282in" />

## ***Admin Add Questionnaire***

<img src="./media/image73.png"
style="width:7.32042in;height:4.11118in" />
