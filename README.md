<img src="./Pictures/100002010000009600000096AC1A0BD80DA021DF.png"
style="width:2.7992in;height:2.7992in" />

**Independent University, Bangladesh**

**Department of Computer Science & Engineering**

**CSE 307: System Analysis and Design**

**Spring 2022**

**Term Project**

<span
id="anchor"></span><img src="./Pictures/10000201000002000000020087F7B80368049991.png"
style="width:2.122in;height:2.122in" />

<span id="anchor-1"></span>HealthyMind

<span id="anchor-2"></span>A Peer Counselling Platform

<span id="anchor-3"></span>**Fahim Ahmed**  
2022409

<span id="anchor-4"></span>**Suhaila**

<span id="anchor-5"></span>1910496

<span id="anchor-6"></span>**Mir Shafayat Ahmed**

<span id="anchor-7"></span>1910456

<span id="anchor-8"></span>**Table of Contents**

<span id="anchor-9"></span>***Section 1:***

<span id="anchor-10"></span>**1. Introduction**

HealthyMind is a non-profit organisation aimed at providing peer-support
services to people of all ages. It is run by a group of mental health
professionals, supervising a team of volunteers who counsel clients over
an internet messaging service. Clients register for the service and are
assigned a volunteer. Both parties remain anonymous to one another. Once
connected, they can have conversations and receive counselling and
support. At present their operations are small in scale; employing only
a dozen or so volunteers, each connected to around five clients.

<span id="anchor-11"></span>**2. History leading to project request**

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

<span id="anchor-12"></span>**3. Problems, opportunities**

<span id="anchor-13"></span>***Problems and Solutions***

|                                                                                                       |                                                                                                                                                                                                                                 |                                                                                                                                                                                                             |
|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                       | Problem                                                                                                                                                                                                                         | Solution                                                                                                                                                                                                    |
| Manual, tedious registration process that involves going to another site. May discourage signing up.  | User initiation will be handled within the application in a guided manner. Users will not be taken to another site.                                                                                                             |                                                                                                                                                                                                             |
| Anonymity difficult to maintain due to Facebook being used                                            | User details will only be visible to supervisors in the new system.                                                                                                                                                             |                                                                                                                                                                                                             |
| Confidentiality cannot be maintained as one volunteer’s messages are not kept isolated from another’s | Each volunteer will have completely separate accounts so this limitation of the previous messaging platform will not apply. Only supervisors will have access to chat logs, and only after a report has been filed by the user. |                                                                                                                                                                                                             |
|                                                                                                       | Supervising a large number of chats unfeasible                                                                                                                                                                                  | AI will be employed to moderate chats. Alerts will be sent to supervisors if inappropriate activity is detected.                                                                                            |
|                                                                                                       | Reporting conversations is done manually via google forms                                                                                                                                                                       | Reporting can be done within the chat application window.                                                                                                                                                   |
|                                                                                                       | Pending reports have to be periodically by supervisors.                                                                                                                                                                         | Urgent alerts will be sent to the supervisor whenever a conversation is reported. All pending reports can be seen in the supervisor’s dashboard.                                                            |
|                                                                                                       | Reports have to dealt with manually                                                                                                                                                                                             | List of possible actions can be seen in the dashboard and handing can be done directly from there                                                                                                           |
|                                                                                                       | Various mental health assessment questionnaires have to be taken off-site                                                                                                                                                       | Editable questionnaires will be integrated into the application so users can have a seamless experience.                                                                                                    |
|                                                                                                       | Questionnaires have to be manually handed out.                                                                                                                                                                                  | Questionnaires can be scheduled and set by supervisors and volunteers. These are to be automatically distributed to clients and the responses can be accessed in a convenient manner from their dashboards. |
|                                                                                                       | Conversations have to be manually scheduled/agreed upon by parties                                                                                                                                                              | Scheduling and notification system will be integrated in the chat application itself.                                                                                                                       |

<span id="anchor-14"></span>***Opportunities***

-   No similar all-in-one platform currently exists.
-   User convenience will be unparalleled.
-   AI-based supervision would ensure confidentiality.
-   Automation will reduce supervisor workloads and will allow them to
    work more efficiently.
-   Volunteer management (leaves, signup, assigning) can be done via
    this application.
-   Chat application will be purpose-designed for this organisation’s
    needs so it can better guarantee confidentiality.
-   Due to questionnaires etc. being integrated into the chat
    application, the new system can give a much more cohesive and
    unified experience.
-   Confidentiality and convenience will attract a large number of
    users.
-   Automation will allow the organisation to scale up their operations.

<span id="anchor-15"></span>**4. Project goal and objectives**

HealthyMind aims to provide cost free service to the users ranging from
all ages. This website is designed to provide a safe space and learning
environment for people without fear of judgement, misunderstanding,
harassment or abuse. It carves out a way for promotion of mental health
through service, advocacy, and education. It offers a very efficient ,
smooth, and comfortable website to use (from home) as well as an
excellent platform that is accessible for all people (including
disability).

One of the advantages is that the users can easily navigate through the
platform with minimum effort where the service can be available 24/7. In
addition, the platform is structured in a way ensuring confidentiality
of both client and volunteer through high monitoring by the employees to
ensure a safe and secure environment for both the parties.

