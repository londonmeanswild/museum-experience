---
title: paper prototypes
show_comments: true 
---
## Overview
Here is an overview of our mobile application design for curators.
![all functionality](/museum-experience/images/prototyping/pp-all-flow.jpg)

### Opening Screen
Our application will start with an opening screen prompting them to log/sign in to their profiles. This can give us the ability to customize accounts if we want to implement that in the future.
![log in](/museum-experience/images/prototyping/pp-login.jpg)

### Task 1: Summarizing and Communicating Data
We have two ways users can access and visualize the feedback data. After logging in, the user will be taken to the home screen seen on the bottom right side of the picture. They then have a couple options from here: click the all feedback button, click the thought bubble icon, or click one of the exhibits listed on the bottom half of the screen. Let's first assume they click the all feedback button. They will then be taken to the top right screen. This will show all visitor feedback from most recent to least recent. The sort button allows the curators to organize it from least recent to most recent. Additionally, there is a "narrow" field that results in a drop down, allowing the user to specify the feedback they want to see. 
![all feedback](/museum-experience/images/prototyping/pp-feedback-flow.jpg)

The other way users can see feedback is through specific exhibits. Assume we're back on the home page and the user decides to click on exhibit A. They will be brought to the middle screen where they will see artwork that was most recently commented on in that exhibit, and data analytics (i.e. graphs and charts) giving them information about the exhibit as a whole. When they click on a piece of art, they will be brought to the top right screen, showing them the piece, recent feedback about the piece, and data/graphs specific to that piece. On the other hand, if the user clicked on the "see more" for the data analytics, they would be brought to the bottom right screen, showing them all of the data for the exhibit as a whole.
![exhibit functionality](/museum-experience/images/prototyping/pp-exhibit-flow.jpg)

### Task 1: Connecting Curators with Museum Visitors
Now assume we're back on the home screen. If the user clicks on the thought bubble, they will be brought to the middle-left screen, showing them short notation of questions and suggestions (i.e. if the question is too long then it will be cut off) and the exhibit it is referring to. By clicking on one of the reply buttons, the user will be taken to the middle-right screen, showing them a picture of the piece of exhibit, followed by the full question/suggestion, and the option to reply or ignore it. By clicking reply, the user then goes to the rightmost screen, opening a chat window that lets them send a message to the visitor who asked it. Aside: since we are creating a design for curators as our primary user, we are ignoring the implementation of the museum visitor aspects. Therefore, for now, we are not worrying about how this response gets into the hands of the visitor. 
![communication functionality](/museum-experience/images/prototyping/pp-comm-flow-keyboard.jpg)

