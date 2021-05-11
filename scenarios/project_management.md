# Collaboration App

## Brief
You work for Widget Corp. Widget Corp launched a task manager for personal use, but noticed a big uptake in usage after they enabled sharing of these task lists with other people, as well as developing a multiple-column view for these lists (such that each list has multiple named columns, and each task can be moved between columns). Growth has slowed, and Widget Corp wants to invest in a new version of the application that more closely targets the needs of the new user-base that has been signing up. You have been asked to propose an initial design for this next-generation version of their application.

## Research Report Summary
*The following is a summary of a report written by the research team at Widget Corp as a result of user research performed on the existing app.*

* We opened a feature request form, and many high-usage users expressed a desire for more granular access controls. Their requests, although different, had some common themes: they wanted access tiers with at least the following permission levels:
    * The below, plus managing user permisions.
    * Being able to move or edit tasks.
    * Being able to move tasks between columns.
    * Just being able to view the tasks.
* We invited some users to our lab to observe how they used our application, and found:
    * Many users were part of a shared list where tasks were prefixed with their initials (e.g. "JB: Fix widget"). Their workflow often began with filtering the list items by their initials ("JB") to see the list items they wanted. This worked well for some, and less well for others (who had initials that commonly came up in words, such as "TH" seeing all items with the word "the").
    * Users were often members of many lists, but mostly interested in one or two of them, which they'd have to scroll down the main page to find each time they wanted to access them.
* One of our account managers had a call with a client about how satisfied they were with the app - the call was with a senior stakeholder within the client organisation, and they expressed frustration at wanting to see a high-level overview of many projects at once (they wanted a view which summarised how many tasks were in which column, and showed multiple lists at once, rather than our typical view of a single list that shows each column inside the list, and each task for each column).
* We analysed an anonymised version of our database, and found that there are a lot of users who manage a set of lists that are shared with the exact same set of people. When the user adds a new person to one of these, they manually add them to every other list too. Conversely, when they remove a user from one, they also remove them from all others. Occasionally, there is an exception where a user is not removed from one or two boards for a while. This may explain some support requests we get from the managing user asking if \<removed user> has logged in and looked at \<list they still had access to after being removed from the others>.