<span id="anchor-16"></span>***Section 2:***

<span id="anchor-17"></span>**5. Product Description**

1.  **Product summary**

It is a platform in which people from all around Bangladesh can connect
and share their inner thoughts while being anonymous to a peer support
volunteer. The volunteers can also apply with just a few steps by
signing up and uploading their resume. The administration is updated
from time to time of the ongoing activities on the website. Moreover,
they can maintain and have an overview of all the users at any
preferable time they want.

Furthermore, after the volunteers and clients have successfully
registered and are part of HealthyMind, they can start communicating
with each other with proper security and privacy ensured on both ends
and also set up schedules if they wish. On the other hand, The volunteer
has an option to even reject a request for chat and clients can also
wish to reassign the volunteer. To maintain security and privacy, an AI
chat moderator is incorporated in the system which will detect any
inappropriate images or messages sent in the chat log and immediately
notify the supervisor.

To summarise, the platform will help increase awareness of mental health
and people will be more willing to share their problems.

1.  **Product Stakeholders**

-   Client

-   Admin

-   Supervisor

-   Volunteer

<span id="anchor-18"></span>**6. System Context diagram**

<img src="./Pictures/100002010000080000000512485BA97A4125E52C.png"
style="width:9.4429in;height:5.9862in" />

<span id="anchor-19"></span>**7. Hardware detail (Include Rich
Picture)**

**Frontend**:

-   Smartphone, PC or Laptop
-   Internet connection capable of smooth browsing experience
-   A Web Browser or an Android or iOS app.

**Backend:**

-   Servers capable of handling 1000 users concurrently hosted by a
    cloud service provider.
-   At least 100MB of storage allocated per user.
-   A relational database - MySQL.
-   A language like Python that is capable of handling thousands of
    requests every second.

<img src="./Pictures/10000201000003A80000026EA5BF3E721623AA59.png"
style="width:8.5417in;height:5.6945in" />

<span id="anchor-20"></span>**8. Key Technical Features of Software**

-    JavaScript will be the main frontend language as it allows for
    making Web Apps that can easily be made into Native apps for Android
    and iOS. Ensuring compatibility.
-    Compute-Heavy tasks like Image Manipulation and Natural Language
    Processing are offloaded to powerful servers, hence allowing for
    older smartphones to use the service.
-    AI model inappropriate content detection is incorporated in the
    system to detect inappropriate chat messages.
-    Backend uses Django/Python for ease of maintainability.
-    End-to-end encryption of all chat messages using SHA256 to ensure
    privacy.
-    User authentication code system to ensure sensitive data is not
    revealed.
-    OTP 2FA used for signup/login

<span id="anchor-21"></span>***Section 3:***

<span id="anchor-22"></span>**9. Information Gathering methods (At least
three methods)**

<span id="anchor-23"></span>Upon a cursory examination of the
organisation, we settled for several interactive data gathering messages
for this project. Due to the small size of the organisation, sampling a
large pool of members was not an option. The decentralised/virtual
nature of the organisation, plus the need for maintaining strict
confidentiality did not permit us the ability to sit down and observe
organisation members carrying out their day to day tasks in their own
environment. Information gathering was carried out in phases:

-   <span id="anchor-24"></span>***Questionnaires: ***

To gather preliminary information about their requirements,
questionnaires were emailed to all the volunteers and supervisors
working under the organisation, plus a few willing clients of the
organisation. The questionnaire had a small description of the new
system to give them some context. Responses were submitted via Google
Forms.

-   <span id="anchor-25"></span>***Interviews: ***

Our interviewer carried out background research by taking notes of the
facebook page of the organisation, their blog and their press releases
detailing the policies, values and vision of the organisation.

We decided to individually interview the vice president (who is also a
former supervisor), a peer support volunteer and two willing clients.
Interview questions were mailed out a week in advance to prepare the
interviewees. The interview was conducted virtually as each individual
was situated at different places. Each session lasted approximately an
hour.

The objective of the interview was to find out how they worked, their
software requirements, what they wish to achieve with the new system,
the resource budget etc. Beside the specific interview questions,
interviewees were encouraged to elaborate on their questionnaire
answers, tell us stories about their time with the organisation, voice
their personal concerns with the old and new system and their opinions
on certain policies and requirements of the organisation.

-   <span id="anchor-26"></span>***JAD sessions: ***

At a later date following the conclusion of the interviews, we sat down
together with all the interviewees for four consecutive days to discuss
the functionalities and UI of the system.

After an hour-long orientation session, led jointly by our senior
analyst and the organisation’s vice president, we first wrote down the
user stories of the existing system, and decided upon the logical
workflow. We raised concerns about some of their requirements (namely,
the extent of the AI moderator’s abilities) - the cost, workability and
practicality made certain requirements unfeasible with their budgetary
constraints and our limited expertise. They were understanding and we
settled upon a scalable system that would allow easy integration with
the components that they may wish to add in the future.

Once the workflow and requirements were tweaked to satisfaction, the new
user stories were written up and the entirety of the last day was spent
drawing up the user interface. Here the clients of the organisation had
particular inputs about its ease of use, which was incorporated into the
final prototype.

  
Samples for the questions and the user stories generated are attached
below.

<span id="anchor-27"></span>Samples

