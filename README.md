Ballot Box
=======
 
What you'll see
-----------
This project implements a quiz screen, allowing users select a response to a given question
 
 
How to Run
-----------
 
In order to properly run this project you must first install Expo, a tool built around React Native allowing for quick starts
on React Native Projects. Documentation can be found here:
 
https://reactnative.dev/docs/environment-setup
 
In order to install simply run:
>npm install -g expo-cli
 
Following installation simply run the following code in the correct directory:
 
>yarn start
 
This will create a QR code that is usable with your phone. If you can't get it to run, you can also visit the following link to
obtain a valid QR code.
 
>https://expo.dev/@oman32/parthean_page
 
 
 
Submission Questions
-----------
 
1. If I could restart the challenge I would increase the application's versatility. I would focus on creating a card
component that would be used for the possible answer to a question. Creating this component would have saved any redundant code
because I would simply be able to pass the tags in as props. Another thing I would have focused on was allowing the card to be
used for multiple quizzes. As it sits now it is statically typed, but I believe the current code can be easily edited to implement iteration over a collection of questions and answers.
 
2. If I had another hour I would focus on grabbing the response of the user. The current code is able to identify which
option was selected with a function but ideally I would be able to grab the actual text of a response and verify its
correctness. This would start leaning more towards the back end of the application, but it's something I would have enjoyed
doing. If I had another week I would focus on building out the application more. I would first add some form of data storage,
possibly a NoSQL database to allow for increased flexibility. After that I would add features such as a notification whether a
user answered correctly, an option to store a question they thought was interesting or important, a feature that allows them to
skip/return to a question and a way to track how many questions are left in the quiz. Once I hit the month mark I would look to
build out the entire application, from home screen to features independent of quizzes. I would also look into using some form on
containers to maintain consistency across operating systems and look into deployment.
 
3. I would first approach the issue by identifying the urgency, importance, and time each task would take. I would place the
following on top priority:
 
   - Learning how to use the Plaid API so that you can tell the team how long it'll take for you to actually integrate it and what the constraints might be
   - Building a staging setup so that things don't go straight to prod
   - Access control for videos that users watch on the product so that the public links aren't used by others
 
When it comes to matters of communication and collaboration it's important to give your team members an estimation of a
feature being implemented. The fact that it is the Plaid API is used to integrate user data into the app that allows for
customization makes it an important and urgent aspect of the application that the whole team should know when it has been
integrated successfully. Once this is done, creating a staging setup is important in order to prevent any accidental bugs and
glitches affecting the product users expect to be reliable. Thus it would minimize customer loss. Lastly the authorization of
videos that only allow users to watch the product is important to assure fairness. If a issue were occur where users
realized there was public access to links while they were required to pay for the service, that would cause many customers to
leave and use this free resource.
 
In the next level of prioritization I would mark the following on my to do list:
 
   - Arman, CEO, reminds you that the videos aren't loading fast enough, and you know the reason is because you're just pulling the entire .mp4 file directly from Firebase
   - Commenting feature on polls hasn't been done (all comments have been hard coded) and 2 users have pointed that to you
   - Multiple early testers have reported that the app takes SO LONG to load
 
This is because these are features that are currently affecting the entire Parthean community. Users having the greatest
experience is expected, thus correcting issues that are already implemented and not meeting clients and Parthean's standards is
important. I believe some issues in this portion would not take too long to correct so I would also attempt to fix these problems
when working on the issue on the first level of importance.
 
The next level of importance would include the following:
 
   - Leaderboard feature to increase engagement with the app
   - Notification feature to remind people to complete their unfinished learnings
   - Sign In with Google feature, which you tried integrating a month ago but gave up on when you faced some bugs
   - More user interviews to understand behavior
 
These are features that are important and would increase user experience and the quality of the product, but they have
not been implemented yet. I would argue that focusing on the issues the product currently has (depending on severity) takes
precedence over creating new features. In addition, the fact that users are using the product as it stands while not having these
features lends itself to prove that these features are important but not quite as urgent.
 
The final level of importance would be the following:
 
   - An Android user reported that some videos are not being marked as "complete" for them despite doing it, but you were unable to replicate it on your test Android device
   - You want to migrate away from Firebase to another database storage engine
 
These are issues that are not urgent and not important. In regards migrating from Firebase to another storage engine that
depends on the team. Just because I personally want to do it does not make it any more important. If there was a good reason to
switch (such as efficiency or cost savings) and the entire team had a desire to change databases before the organization
grows, this would be rated higher. Lastly, the issue that is only affecting one user and is not replicable is important but
does not take precedence over the experience everyone who uses the platform has.

4. I would say this assignment took 2 and a half to 3 hours to complete. The most time consuming portion was relearning React
Native. I had experience creating an application a few years ago so I remembered a few things. However I realized how much I had
forgotten so learning how to format screens and create elements and components took more time than I had expected.

