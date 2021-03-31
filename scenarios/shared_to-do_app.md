# Shared To-Do App

## Brief
You work for Widget Corp. Widget Corp launched a to-do manager for personal use, but noticed a big uptake in usage after they enabled sharing of these to-do lists with other people, as well as developing a multiple-column view for these lists (such that each list has multiple named columns, and each to-do item can be moved between columns). Growth has slowed, and Widget Corp wants to invest in a new version of the application that more closely targets the needs of the new user-base that has been signing up. You have been asked to propose an initial design for this next-generation version of their application.

## Research Report Summary
*The following is a summary of a report written by the research team at Widget Corp as a result of user research performed on the existing app.*

* We opened a feature request form, and many high-usage users expressed a desire for shared to-do lists to have more granular access controls. Their requests, although different, had some common themes: they wanted access tiers with at least the following permission levels:
    * The below, and managing users who the list is shared with.
    * Being able to move or edit to-do items.
    * Being able to move to-do items between columns.
    * Just being able to see the to-do list.
* We invited some users to our lab to observe how they used our application, and found:
    * Many users were part of a shared list where to-do items were prefixed with their initials (e.g. "JB: Fix widget"). Their workflow often began with filtering the list items by their initials ("JB") to see the list items they wanted. This worked well for some, and less well for others (who had initials that commonly came up in words, such as "TH" seeing all items with the word "the").
    * Many users were part of a lot of lists, but were mostly only interested in one or two lists, which they'd have to scroll down the main page to find each time they wanted to see it.
* One of our account managers had a call with a client about how satisfied they were with the app - the call was with a senior stakeholder within the client organisation, and they expressed frustration at wanting to see a high-level overview of many projects at once (they wanted a view which summarised how many to-do items were in which column, and showed multiple lists at once, rather than our typical view of a single list that shows each column inside the list, and each to-do for each column).
* We analysed an anonymised version of our database, and found that there are a lot of users who manage a set of to-do lists that are shared with the exact same set of people. When the user adds a new person to one of these, they manually add them to every other list too. Conversely, when they remove a user from one, they also remove them from all others. Occasionally, there is an exception where a user is not removed from one or two boards for a while. This may explain some support requests we get from the managing user asking if \<removed user> has logged in and looked at \<list they still had access to after being removed from the others>.