<span id="anchor-28"></span>1. Questionnaire Sample

<table>
<tbody>
<tr class="odd">
<td><strong>Choose your position:</strong></td>
</tr>
<tr class="even">
<td><strong>How long have you been involved with the
organisation?</strong></td>
</tr>
<tr class="odd">
<td><strong>What device(s) do you currently use to access the service?
(Check all that apply)</strong></td>
</tr>
<tr class="even">
<td><strong>How much time do you spend using the service every
week?</strong></td>
</tr>
<tr class="odd">
<td><strong>Rate your satisfaction with the current system (on a scale
of 1-10): _______</strong></td>
</tr>
<tr class="even">
<td><strong>How much are you willing to adapt to the new
system?</strong></td>
</tr>
<tr class="odd">
<td><strong>Which is most important?</strong></td>
</tr>
<tr class="even">
<td><p><strong>Explain your role in the organisation.</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>How effective do you find the current system at its task
of providing/receiving counselling?</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>Why?</strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>What would make it easier for you to more effectively use
the service? </strong></p>
<p><strong>_______________________________________________________________________</strong></p>
<p><strong>_______________________________________________________________________</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Briefly describe 3 worst aspects about the current system
in your opinion.</strong></p></td>
</tr>
</tbody>
</table>

\* only questions shown here, no instructions etc.

<span id="anchor-29"></span>2. Interview Questions

|                                                                                                         |
|---------------------------------------------------------------------------------------------------------|
| **Supervisor/Vice President Interview Questions (arranged in a funnel to extract maximum information)** |
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

|                                                                                        |
|----------------------------------------------------------------------------------------|
| **Volunteer Interview Questions (arranged in a pyramid to ease them into opening up)** |
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

|                                                                                      |
|--------------------------------------------------------------------------------------|
| **Client Interview Questions**                                                       |
| Why did you choose this organisation?                                                |
| What is the best part of the current system in your opinion?                         |
| Are there any new features you want to see added?                                    |
| How easy is it to navigate through the system?                                       |
| How can the current system be made much easier?                                      |
| Are you comfortable with the current system’s privacy and security system? Explain.  |
| Have you experienced any inappropriate situations? If yes, what did you do about it? |
| What would make you feel more comfortable using this service?                        |

<span id="anchor-30"></span>3. User Stories of the New System

**Welcome new user**

Show users a short welcome message and tell them about the service, how
it works, who it’s for, and how to get started.

**Sign up new user **

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

<span id="anchor-31"></span>**10. Major functionalities offered by the
system**

-   Send and Receive chat messages (Chatting).
-   AI Chat moderator detects inappropriate contents.
-   Accepting volunteers.
-   View user related graphs and profiles.
-   Request to chat with a Volunteer.
-   Manually report chats.
-   Signup, Login, Ban/Removing Users.
-   Create and edit questionnaires.
-   Leave Application for Volunteers.
-    Report handling for Supervisors.
-   Edit user profiles and questionnaire responses.

<span id="anchor-32"></span>**11. Use Case Diagram**

<span id="anchor-33"></span>***User Initiation System***

<span
id="anchor-34"></span><img src="./Pictures/10000000000004C40000030C7B5005AAE66A320F.png"
style="width:6.7866in;height:4.3453in" />

<span id="anchor-35"></span>***Notification System***

<img src="./Pictures/100000000000064000000384793197084312B896.png"
style="width:6.8598in;height:3.8846in" />

<span id="anchor-36"></span>***Chat System***

<img src="./Pictures/1000020100000800000005FB6763B69FB3EF57EA.png"
style="width:7.4673in;height:5.5764in" />

<span id="anchor-37"></span>***Report Handling System***

<img src="./Pictures/10000201000004550000044C110C81E4C35AD101.png"
style="width:7.1736in;height:7.1138in" />

<span id="anchor-38"></span>***Questionnaire System***

<img src="./Pictures/1000000000000576000003DD0678FC73B1D7AB46.png"
style="width:9.4429in;height:6.6807in" />

<span id="anchor-39"></span>***User Management System***

<img src="./Pictures/100000000000050B0000035C6FB50728F4C97973.png"
style="width:9.4429in;height:6.2917in" />

