---
type:  post
title:  usability design review 
---

## Usability Tests

### Usability Test 1


### Usability Test 2


### Usability Test 3


## Feedback

### Table (see figures below for pictures of where problem occurs)
![usability feedback table](/museum-experience/images/prototyping/usability-feedback-table.png){:height="100%" width="100%"}


## Prototype Changes

### Here's an overview of our original paper prototype since the heuristic evaluation:
![original prototype](/museum-experience/images/prototyping/edited-full-flow.jpg){:height="80%" width="80%"}

### Here's an overivew of our new paper prototype
![new prototype](/museum-experience/images/prototyping/final-overview.JPG){:height="80%" width="80%"}

### Home Screen (old, new)
![old home screen](/museum-experience/images/prototyping/edited-home-page.jpeg){:height="30%" width="30%"}
![new home screen](/museum-experience/images/prototyping/final-home.JPG){:height="80%" width="80%"}

### "All Feedback" Screen (old, new)
![old all feedback screen](/museum-experience/images/prototyping/OLD-all-feedback.JPG){:height="80%" width="80%"}
![new all feedback screen](/museum-experience/images/prototyping/final-all-feedback.JPG){:height="80%" width="80%"}

### "[Category] Exhibit" Screen (old, new)
![old response preview screen](/museum-experience/images/prototyping/edited-ignore-answer.jpeg){:height="30%" width="30%"}
![new response preview screen](/museum-experience/images/prototyping/final-response-preview.JPG){:height="80%" width="80%"}

### "Questions and Suggestions" Screen (DELETED)
![old questions and suggestions screen](/museum-experience/images/prototyping/edited-comment-page.jpeg){:height="30%" width="30%"}

### "Exhibit [A]" Screen (old, new)
![old exhibit analytics](/museum-experience/images/prototyping/edited-data-viz.jpeg){:height="30%" width="30%"}
![new exhibit analytics](/museum-experience/images/prototyping/final-exhibit-analytics.JPG){:height="80%" width="80%"}

### "Exhibit [A] General Data" Screen (DELETED)
![old analytics general data screen](/museum-experience/images/prototyping/OLD-analytics-general-data.JPG){:height="80%" width="80%"}

### "Individual Piece Analytics" Screen (old, new)
![old individual piece analytics screen](/museum-experience/images/prototyping/OLD-artwork-analytics.png){:height="30%" width="30%"}
![new individual piece analytics screen](/museum-experience/images/prototyping/final-artwork-analytics.JPG){:height="80%" width="80%"}


## Task Review
Note: task 1 is now a more specific version of our old task (summarizing and communicating data), and task 2 is staying the same. Since we are dealing with fictional data, it has been hard for us to figure out how vague or specific we need to be. However, after talking to a curator, I think we've narrowed down to three important pieces of information (there was discussion about this in the feedback table above). Based on this, we've decided that task 1 will revolve around communicating this information to the curators (in as simple a way as possible). Additionally, the curator seemed to be very interested in the communication aspect of our design (task 2), so we've also decided to keep that, and again, make that process as easy as possible.

### Task 1: Find Exhibit Graphs/Analytics
The user starts at the home screen.
![new home screen](/museum-experience/images/prototyping/final-home.JPG){:height="80%" width="80%"}

They then have a couple options from here: click the all feedback button, or click one of the exhibits listed on the bottom half of the screen. Let’s first assume they click one of the exhibits. They will then be taken to the analytics for the exhibit they clicked, showing both the overall analytics for the exhibit and an alphabetically organized set of the artwork in that exhibit. 
![new exhibit analytics](/museum-experience/images/prototyping/final-exhibit-analytics.JPG){:height="80%" width="80%"}

The graphs from the overall analytics are based on what we found are the most important and feasible pieces of information (feasible based on assuming we have visitor feedback data available, and important based on discussion with a curator). Let's assume the user then clicks on a specfic peice of artwork. They will then be taken to the artwork analytics page which shows the piece of art, and the same graphs, except using data for that specific piece work. Additionally, the emotional distribution graph might be confusing since negative emotion may seem like a bad thing, so there is a help button to explain that this might not be the case.
![new individual piece analytics screen](/museum-experience/images/prototyping/final-artwork-analytics.JPG){:height="80%" width="80%"}

