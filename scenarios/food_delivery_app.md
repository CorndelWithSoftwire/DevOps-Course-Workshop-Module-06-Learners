# Food Delivery App

## Brief
You work for Widget Corp. Widget Corp has a mobile app for delivering food to houses from restaurants and take-aways. Customers can search for restaurants, place an order and then await delivery. The app is relatively popular, but competitors are gaining in popularity. The existing app was quickly hacked together to gain market share, and Widget Corp is ready to invest in a new version that fixes any pain points in the existing app, and is more stable for future expansion. You have been asked to propose an initial design for the next-generation version of their application.

## Research Report Summary
*The following is a summary of a report written by the research team at Widget Corp as a result of user research performed on the existing app.*

* We've looked at our reviews on the app store, and found a few common issues that customers have:
    * Customers would like more real-time feedback when they place an order. That currently puts a message in a queue, which eventually results in an email to users confirming or rejecting their order. 
    * Users would like the ability to quickly see their past orders and re-order the same thing from the same place. Often this is because they are busy city workers who only just about have enough time to get home and eat before they sleep.
    * Users would like to leave reviews for restaurants, and receive recommendations for other restaurants they might like. Often this is because they are passionate about food and interested in exploring new options
* In a series of lab tests, observing users trying the app for the first time, we found:
    * A user with allergies resorted to calling the restaurant to be confident that their order was safe, and would have liked to see allergens displayed on the menu ideally
    * A user expected an up to date status of their food order and the driver's location. Without it, they were worried about delays or the food getting cold.
    * A user was frustrated by the inability to search for restaurants that served specific dishes
* Telemetry suggests that we lose users when we do app deployments (which currently bring the infrastructure down for an hour). Most of these users come back, but some install a new app and stick with the new app.