<span id="anchor-40"></span>**12. Normal and Alternate Scenarios**

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name :</strong></p>
<p><span id="anchor-41"></span>User signup</p></td>
<td><strong>UniqueID: INIT01</strong></td>
</tr>
<tr class="even">
<td><strong>Area:</strong> User Signup page</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s): </strong>Client</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder : </strong>Supervisor, volunteer</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description : </strong>Users are able to register into the
system.</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event: </strong>Click on Signup button on the
website</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type : </strong>External </td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td>Sign up form</td>
</tr>
<tr class="even">
<td></td>
<td>Sign up form and personal details</td>
</tr>
<tr class="odd">
<td></td>
<td>Questionnaire form, responses, preferences </td>
</tr>
<tr class="even">
<td></td>
<td> Response and sign up form</td>
</tr>
<tr class="odd">
<td></td>
<td>Request</td>
</tr>
<tr class="even">
<td><strong>Alternative Scenario</strong></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Preconditions : </strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Postconditions:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Success Guarantee :</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Minimum Guarantee :</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Requirements Met: </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Outstanding Issues : </strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name :</strong></p>
<p><span id="anchor-42"></span>Reported notifications</p></td>
<td><strong>UniqueID: NOTIF01</strong></td>
</tr>
<tr class="even">
<td><strong>Area : </strong>Notification System</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s) : </strong>Supervisor</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder : </strong>Client and Volunteer</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description : </strong>The notifications received by the
supervisor when malicious content is detected.</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event : </strong>Malicious text or images
detected by AI chat moderator</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type : </strong>Temporal</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td>User ID and password</td>
</tr>
<tr class="even">
<td></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td>Report page</td>
</tr>
<tr class="odd">
<td></td>
<td>Report page</td>
</tr>
<tr class="even">
<td><strong>Alternative Scenarios</strong></td>
<td></td>
</tr>
<tr class="odd">
<td>Report notification</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Preconditions</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Postconditions: </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Success Guarantee: </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Minimum Guarantee </strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Requirements Met : </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Outstanding Issues : </strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name: </strong></p>
<p><span id="anchor-43"></span>Have conversations in chat</p></td>
<td><strong>UniqueID: CHA 01</strong></td>
</tr>
<tr class="even">
<td><strong>Area</strong>: Chat system</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s):</strong> Client, Volunteer, AI moderator</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder: </strong>Supervisor</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description: </strong>Clients and volunteers can have
conversations over chat which is moderated by an AI moderator.</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event: </strong>Client or volunteer sends a text
or image in the chat window.</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type:</strong> External</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td><p>messages</p>
<p>anonymised sender information</p>
<p>message text</p></td>
</tr>
<tr class="even">
<td><strong>Extensions or Alternative Scenarios</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Sending Images</strong></p>
<p><strong>Unblur Censored Image</strong></p></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Preconditions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Postconditions:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Success Guarantee:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Minimum Guarantee:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Requirements Met:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Outstanding Issues:</strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name: </strong></p>
<p><span id="anchor-44"></span>View flagged conversation report
details</p></td>
<td><strong>UniqueID: REP 01</strong></td>
</tr>
<tr class="even">
<td><strong>Area</strong>: Report Handling</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s):</strong> Supervisor</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder: </strong>Client, Volunteer</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description: </strong>Supervisor sees the user or AI
generated chat report details and decides what to do.</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event: </strong>Supervisor receives “Conversation
Reported” notification.</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type:</strong> External</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td><p>list of reported conversations</p>
<p>moderation events log</p>
<p>Report Conversation form responses</p></td>
</tr>
<tr class="even">
<td><strong>Extensions or Alternative Scenarios</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>View Entire Chat-log</strong></p>
<p><strong>Request Permission to View Chat-log</strong></p></td>
<td><p>chat logs</p></td>
</tr>
<tr class="even">
<td><strong>Preconditions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Postconditions:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Success Guarantee:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Minimum Guarantee:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Requirements Met:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Outstanding Issues:</strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name :</strong></p>
<p><span id="anchor-45"></span>Make Questionnaire </p></td>
<td><strong>UniqueID: QUT01</strong></td>
</tr>
<tr class="even">
<td><strong>Area:</strong> Admin Dashboard</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s): </strong>Admin and Supervisor</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder : </strong>Volunteer and client</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description : </strong>User is able to create a new
questionnaire or edit the previous one</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event: </strong>Click on the questionnaire
form</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type : </strong>External </td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td>Admin page</td>
</tr>
<tr class="even">
<td></td>
<td>Questionnaire template</td>
</tr>
<tr class="odd">
<td></td>
<td>Questionnaire form</td>
</tr>
<tr class="even">
<td></td>
<td> Admin page</td>
</tr>
<tr class="odd">
<td><strong>Alternative Scenario</strong></td>
<td></td>
</tr>
<tr class="even">
<td></td>
<td></td>
</tr>
<tr class="odd">
<td><p><strong>Preconditions : </strong></p></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Postconditions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Success Guarantee :</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Minimum Guarantee :</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Requirements Met: </strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Outstanding Issues : </strong></td>
<td></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><p><strong>Use Case Name :</strong></p>
<p><span id="anchor-46"></span>View Volunteer Profile</p></td>
<td><strong>UniqueID: UM01</strong></td>
</tr>
<tr class="even">
<td><strong>Area:</strong> Volunteer profile page</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Actors(s): </strong>Volunteer</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Stakeholder : </strong>Supervisor, Client,Admin</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Description : </strong>Users can view their own profile
details and edit</td>
<td></td>
</tr>
<tr class="even">
<td><strong>Triggering Event: </strong>Click on Profile button</td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Trigger Type : </strong>External </td>
<td></td>
</tr>
<tr class="even">
<td><strong>Steps Performed (Main Path)</strong></td>
<td><strong>Information for steps</strong></td>
</tr>
<tr class="odd">
<td></td>
<td>Profile page</td>
</tr>
<tr class="even">
<td></td>
<td>User data </td>
</tr>
<tr class="odd">
<td></td>
<td>Profile page</td>
</tr>
<tr class="even">
<td></td>
<td>Questionnaire form</td>
</tr>
<tr class="odd">
<td></td>
<td>Request</td>
</tr>
<tr class="even">
<td></td>
<td>Profile form</td>
</tr>
<tr class="odd">
<td></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Alternative Scenario</strong></td>
<td></td>
</tr>
<tr class="odd">
<td></td>
<td></td>
</tr>
<tr class="even">
<td><p><strong>Preconditions : </strong></p></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Postconditions:</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Assumptions:</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Success Guarantee :</strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Minimum Guarantee :</strong></td>
<td></td>
</tr>
<tr class="odd">
<td><strong>Requirements Met: </strong></td>
<td></td>
</tr>
<tr class="even">
<td><strong>Outstanding Issues : </strong></td>
<td></td>
</tr>
</tbody>
</table>

