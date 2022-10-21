# CS-360---Mobile-App-Architecture
Apply mobile development principles and best practices to develop mobile applications using user-centered design principles and industry standards


Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
The app is a weight tracking application that tracks the user's current weight via a SQL database that records the date and weight of the entry. The app also records the user's goal weight they would like to achieve. The app also will send SMS notifications to the user when the goal weight is achieved.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
The initial screen of the app allows the user to select whether they are a new user or existing user based on if they have set up an account or need to create a new one. After this screen, it will take the user to a sign in / create account screen. If the user's credentials are not found the database, a toast notification will output a message stating "account Created". If the user is in the database, the toast message output "Sign in successful". After the user logs in, the app redirects to the main screen where the user can log their goal weight. The navigation buttons at the bottom of the screen allwos the user to choose to go to the weight log history, or settings screens. The weight log history screen is the location where the user will log their daily weight along with the date of the log. When submitted, the weight logged and date will output to a listView. The logged weights can be deleted by a long press on the selected weight. From the main screen again, the user can select the settings screen. This screen prompts the user if they would like to initialize text notifications.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
How did you test to ensure your code was functional? Why is this process important and what did it reveal?
When approaching the development of the app, I used a common iteration approach. I broke each screen down into sprints. I would then work on each sprint, starting with the screation of the first screen. After this, I created the database, due to each screen therafter using the database created in some form or fashion. Afther this, each screen was created an tested individually before applying each portion together. This approach is similar to an Agile methodology and can be applied to each project in the future if it applies. 

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
Being new to app development an design, the entire process was a creative experience. After my intial proposal, the app then was adjusted on screens to fit the needs and skillset I was bringing to the app. Simplification of screens was necessary to meet the requirements of the app. This simplification actually created a more visually appealing app that functioned as it was originally intended to. 

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The design component of the app of placement of buttons and other features within the app was the area I excelled best. By using previous knowledge from other courses, I was able to implement a UI design that was visually appealing and provided a positive user experience when using the app. 
