---
layout: post
title:  "IHS Mobile App"
date:   2018-04-18 15:39:40
preview: /img/ihs/icon.png

---


<br>
<p style="text-align: center;"><b>Client</b></p>

[The institute for Human Services](https://ihshawaii.org/) is a non-profit organization that aims to "create and offer tailored solutions for those in crisis, and nurture homeless people toward greater self-direction and responsibility." <br>

<br>

|    My Roles    | Duration |    Tool     |
| :------------: | :------: | :---------: |
| UI/UX Designer | 3 months |    Figma    |
|                |          |     Jira    |

<br>

**I: PROBLEM STATEMENT** <br>
The Institute for Human Services (IHS) is presently dedicated to aiding homeless individuals in Hawaii in securing housing, obtaining medical support, healthcare, and more, all with the aim of reducing the homelessness rate. However, the current method of manually managing and storing homeless information remains time-consuming and results in duplicated profile records.
<br><br>

**II: BUSINESS GOALS** <br>
The objective of this initiative is to streamline the management of clients for both field workers and administrators through automation, thereby saving time and enhancing the assistance provided to homeless individuals. The ultimate aim is to expedite the resolution of homelessness cases.

**TERMS USED** <br>
**Encounter**: Each time an IHS field worker meets a homeless person counts as one encounter
**Client**: Each homeless person is called a client
**User**: IHS Staff
**Flag(s)**: A variable in the system that signifies the type of assistance a client needs (ex. Employment assistance, transportation, assistance with SNAP...)

<br><br>
>**Success Metrics**:
>- The number of encounters captured per month
>- The number of clients serviced per month\
>- The number of field workers engaging with the app
>- The time spent generating each encounter cut down


**<u>Personas</u>**<br>
<img src="/img/when2meet/Carson.jpg" alt="When2meet1" title="Carson" height="400"/>
<br>
<img src="/img/when2meet/Eddie.jpg" alt="When2meet2" title="Eddie" height="400"/>
<br><br>

**III: USABILITY TESTING** <br>
>**Usability Tasks**: We conducted six usability tasks with each session lasting around 20 - 25 minutes on average. We recorded the participants while they were performing our usability tasks. For this, we thought up of five tasks that our participants would carry out. These five participants were recruited by each individual team member, each team member carried out a complete usability test.<br>

>**Cognitive Walkthrough**: By doing this, we figured out different usability issues which may make it difficult for the user to use When2Meet.<br>

**Findings**:<br><br>
**Issue 1**: Changing the calendar/month from the default dates given by the system
Ex: Changing the below dates to display weeks in October of 2019 would be difficult to find out how due to the lack of scroll bar<br>
<img src="/img/when2meet/Issue1.JPG" alt="Issue" height="191"/><br>
4/5 users that we tested all had trouble figuring out how to scroll to their desired date. 3 of our users tried using the scroll wheel   while hovering over the calendar at first, while the other person tried to click and drag down. <br><br>
**Issue 2**: The instructions to select availability is not immediately noticeable
The instructions here are circled in blue. The font is small and too late for it to be displaying important information about how to     interact with the system.<br>
<img src="/img/when2meet/Issue2.JPG" alt="Issue" height="457"/> <br>
**Issue 3**: The "Event" name box is not clearly something that is required to be edited. 4 of our 5 users found it unclear that it was something to be touched.<br>
<img src="/img/when2meet/Issue3.JPG" alt="Issue" height="82"/> <br>
**Issue 4**: Clearing/filling the availability boxes by clicking and dragging is difficult due to the large room for error that is given by such small boxes representing segments of time. Clicking in the wrong box means that it incorrectly displays the user’s desired availability.<br><br>
<img src="/img/when2meet/Issue4.JPG" alt="Issue" height="400"/> <br><br>
**Issue 5**: The interface is overwhelming for new users.<br>
Specifically, in creating a new event, users are given all the requirements to do so in one screen rather than being given a step by step process. All the information and necessary boxes needed to fill in can be too much for a new user to try and figure out what they need to do with all of the options.<br>
<img src="/img/when2meet/Issue5.JPG" alt="Issue" height="296"/> <br><br>
**Issue 6**: The interface is overwhelming for new users.<br>
Signing in with an incorrect username will simply create a new user. This is a mistake which is very easy to make, and When2Meet doesn’t provide any mechanism that can prevent this. <br><br>
**Issue 7**: There is no way to go back to the sign in page if you have already signed into an account. There is no way to redo/undo this action through the interface. You must revisit the event link in order to do so.<br><br>
**Issue 8**: Cannot change the title, dates, or time range of an already created event.<br>
Only the availability and time zone can be changed. No other options of customization are given, even if they are the creator of the event.<br>
<img src="/img/when2meet/Issue8.JPG" alt="Issue" height="350"/> <br><br>
**PHASE IV: REDESIGN** <br>
After reviewing the data we got, these are the targets that we decided to redesign:	<br><br>
**Homepage**: Many participants in our usability test found that the homepage is overwhelming and confusing (especially for new users). Too much information on the same page makes it difficult for them to figure out where to start and what they need to do. <br>

**Event Creation Process**: This one is related to the homepage. All the steps combined in the homepage make the users confused as we indicated above. Also, when choosing the dates, the lack of scroll bar makes it difficult to change the month/year (4/5 users in our usability test had trouble with this task). <br>

**Availability Indication**: Through cognitive walkthrough and usability testing, we realize that the instructions regarding how to select availability are not noticeable enough. The font is small and blends in the background which makes it really hard to see. The option of entering both username and password is confusing too. <br>

**Sharing Process**: During usability testing, we found that the email option is not visible enough, and it took users awhile find it. The share-through-Facebook option doesn’t work at all. For the sharing link, we will have to manually use the mouse and drag to copy it, which is not efficient.<br><br>

**Wireframes:**
<img src="/img/when2meet/wireframe1.JPG" alt="Issue" height="503"/> 
<img src="/img/when2meet/wireframe2.JPG" alt="Issue" height="501"/>
<img src="/img/when2meet/wireframe3.JPG" alt="Issue" height="302"/>
<br><br>

**Final design:**<br>
<img src="/img/when2meet/when2meet homepage.jpg" alt="Issue" height="400"/> 
<img src="/img/when2meet/when2meet 2.jpg" alt="Issue" height="400"/> 
<img src="/img/when2meet/when2meet 3.jpg" alt="Issue" height="400"/> 
<img src="/img/when2meet/when2meet 4.jpg" alt="Issue" height="400"/> 
<img src="/img/when2meet/when2meet 5.jpg" alt="Issue" height="400"/> 
<img src="/img/when2meet/when2meet 6.jpg" alt="Issue" height="400"/> 