<span id="anchor-47"></span>**13. Functional Requirements**

<span id="anchor-48"></span>*** User Initiation System***

1.  Client inputs personal information, completes a questionnaire to be
    a registered member.
2.  Login with email and password.
3.  Clients can request for volunteer
4.  Interested people can apply for volunteer positions by uploading the
    required documents and signing up.
5.  The chosen volunteer will be sent an email regarding the
    confirmation of their selection.
6.  Selected volunteers will have to activate their account (which will
    be created by the administrator) using email
7.  Volunteers can be able to accept/reject requests of clients.

<span id="anchor-49"></span>***Notification System***

1.  System sends notification/request to the best fit Volunteer.
2.  Clients get notified about the selection of new volunteer after
    request
3.  Volunteers and clients receive notification of unread chat messages
    while they are away.
4.  System sends notification to both volunteers and clients of their
    scheduled session ahead of time.
5.  Supervisor receives notification for any AI flagged chats
6.  System notifies the supervisor of a new reported chat made by a
    client or volunteer.
7.  Admin receives notification of a new submitted request for leave
    application made by employees
8.  Volunteers receive notification of the decision to leave.

<span id="anchor-50"></span>***Chat System***

1.  Exchange texts and images in chat. Volunteers and clients are kept
    anonymous to each other.
2.  Set chat schedules..
3.  AI censors images and links deemed inappropriate, logs censorship
    events.
4.  Give permission to unblur censored images/links by the chat
    moderator AI.

<span id="anchor-51"></span>*** Report Handling System***

1.  Manually report inappropriate behaviour in chat.
2.  AI automatically reports chat if the threshold number of
    inappropriate images sent.
3.  View manual and AI-generated reports of inappropriate behaviour.
4.  View chat logs and questionnaire responses of reported chats.
5.  View logs of censorship events, along with censored images. Report
    false positives.
6.  Send a message to reporting and reported users to explain how the
    report has been dealt with.
7.  Ban a user for an amount of time following inappropriate behaviour.
8.  Reassign a volunteer in a chat.

<span id="anchor-52"></span>***Questionnaire System***

1.  Create a new questionnaire.
2.  Edit previous questionnaire.
3.  Can view questionnaire responses.
4.  Users can insert responses to the questionnaires.
5.  Both responses and questionnaires can be stored.
6.  Create a new newsletter and publish.
7.  Users can edit questionnaire responses.

<span id="anchor-53"></span>***User Management System***

1.  View Volunteer-Client Statistics.
2.  Users can view and edit profile information.
3.  Clients can delete their account.
4.  Supervisors can ban or remove volunteer accounts.
5.  Admin can view system statistics.
6.  Volunteers can view their statistics.
7.  Volunteers can apply for leave applications.
8.  Supervisors can approve/reject leave applications.

<span id="anchor-54"></span>**14. Non-Functional Requirements**

-   <span id="anchor-55"></span>***Privacy***

    -   Identifying information of clients should only be visible to
        > authorised personnel of the organisation and only under
        > special circumstances.

    -   Volunteers and clients should be anonymous to one another.

    -   Screenshot-prevention feature in chat window.

    -   Chat logs accessible to supervisors only in case of reports.

-   <span id="anchor-56"></span>***Security:***

    -   End to end encryption of chats.

    -   Encrypted storage of all user data in servers.

    -   Store only the bare minimum user data in servers.

-   <span id="anchor-57"></span>***Cost:***

    -   Compress all images on the user end to minimise server
        > bandwidth/storage requirements.

    -   Should not contain proprietary components that may incur
        > expensive licensing fees.

    -   Back-end must run on a cloud server provider’s budget-tier plan.

-   <span id="anchor-58"></span>***Usability:***

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

-   <span id="anchor-59"></span>***Misc.***

    -   Must be fully open source for the sake of transparency.

    -   Must be easily auditable to ensure confidentiality of user data
        > is being maintained.

    -   Apps must respect user privacy - no ads, no data gathering or
        > unnecessary device permissions.

    -   Maintainable by a small team.

    -   Not dependent on third party developer’s components, as
        > long-term support may not be guaranteed with those.

<span id="anchor-60"></span>***Section 4:***

<span id="anchor-61"></span>**15. Entity Relationship Diagram**

<img src="./Pictures/1000020100000800000005F64F5479FEB78798C0.png"
style="width:9.4429in;height:7.0417in" />

<span id="anchor-62"></span>**16. Logical Data Flow diagram**

<span id="anchor-63"></span>***Diagram 0***

<img src="./Pictures/1000020100000800000005788D3C85A334F2DBE9.png"
style="width:9.4429in;height:6.4583in" />