### Task 2: Connecting Curators with Museum Visitors
Now let's assume users click the home button to get back to the home page.
![new home screen](/museum-experience/images/prototyping/final-home.JPG){:height="80%" width="80%"}

Let’s now assume they click the all feedback button. They will then be taken to the all feedback screen which will show them all visitor feedback from most recent to least recent, categorized by exhibit. We have also determined that there are 3 types of comments: questions, suggestions (not a question, but comment implies that action should be taken), and general comments (comments that don't imply action should be taken). The user can then click one of the checkboxes in order to make certain types of questions appear or disappear based on what they want to see. 
![new all feedback screen](/museum-experience/images/prototyping/final-all-feedback.JPG){:height="80%" width="80%"}

Let's assume a user now wants to reply to a comment, so they click reply ("ignored" and "replied" are also still clickable, and take you to the same screen). They will then be taken to a response preview screen where they can see the exhibit/artwork and the full question. The curator can see responses from previous curators, edit those responses, ignore the question (which will mark the question as ignored), or respond to the question. 

![new response preview screen](/museum-experience/images/prototyping/final-response-preview.JPG){:height="80%" width="80%"}

Let's assume the user clicks respond. Now they will see a response screen and be able to type and submit their response.

![new response screen](/museum-experience/images/prototyping/final-response.JPG){:height="80%" width="80%"}

## Discussion of Important Changes

### Change to Data Analytics Display
We've mentioned this throughout the deliverable, but one of our biggest decisions was determining what data we should be displaying. Since vague data and graphs were not very helpful to the curator, we decided that we had to specfiy something a little more real. During our meeting with the curator, we noticed she really wanted to learn about the visitors and what they got out of an exhibit. Based on the assumption that we have visitor feedback data, we were able to create three graphs that we thought most effectively communicated this information. First, visitor satisfaction is a good overview of the feelings towards an exhibit. Second, types of comments gives the curator a sense of whether people are voicing their likes and dislikes. Finally, an emotional distribution let's the curator know if visitors are experiencing the story that the they are trying to illustrate (e.g. if the emotional distribution is high on the negative emotion end, then we know visitors have feelings of sadness, anger, or some other type of negative emotion. However, if this is the emotion curators are trying to elicit, then this will show that they did a good job). By creating these illustrations, we believe that we are communicating the most important information possible to the curator. Additionally, we had thought about adding a customization option for graphs since we no longer have a general data analytics page. However, this would require additional usability tests and we are not sure that we'll have the time to go through all the steps to make sure this is intuitive (creating a customization option essentially adds another task, and this could take multiple iterations to implement correctly).

### Change to "All Feedback" Screen
After the usability tests, we realized that the all feedback screen was vague (relative to the questions and suggestions page) and the options for narrowing were a little overwhelming. After talking with the curator, we found that it was most important to be able to categorize by exhibit, and then they should be able to categorize by the type of question. We realized that the "all feedback" and the "questions and suggestions" pages were unncessarily redundant (we originally had both to make sorting easier, but we realized this didn't really work). By combining the "all feedback" and "questions and suggestions" screens, we simplified the design, and made it much more intuitive. Additionally, we added time stamps in order to show that the information is organized by most recent to least recent (in the specific exhibit).

### Artwork Analytics Organization
In our original exhibit analytics page, we simply had a list of thumbnails to let users know that they could click to get specific artwork analatics. However, to our users, this was confusing and a little overwhelming (they also didn't know how these were ordered). We decided to categorize the artworks alphbetically to give a clear indication of order, and mention in the artwork analytics header that they can click on a piece. This makes the functionality clearer and more intuitive to use. Futher, since it would make sense for the exhibit analytics to be the highlight of the exhibit analytics page, we decided to flip the "exhibit analytics" section with the "artwork analytics" section. 


