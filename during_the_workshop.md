# Module 6 Workshop

## UX-Driven App Design
### Step 1 - Read your brief and user research report
Choose one of the following three scenarios:

1. [Brief & user research report for Holiday Booking Website](./scenarios/holiday_booking_portal.md)
2. [Brief & user research report for Food Delivery App](./scenarios/food_delivery_app.md)
3. [Brief & user research report for Inner-city Travel Advisor](./scenarios/inner-city_travel_advisor.md)

Your choice of app brief comes with a summary of a report written by the user research department. You should study this document and get a feel for the various needs, profiles, and difficulties faced by the user-base of the application.

Read this document, and discuss as a group any implications or considerations you may need to make. 

Decide on a tool for collaborating - you will need to record your findings, decisions, and thoughts. We suggest [Miro](https://miro.com) as previously used, but Google Docs, Google Slides, or other real-time collaboration tools are also acceptable.

### Step 2 - Create user personas for your application
User personas are based on research data about the real-world users of your application, but there is often reason to theorise about portions of your user-base whose needs are not represented by your research. This latter form of consideration makes up speculative design. Use the user research report for your application, and any speculative design from your team to inform the creation of user personas for your service.

You are aiming to capture all of the characteristics shown by your user-base. To do this consider creating about 3-5 user personas, but it depends on how detailed your persona creation approach is, how diverse the userbase is, and how much overlap there is between personas.

Your user personas should have:
* A name/group (e.g. back-office staff)
    * This should describe the characteristics that this persona represents, and be a useful name when discussed with members of the team.
* A (fictional) name
* A job title, or their responsibilities 
* Demographic information
    * In so far as is useful & relevant - you want to capture information about what might affect your user during operation of your app, and have enough information to bring the persona to life, but avoid lots of irrelevant information that can make you susceptible to bias.
* Their context/environment - factors that affect how they use or respond to the app (e.g. physical patterns or limitations, social context, technological comfort). This is a very wide net - it spans:
    * Do they use it in a work, home or public setting? Or while travelling with inconsistent mobile data?
    * Usability concerns (Does the user require a screenreader? Is the user proficient in English? Does the user only have access to a basic phone?)
* Social and psychological factors, such as:
    * Anxious and benefits from seeing real-time updates on their ticket
    * Attracted by an element of exclusivity
    * 
* Their goals in using the app, and their needs met in so doing

### Step 3 - Create user journeys
User journeys are descriptions of a user, the context affecting them, and the need of theirs that is met by your application (e.g. "*as an online shopper, who is a busy and multitasking stay-at-home mother, I want to make an online grocery shop with as little fuss as possible*"). A user journey should represent a fairly complex need for the user (i.e. it should include at least one decision point). 

Read through your user personas - let these users come to life for you, and consider the core value statements in each persona. Having considered these, write at least one user journey. For this exercise, focus on the user journey that best explores the nuances in your user-base. Summarise it, similarly to the example above.

User researchers will often map a user journey in a more detailed format that enables them to explore the users' thoughts, concerns, and pain points. Create a user journey map for your journey and a specific persona:

1. Create a timeline - break down the journey into key phases and list the possible "touchpoints" (interactions with the product)
1. In each phase, what are the user's motivations, expectations or feelings? What are the possible pain points?
1. Identify opportunities - are there any feature ideas that would address a pain point? 

If you have time, go through the process for different personas or journeys.

### Step 4 - Create user stories

User stories are lower-level versions of the above, whose assembled product may comprise enough functionality to fulfil a user journey (e.g. "*as an online shopper, when I've logged in to the website before, I want to be able to visit the site and immediately start shopping without having to log in again, so I don't need to deal with unnecessary friction during my tasks*". 

Once you have one user journey you are happy with (ideally one that explores the impact of different characteristics amongst your user-base), write out a few user stories to capture the functionality required by your users along this journey. Try to cover some of the key ideas that were inspired by the user research results, which hopefully led to opportunities in the user journey map.

User story writing tips:
* You want something specific enough that developers can take the story and build something (or break down into subtasks then build), but without deciding on implementation details
* You also want to capture the motivation for the task, i.e. what the user is getting out of this feature.
* Write acceptance criteria to add detail and cover edge cases. If all these criteria are met, everyone should agree the story has been completed.
  * Each criterion should be independently testable
  * You will typically have 1-3 criteria. If you have more than 5, consider dividing the user story into smaller ones.
  * Acceptance criteria still do not mention implementation details. They cover testable functionality.
  * Typically written as "Given ..., When ..., Then ...". For example: "Given that I logged in within the last two weeks and did not log out, when I visit the site from the same browser, then the requested page should load with me logged into my account"
  * Consider including expectations that something doesn't happen, e.g. "I should not be redirected...", or what should happen when something goes wrong. For example: "Given that I logged in recently but reset my password since then ..."
  * Acceptance criteria can include non-functional requirements (NFRs), e.g. required response times, if it is especially important or likely to be an issue.

Pick one of your user stories and write out Acceptance Criteria for it. This might include:

* Must haves, these can be used when testing the ticket to make sure it satisfies the requirements
* Should haves/nice to haves, these things might improve the user experience or make the feature easier to maintain, but are not required
* Relevant non-functional requirements, for example around security and performance

### Step 5 - Create user flow diagrams and wireframes

A user flow diagram is a flowchart that illustrates the user's path along their journey. This includes all interactions they'll need to make, actions they need to take, decisions they need to make, and any pain points encountered. You may discover as a result of creating a user flow diagram ways in which your service could be streamlined in order to provide the same service with less friction - if so, let that become part of your new design!

A wireframe is a low fidelity representation of your application's UI (drawn within a box that represents the window of a web browser, or the frame of a phone display).

Make a user flow diagram that illustrates the user journey you've chosen.
You should also build wireframes that illustrate screens and modals in your application, enough to cover all interactions and decision points that the user will experience on their journey. Feel free to use any built-in functionality from your whiteboarding tool, or use a dedicated wireframing tool like [Balsamiq](https://balsamiq.cloud/).

### Step 6 - Propose a technical architecture
At this point, you have a much clearer idea of the characteristics of your user-base, and of the application you are trying to build. Make a list of the technical constraints that will impose on your architectural decisions - for the purposes of this exercise, you may make useful assumptions (but please document them as you do so). 

Then, make a technical architecture proposal.
The output from this step can vary - if at this point your group has existing exposure to high-level architecture, please make a simple architecture diagram illustrating your proposal. If your group has less experience with high-level architecture, a brief description will also be fine. This proposal can be very (very!) simple, or it can involve a few more moving parts - either is fine, as long as your design choice is supported by your justifications.

Please document all the design considerations you included, assumptions you made, and other constraints. See the slides for more inspiration on architectural considerations, but at a minimum, you want to answer the following questions (and use the answers to inform your design):
* How are the users expected to operate your application? (e.g. website, mobile app, social network integrated chat bot, other)
* Is your expected load profile stable or spiky? Would you benefit from an architecture that permits horizontal scaling?
* What service uptime is required? How robust a layer, and how many layers of redundancy do you need?
* What kind of feedback does the user require? Do they require real-time feedback or would an email later from a batch processing system suffice?
* What components of your system need internet access, and which require only access to other components of your application?

### Step 7 - Prepare a short presentation
You will need to present your app design proposal to the "company stakeholders" (in actuality, you will present to the rest of your cohort). This presentation could take the form of some slides (if so, no more than 5), but could easily just be the members of your group talking through your Miro board (or other collaboration tool).

The objectives of your presentation are as follows:
* Inform the stakeholders of the kinds of users you are catering for, the goals they want to achieve, the pain points they might experience, and the ways in which you plan to meet their needs (as a result of the research given to you, and any speculative design work you have done).
* Describe the user journey you have narrowed in on, and how it captures the nuance of the different characteristics in your user-base. 
* Give a brief overview of the user stories whose implementation would result in the said user journey being realised, alongside any due considerations you made whilst writing these.
* Show off your user flow diagram and wireframes, noting any points where you have managed to make your service streamlined, or cater for user needs.
* Explain your technical architecture proposal: what constraints and usage profiles have you designed for, and how is your design justified by these?