<span id="anchor-64"></span>***User Initiation System***

<span id="anchor-65"></span>**Logical Dataflow: Existing**

<img src="./Pictures/100000000000044C000002D0482491E0D81EDB92.png"
style="width:7.7965in;height:5.0984in" />

<span id="anchor-66"></span>

<span id="anchor-67"></span>**Logical Dataflow: Proposed**

<img src="./Pictures/1000000000000665000004A82946125833D98E06.png"
style="width:8.0465in;height:5.8555in" />

<span id="anchor-68"></span>***Notification System***

<span id="anchor-69"></span>**Logical Dataflow: Proposed**

<img src="./Pictures/100000000000067D000003FC4AAD2E4C4FB9D38D.png"
style="width:9.4429in;height:5.8055in" />

<span id="anchor-70"></span>***Chat System***

<span id="anchor-71"></span>**Logical Dataflow: Existing**

<img src="./Pictures/1000020100000800000004D3457A56E1A6A86176.png"
style="width:8.3453in;height:5.0047in" />

<span id="anchor-72"></span>**Logical Dataflow: Proposed**

<img src="./Pictures/1000020100000800000005CF8FACF1AFABBEE7FC.png"
style="width:9.4429in;height:6.861in" />

<span id="anchor-73"></span>***Report System***

<span id="anchor-74"></span>**Logical Dataflow: Existing**

<img src="./Pictures/1000020100000800000004BD7524BDF262398E35.png"
style="width:7.4839in;height:4.4217in" />

<span id="anchor-75"></span>**Logical Dataflow: Proposed**

<img src="./Pictures/10000201000008000000068E80CDFD595163144E.png"
style="width:9.4429in;height:7.7362in" />

<span id="anchor-76"></span>***Questionnaire System***

<span id="anchor-77"></span>**Logical Dataflow: Existing**

<img src="./Pictures/1000000000000334000002E4E00179B9228268A7.png"
style="width:7.4744in;height:6.7453in" />

<span id="anchor-78"></span>**Logical Dataflow: Proposed**

<img src="./Pictures/1000000000000382000002E4DABE0785B226619E.png"
style="width:7.328in;height:6.039in" />

<span id="anchor-79"></span>***User Management System***

<span id="anchor-80"></span>**Logical Dataflow: Proposed**

<span
id="anchor-81"></span><img src="./Pictures/1000000000000410000003200B82F164CAC196AE.png"
style="width:7.7472in;height:5.9555in" />

<span id="anchor-82"></span>**17. Physical Data Flow diagram**

<span id="anchor-83"></span>***User Initiation System***

<img src="./Pictures/100002010000074E0000052A8DEA7D2E43FDEB24.png"
style="width:8.9346in;height:4.9898in" />

<span id="anchor-84"></span>

<span id="anchor-85"></span>***Notification System***

<img src="./Pictures/1000000000000521000003D48488A3BED436FD38.png"
style="width:8.272in;height:6.1638in" />

<span id="anchor-86"></span>***Chat System***

<img src="./Pictures/1000020100000800000005AEE06831094E070E8F.png"
style="width:8.2634in;height:5.8681in" />

<span id="anchor-87"></span>

<span id="anchor-88"></span>***Report System***

<img src="./Pictures/1000020100000800000006B7E2FE8009C20FAE73.png"
style="width:8.4319in;height:7.0752in" />

<span id="anchor-89"></span>**18. Activity diagrams**

<span id="anchor-90"></span>***Activity: User Initiation System ***

<img src="./Pictures/10000201000005DC000004F4418B13FCEDA932DB.png"
style="width:8.6516in;height:7.3161in" />

<span id="anchor-91"></span>***Activity: Volunteer signup System***

<img src="./Pictures/100000000000048800000500F873E05F67D76F54.png"
style="width:8.8181in;height:9.7217in" />

<span id="anchor-92"></span>***Activity: Report Notification System***

<img src="./Pictures/10000000000005AA000003E8667ACCD0089AB375.png"
style="width:8.8311in;height:6.089in" />

<span id="anchor-93"></span>***Activity: Chat Notification System***

<img src="./Pictures/1000000000000578000005B4F149EFD6662E1359.png"
style="width:8.8937in;height:9.2661in" />

<span id="anchor-94"></span>***Activity: Chat System***

<img src="./Pictures/1000020100000800000005BEED84A975BFB9A34E.png"
style="width:9.3181in;height:6.6783in" />

<span id="anchor-95"></span>***Activity: Report System***

<img src="./Pictures/100002010000080000000635398322016081A00F.png"
style="width:9.672in;height:7.4898in" />

<span id="anchor-96"></span>***Activity: Questionnaire System***

<img src="./Pictures/10000000000005C8000005A0B6A4B9DF548EC1A7.png"
style="width:9.4429in;height:9.1945in" />

> <span id="anchor-97"></span>**19. Sequence diagrams**

<span id="anchor-98"></span>***User Initiation System***

<span id="anchor-99"></span>***User sign up***

<span
id="anchor-100"></span><img src="./Pictures/10000000000007760000033ED04032499FC69F56.png"
style="width:8.8154in;height:3.8201in" />

<span id="anchor-101"></span>

