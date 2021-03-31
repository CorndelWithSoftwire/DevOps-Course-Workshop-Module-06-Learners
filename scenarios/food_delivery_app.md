# Food Delivery App

## Brief
You work for Widget Corp. Widget Corp has a mobile app for delivering food to houses from restaurants and take-aways. This app is used by the restaurants, the delivery drivers, and the customers. The app is relatively popular, but competitors are gaining in popularity. The existing app was quickly hacked together to gain market share, and Widget Corp is ready to invest in a new version that fixes any pain points in the existing app, and is more stable for future expansion. You have been asked to propose an initial design for the next-generation version of their application.

## Research Report Summary
*The following is a summary of a report written by the research team at Widget Corp as a result of user research performed on the existing app.*

* We've looked at our reviews on the app store, and found a few common issues that customers have:
    * Placing a food order currently puts a message in a queue, which eventually results in an email to users confirming or rejecting their order. Customers would like more real-time feedback, and to be able to check the status of their order from the app at all times.
    * Users would like the ability to quickly see their past-orders and re-order the same thing from the same place. Often this is because they are busy city workers who only just about have enough time to get home and eat before they sleep.
     * Users would like to leave reviews for restaurants, and receive recommendations for other restaurants they might like. Often this is because they are passionate about food and interested in exploring new options.
* We've interviewed delivery drivers to ask about their thoughts on the app, and they've had a few common themes:
    * The app currently shows you a list of addresses - where to pick something up, then where to deliver it, etc. Each item in the list is a link that opens a separate map application to help guide you to the destination, but drivers would find it easier and more seamless if the app had an integrated map that continuously updated with the new jobs and locations.
    * Sometimes, there's a problem and drivers want to be able to send messages to the customers with updates or questions. However, we've asked our customers, and they don't want their phone number to be given to drivers even just to receive text messages. We've actually had similar feedback for restaurants wanting to send updates/queries (e.g. "run out of beef") in the same way. An inbuilt messaging system may be popular.
* Some restaurants want a website version of our application - their computers are hooked up to their kitchen PA system, which would help them hear the alert when a new order comes in - the kitchens are often too busy to manually check the screen often. 
* Telemetry suggests that we lose users when we do app deployments (which currently bring the infrastructure down for an hour). Most of these users come back, but some install a new app and stick with the new app.