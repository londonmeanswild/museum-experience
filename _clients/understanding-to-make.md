---
name: heART
subtitle: understanding to make
image_path: /images/clients/blank.png
---

## understanding to make

### initial paper prototype
Our initial paper prototype writeup can be found [here](https://londonmeanswild.github.io/museum-experience/2018/10/28/paper-prototypes/). 
**need critical aspects still**

#### pictures
Here is the overview of our first paper prototype. We are designing a mobile application for curators. We included a log-in screen because it is a step that helped to orient testers who were not also classmates. 
![all functionality](/museum-experience/images/prototyping/pp-all-flow.jpg){:height="30%" width="30%"}
![log in](/museum-experience/images/prototyping/pp-login.jpg){:height="30%" width="30%"}

##### original task one: summarizing and communicating data
We have two ways users can access and visualize the feedback data. After logging in, the user will be taken to the home screen seen on the bottom right side of the picture. They then have a couple options from here: click the all feedback button, click the thought bubble icon, or click one of the exhibits listed on the bottom half of the screen. Let's first assume they click the all feedback button. They will then be taken to the top right screen. This will show all visitor feedback from most recent to least recent. The sort button allows the curators to organize it from least recent to most recent. Additionally, there is a "narrow" field that results in a drop down, allowing the user to specify the feedback they want to see. 
![all feedback](/museum-experience/images/prototyping/pp-feedback-flow.jpg){:height="30%" width="30%"}

The other way users can see feedback is through specific exhibits. Assume we're back on the home page and the user decides to click on exhibit A. They will be brought to the middle screen where they will see artwork that was most recently commented on in that exhibit, and data analytics (i.e. graphs and charts) giving them information about the exhibit as a whole. When they click on a piece of art, they will be brought to the top right screen, showing them the piece, recent feedback about the piece, and data/graphs specific to that piece. On the other hand, if the user clicked on the "see more" for the data analytics, they would be brought to the bottom right screen, showing them all of the data for the exhibit as a whole.
![exhibit functionality](/museum-experience/images/prototyping/pp-exhibit-flow.jpg){:height="30%" width="30%"}

##### original task two: connecting curators with museum visitors
Now we're back on the home screen. If the user clicks on the thought bubble, they will be brought to the middle-left screen, showing them short notation of questions and suggestions (i.e. if the question is too long then it will be cut off) and the exhibit it is referring to. By clicking on one of the reply buttons, the user will be taken to the middle-right screen, showing them a picture of the piece of exhibit, followed by the full question/suggestion, and the option to reply or ignore it. By clicking reply, the user then goes to the rightmost screen, opening a chat window that lets them send a message to the visitor who asked it. Aside: since we are creating a design for curators as our primary user, we are ignoring the implementation of the museum visitor aspects. Therefore, for now, we are not worrying about how this response gets into the hands of the visitor. ![communication functionality](/museum-experience/images/prototyping/pp-comm-flow-keyboard.jpg){:height="30%" width="30%"}


### testing process

Our heuristic evaluation can be found [here](htps://londonmeanswild.github.io/museum-experience/2018/10/30/heuristic/), while the usability design review can be found [here](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/). 

In running the tests, we discovered that each user had a different way of navigating through their (identical) tasks. 
**need more insights** 

### testing results

Our heuristic evaluation can be found [here](htps://londonmeanswild.github.io/museum-experience/2018/10/30/heuristic/), while the usability design review can be found [here](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/). 

We learned that we needed to organize information differently, and provide multiple paths to the same result. Our heuristic evaluator changes were to:
* Add text to home screen in place of comment icon
* Add feedback home screen category
* Add identifiers for (un)answered questions on the Questions and Suggestions screen. Did so by changing the color of text on answered questions.
* Change reply indicator. Instead of an arrow there is now a “reply” button. On addressed questions, “reply” button has been changed to “replied."
* Add filter by keyword for drop-down “sort” menu. This allows circumvention of a “delete” or “restore” function. Instead, people can search by answered or ignored.
* Add data viz labels

Our heuristic evaluators were quite thorough, so our cognitive walkthrough proved to be relatively unexciting. We also think it may have been useful to do a cognitive walkthrough with an outside perspective, because we are probably too close to the project. 

The usability walkthroughs proved insightful, however, and 
![usability feedback table](/museum-experience/images/prototyping/usability-feedback-table.png){:height="100%" width="100%"}

### final paper prototype

Our final paper prototype can be found towards the bottom of our usability review [page](https://londonmeanswild.github.io/museum-experience/2018/11/08/usability-review/). 

![final overview](/museum-experience/images/prototyping/final-overview.JPG){:height="30%" width="30%"}

![final home screen](/museum-experience/images/prototyping/final-home.JPG){:height="30%" width="30%"}

![final all feedback](/museum-experience/images/prototyping/final-all-feedback.JPG){:height="30%" width="30%"}
![final response preview](/museum-experience/images/prototyping/final-response-preview.JPG){:height="30%" width="30%"}
![final response](/museum-experience/images/prototyping/final-response.JPG){:height="30%" width="30%"}
      
![final artwork analytics](/museum-experience/images/prototyping/final-artwork-analytics.JPG){:height="30%" width="30%"}
![final exhibit analytics](/museum-experience/images/prototyping/final-exhibit-analytics.JPG){:height="30%" width="30%"}

#### Task Review
Note: task 1 is now a more specific version of our old task (summarizing and communicating data), and task 2 is staying the same. Since we are dealing with fictional data, it has been hard for us to figure out how vague or specific we need to be. However, after talking to a curator, I think we've narrowed down to three important pieces of information (there was discussion about this in the feedback table above). Based on this, we've decided that task 1 will revolve around communicating this information to the curators (in as simple a way as possible). Additionally, the curator seemed to be very interested in the communication aspect of our design (task 2), so we've also decided to keep that, and again, make that process as easy as possible.

### revised task one: find exhibit and artwork analytics
The user starts at the home screen.
![new home screen](/museum-experience/images/prototyping/final-home.JPG){:height="80%" width="80%"}

They then have a couple options from here: click the all feedback button, or click one of the exhibits listed on the bottom half of the screen. Let’s first assume they click one of the exhibits. They will then be taken to the analytics for the exhibit they clicked, showing both the overall analytics for the exhibit and an alphabetically organized set of the artwork in that exhibit. 
![new exhibit analytics](/museum-experience/images/prototyping/final-exhibit-analytics.JPG){:height="80%" width="80%"}

The graphs from the overall analytics are based on what we found are the most important and feasible pieces of information (feasible based on assuming we have visitor feedback data available, and important based on discussion with a curator). Let's assume the user then clicks on a specfic peice of artwork. They will then be taken to the artwork analytics page which shows the piece of art, and the same graphs, except using data for that specific piece work. Additionally, the emotional distribution graph might be confusing since negative emotion may seem like a bad thing, so there is a help button to explain that this might not be the case.
![new individual piece analytics screen](/museum-experience/images/prototyping/final-artwork-analytics.JPG){:height="80%" width="80%"}

### revised task two: connecting curators with museum visitors
Now let's assume users click the home button to get back to the home page.
![new home screen](/museum-experience/images/prototyping/final-home.JPG){:height="80%" width="80%"}

If a user clicks the all feedback button, they will then be taken to the all feedback screen. This will show them all visitor feedback from most recent to least recent, categorized by exhibit. We have also determined that there are 3 types of comments: questions, suggestions (not a question, but comment implies that action should be taken), and general comments (comments that don't imply action should be taken). The user can then click one of the checkboxes in order to make certain types of questions appear or disappear based on what they want to see. 
![new all feedback screen](/museum-experience/images/prototyping/final-all-feedback.JPG){:height="80%" width="80%"}

If a user now wants to reply to a comment, they click reply ("ignored" and "replied" are also still clickable, and take you to the same screen). They will then be taken to a response preview screen where they can see the exhibit/artwork and the full question. The curator can see responses from previous curators, edit those responses, ignore the question (which will mark the question as ignored), or respond to the question. 

![new response preview screen](/museum-experience/images/prototyping/final-response-preview.JPG){:height="80%" width="80%"}

Let's assume the user clicks respond. Now they will see a response screen and be able to type and submit their response.

![new response screen](/museum-experience/images/prototyping/final-response.JPG){:height="80%" width="80%"}
     
      
      

### digital mockup

Our digital mockup page is [here](https://londonmeanswild.github.io/museum-experience/2018/11/12/digital-mock-up/). 