<span id="anchor-102"></span>***Notification System***

<span id="anchor-103"></span>***Reported Notification***

<img src="./Pictures/10000000000005FC000003344232CA56219A285D.png"
style="width:8.7161in;height:4.5417in" />

<span id="anchor-104"></span>***Chat System***

<span id="anchor-105"></span>**Have Conversations**

<span
id="anchor-106"></span><img src="./Pictures/1000020100000800000003FF0B4308E181E39F80.png"
style="width:9.4429in;height:4.722in" />

<span id="anchor-107"></span>  
*Report System*

<span id="anchor-108"></span>** View Reported Conversation**

<img src="./Pictures/1000020100000800000004658B37E81F5CF41067.png"
style="width:9.4429in;height:5.1807in" />

<span id="anchor-109"></span>*Questionnaire System*

<span id="anchor-110"></span>**Edit Questionnaire**

<img src="./Pictures/1000000000000348000003C05956205A5BE27970.png"
style="width:6.7909in;height:7.7374in" />

<span id="anchor-111"></span>**20. Communication diagrams**

<span id="anchor-112"></span>***User Initiation System***

<span id="anchor-113"></span>**User sign up**

<img src="./Pictures/10000000000005B4000000C8B1E61D829FA27D6C.png"
style="width:9.448in;height:1.8165in" />

<span id="anchor-114"></span>***Notification System***

<span id="anchor-115"></span>**Reported Notification**

<img src="./Pictures/10000000000003C0000001CA674451CBF968E380.png"
style="width:7.539in;height:3.5902in" />

<span id="anchor-116"></span>***Chat System***

<span id="anchor-117"></span>**Have
Conversations**<img src="./Pictures/1000020100000800000003782AA689D01C19C058.png"
style="width:9.4429in;height:4.0972in" />

<span id="anchor-118"></span>

<span id="anchor-119"></span>***Report System***

<span id="anchor-120"></span>**View Reported
Conversation**<img src="./Pictures/1000000000000690000003C24EB7F8A2827B629B.png"
style="width:8.2953in;height:4.7563in" />

<span id="anchor-121"></span>***Questionnaire System***

<span id="anchor-122"></span>**Make questionnaire**

<img src="./Pictures/10000000000003C900000185343A0D6E573B5BA2.png"
style="width:7.8728in;height:3.1634in" />

<span id="anchor-123"></span>**21. Class diagrams**

<img src="./Pictures/100002010000075300000800FFD60B942AF9855D.png"
style="width:9.4429in;height:10.3055in" />

<span id="anchor-124"></span>**22. State-chart diagrams.**

<span id="anchor-125"></span>***Client class***

<img src="./Pictures/10000000000003D80000025EFC4760DE1524EC90.png"
style="width:6.5in;height:4in" />

<span id="anchor-126"></span>***Volunteer class***

<img src="./Pictures/1000000000000325000003FCBA058CA26CC6B8B9.png"
style="width:6.5in;height:7.4764in" />

<span id="anchor-127"></span>***Chat class***

<img src="./Pictures/1000020100000800000005533F5AEF3FA9BEAEC9.png"
style="width:7.3957in;height:4.9165in" />

<span id="anchor-128"></span>

<span id="anchor-129"></span>***Report class***

<img src="./Pictures/1000000000000637000005A4D76D8D494FAB360A.png"
style="width:6.778in;height:6.1453in" />

<span id="anchor-130"></span>***Leave Application class***

<img src="./Pictures/1000000000000598000002584D3AB0EE7E6CED20.png"
style="width:7.7992in;height:3.2665in" />

<span id="anchor-131"></span>***Questionnaire class***

<img src="./Pictures/1000000000000495000001D07091886F47EC577B.png"
style="width:7.9866in;height:3.1472in" />

<span id="anchor-132"></span>**23. CRUD matrix**

<span id="anchor-133"></span>***User Initiation System***

|                                     |            |               |           |                |                       |
|-------------------------------------|------------|---------------|-----------|----------------|-----------------------|
| **Activity**                        | **Client** | **Volunteer** | **Admin** | **Supervisor** | **AI Chat Moderator** |
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

<span id="anchor-134"></span>

<span id="anchor-135"></span>***Chat System***

|                               |           |                 |             |                |
|-------------------------------|-----------|-----------------|-------------|----------------|
| **Activity**                  | **Chats** | **UserRecords** | **Reports** | **CensorLogs** |
| Report Conversation           | R         | R               | C           | R              |
| View Report Details           |           |                 | R           | R              |
| Write Report-Handling Message |           |                 | RU          |                |
| Request Chat-log Access       | U         | R               | RU          |                |
| Grant Chat-log Access         | U         |                 | RU          |                |
| View Chat-log                 | R         |                 |             |                |
| Ban/Reassign                  |           | RU              | RU          |                |

<span id="anchor-136"></span>

<span id="anchor-137"></span>

<span id="anchor-138"></span>

<span id="anchor-139"></span>***Report System***

|                |           |                |                   |
|----------------|-----------|----------------|-------------------|
| **Activity**   | **Chats** | **CensorLogs** | **Notifications** |
| Send Message   | CRU       |                |                   |
| Load Messages  | R         |                |                   |
| Censor Message | R         | CR             |                   |
| Schedule Chat  |           |                | C                 |
| Unblur Message | U         |                |                   |

<span id="anchor-140"></span>***Questionnaire System***

|                              |                   |
|------------------------------|-------------------|
| **Activity**                 | **Questionnaire** |
| Create questionnaire         | C                 |
| View questionnaire           | R                 |
| Edit questionnaire responses | RU                |
| Edit questionnaire           | U                 |
| Publish questionnaire        | CU                |

<span id="anchor-141"></span>***Section 5:***

<span id="anchor-142"></span>**24. Structure English pseudo code for the
system**

<span id="anchor-143"></span>***User Initiation System***

<img src="./Pictures/100002010000043A00000800579880AF0FAD031F.png"
style="width:6.2429in;height:11.8102in" />

<span id="anchor-144"></span>***Notification System***

<img src="./Pictures/10000201000004B20000054C997CFB67F804319D.png"
style="width:7.4736in;height:8.4311in" />

<span id="anchor-145"></span>***Having Conversations***

<img src="./Pictures/10000000000005C0000005D4C0EC712BE231A2FB.png"
style="width:8.3in;height:8.4043in" />

<span id="anchor-146"></span>***Handle Reports***

<img src="./Pictures/1000000000000514000006E2F19F0C596C94DF09.png"
style="width:8.4547in;height:11.4571in" />

<span id="anchor-147"></span>***User Management***

<img src="./Pictures/10000201000006B300000800006877C1A48E0078.png"
style="width:9.4429in;height:11.278in" />

<span id="anchor-148"></span>***Questionnaire Management***

<img src="./Pictures/10000000000005A200000800881BA9D2AEDEDA2D.png"
style="width:9.4429in;height:13.4165in" />

<span id="anchor-149"></span>**25. Prototype the user interface**

<span id="anchor-150"></span>***User Signup***

<img src="./Pictures/1000020100000780000004382CF899E7C81F6724.png"
style="width:7.6957in;height:4.3181in" />

<span id="anchor-151"></span>***Volunteer Application***

<img src="./Pictures/100002010000078000000438D6393B3C2AAD9830.png"
style="width:7.8063in;height:4.3728in" />

<span id="anchor-152"></span>***User Login***

<img src="./Pictures/100002010000078000000438D1AC315BCC133B42.png"
style="width:8.0236in;height:4.4965in" />

<span id="anchor-153"></span>***Chat ***

<img src="./Pictures/100002010000078000000438636093F0623BA4F4.png"
style="width:8.2453in;height:4.6272in" />

<span id="anchor-154"></span>***Chat Client List (visible to volunteers
only)***

<img src="./Pictures/100002010000078000000438863B08E78D796D4D.png"
style="width:8.1429in;height:4.5661in" />

<span id="anchor-155"></span>***Chat Schedule***

<img src="./Pictures/100002010000078000000438A3C7409158CAF900.png"
style="width:8.089in;height:4.5398in" />

<span id="anchor-156"></span>***Chat Questionnaire***

<img src="./Pictures/10000201000007800000043856095A682539268E.png"
style="width:7.9425in;height:4.4516in" />

<span id="anchor-157"></span>

<span id="anchor-158"></span>***Add Custom Questionnaire (visible to
volunteers only)***

<img src="./Pictures/100002010000078000000438966ED8B3A00F4608.png"
style="width:7.8457in;height:4.4071in" />

<span id="anchor-159"></span>***Chat Notification***

<img src="./Pictures/1000020100000780000004383944EF029EB892D0.png"
style="width:7.7508in;height:4.3465in" />

<span id="anchor-160"></span>

<span id="anchor-161"></span>***Report Chat***

<img src="./Pictures/100002010000078000000438ADB90B267760E2EE.png"
style="width:7.7756in;height:4.3646in" />

<span id="anchor-162"></span>

<span id="anchor-163"></span>***Report Management***

<img src="./Pictures/100002010000078000000438A2FA3F7C48D52200.png"
style="width:7.411in;height:4.1535in" />

<span id="anchor-164"></span>***AI-flagged Report Details***

<img src="./Pictures/1000020100000780000004387EE2829CFB1E38CB.png"
style="width:7.5319in;height:4.2201in" />

<span id="anchor-165"></span>

<span id="anchor-166"></span>***Manually-flagged Report Details***

<img src="./Pictures/1000020100000780000004380CA6AF9654CEE1D2.png"
style="width:7.6819in;height:4.3138in" />

<span id="anchor-167"></span>

<span id="anchor-168"></span>***Report-handling wizard***

<img src="./Pictures/100002010000078000000438A5E9343B80AF2631.png"
style="width:7.7457in;height:4.3492in" />

<span id="anchor-169"></span>***Leave Application List***

<img src="./Pictures/1000020100000780000004385817624B7CF4AF24.png"
style="width:7.0575in;height:3.9602in" />

<span id="anchor-170"></span>***Leave Application Details***

<img src="./Pictures/100002010000078000000438C73DEBDD4AF3C8E4.png"
style="width:7.372in;height:4.1327in" />

<span id="anchor-171"></span>***Admin Add Questionnaire***

<img src="./Pictures/1000020100000780000004387F3E9B8B3B6FB29D.png"
style="width:7.3201in;height:4.111in" />
