---
name: heART
subtitle: looking to understand
image_path: /images/clients/blank.png
---

## Title here

### team:
* chris anton: coordinating mastermind
* kenneth an: artistic talent 
* landon marchant: random ideas generator 

#### problem and solution overview ####

Curators not only have limited feedback on visitor emotions, but even if they had a surplus of information, there would be no time in a curator's busy schedule to sort through it. There's currently no good way for a curator to know whether exhibits (and specific pieces of art) cause confusion or spark inspiration in the visitors who experience them. Furthermore, curators have noticed that, due to their busy schedules, there's a lack of connection between themselves and the museum visitors. 

Since there are multiple other groups focusing on data collection, we decided to pivot our project and assume that we have all the necessary data for this project (i.e. feedback about exhibits and artwork from museum visitors). Our vision is to create an application that will organize and present user data, and effectively communicate this information to curators (with little effort on their part). We want to allow curators to understand the experiences of visitors without sacrificing large amounts of time to personally connect with them. Furthermore, we want to repurpose some of those data visualizations. We think it would be cool to have an interactive wall panel of anonymized data for visitors to play with, increasing audience engagement and possibly giving a means for visitors to communicate more directly with curators (e.g. there could be an "ask the experts" field where visitors can post questions for curators to answer).

#### design research goals, stakeholders, and participants

We used a blend of contexual inquiry and interviews to engage with participants. These happened at WCMA. U3 wanted to start in a side gallery before going to the Object Lab, and U4 went directly to the Object Lab. Curator encounters were in offices and archives. Our inquiries analyzed WCMA curators and two Williams students, one who was a summer intern at WCMA and another who is an art enthusiast. The full writeup for each encounter can be found [here](https://londonmeanswild.github.io/museum-experience/groundwork/research/2018/10/04/CI-writeups/). From these, we developed a better understanding of both visitor and curator desires for the museum. In particular, the Williams students seemed to want a deeper experience where they can work to understand the art, and possibly even discuss it with others. Curators, on the other hand, want to get better and more direct feedback from the visitors. This is especially useful if they can get a sense of what frustrates people, and which galleries people are most interested in. We asked students what they thought of a low-tech data collection solution, and they liked the idea of post-it walls between exhibits. When asked for their thoughts on solutions for more engaging exhibits, students had varying thoughts on what made a good exhibit. One didn't like the arrangement of art, while the other student enjoyed having to engage with art and question. The curators didn't want a way to track emotion, since it is so subjective. Instead, they want some way to hear what is frustrating or interesting to visitors. 

#### design research and themes

Our high level themes are now feedback and engagement. Visitors expressed a desire to understand, relate to, and engage with exhibits, but without having answers handed to them. Meanwhile, curators wanted to create exhibits for people to critically engage with, wanted immediate feedback on exhibits, and wanted to give context. 

We identified themes by looking for common statements, concerns, and questions between our participants, as well as their differences. The curators and visitors had opposing responses despite shared priorities. However, all of them -- and the disconnect between responses -- point to an issue of curator/visitor communication. 

We are assuming that the data we need has already been collected. This allows us to focus on the challenge of organzing and representing data. We have decided to focus almost entirely on curators, which will allow us to simplify our design.  We currently plan on building an app that organizes and communicates that data efficiently to the curators (e.g. maybe has a mix of visitor comments, number of people visiting exhibit, number of people who liked a certain artwork, etc.). Since the visualization and data work has already happened, we intend to repurpose it in order to engage visitors (and possibly create a more direct connection between visitors and curators). We are considering the merits of  an interactive wall panel that displays select data, and allows visitors to interact with it in some way or another (e.g. touch a pink bubble that splinters into different pieces of information about certain exhibits). 

We also want to further explore the idea of immediate feedback via text, whether texts are sent to a curator or AI. This system could use a piece, exhibit, or theme-specific key word so that responses were sent to the right individual or team. This is inspired by the curator's comment that "he wished he could get visitor questions directly sent to his phone so he could answer them (given he had the time), that way it might eliminate some frustration." 

#### task analysis 

We intend the majority of this design to be used by curators. We plan on repurposing some of the work in order to engage with museum visitors. Our tasks allow curators to view and respond to feedback from visitors based on date/time, theme, or exhibit in question. They also will allow visitors to engage with select portions of this data in an interactive exhibit, modeled after the data visualizations curators have access to. Hopefully, our tasks will help curators develop exhibits based on understanding visitor experiences, and increase visitor willingness to give feedback. The ability to perform curation tasks is  developed through formal education, personal style development, and mentorship, and assisted by the presence of interns, professional peers, and the museum database. Our design will allow curators to deepen their skills and work more effectively as they go through the WCMA archives. Curators need access to precise, yet diverse, data. They need visitor experience, quantified. Right now they have a gap in data because many people who don't take the WCMA experience surveys or exit interviews. We are assuming this data has been provided -- it is now our responsibility to help make sense of it. Curators are currently designing new exhibits 2-3 times a year, so we are focusing on the real-time reporting of data to curators, with features that allow them to examine feedback over different timespans. If things go wrong, curators will be making decisions based on faulty information since our design is focused on data organization and visualization. 

#### design sketches 
##### **Task Recap:** #####
**1. collect pre-existing data from WALLS journals**

**2. collect exhibit thoughts and feedback from representative groups of visitors**

**3. assign collected visitor data to specific artwork in database**

**4. search database to curate exhibits**

**5. summarize and communicate visitor feedback to curators**

**6. establish a direct connection between curators and visitors (i.e. where visitors can ask clarifying questions)**

##### Designs: #####

All of our designs implement three new tasks, and combine existing tasks to do so. Our three new tasks are
*  Allow visitors to give feedback on art
*  Curators use visitor responses to curate new exhibits
*  Curators can "test" exhibits

Design one combines tasks [2, 3, 5, 6](https://londonmeanswild.github.io/museum-experience/teamwork/ideas/2018/10/12/task-review/).

![design one, image one](/museum-experience/images/ideation/design-1-1.png)
![design one, image two](/museum-experience/images/ideation/design-1-2.png)
![design one, image three](/museum-experience/images/ideation/design-1-3.png)
      
general idea:
We see a mobile interface - either through an app or device - as a way to collect feedback from visitors (task 2). This feedback will be saved to the database for each specific piece they comment on (task 3). Some computer algorithm would search for certain keywords in each of the comments. It would then categorize these comments based on positive/negative feedback, whether or not the feedback is a question, etc. (task 5). 

Design two combines tasks [3, 4, 5, 6](https://londonmeanswild.github.io/museum-experience/teamwork/ideas/2018/10/12/task-review/)

![design two, image one](/museum-experience/images/ideation/design-2-1.png)
![design two, image two](/museum-experience/images/ideation/design-2-2.png)
![design two, image three](/museum-experience/images/ideation/design-2-3.png)
![design three, image four](/museum-experience/images/ideation/design-2-4.png)

general idea:
Assuming we have all the data we need, the task becomes creating an application that will summarize and present data, allowing curators to search it. Our application’s interface would show how many people looked at a certain piece, how many people commented on it, the exhibit it's currently in (or was last in), and the history of the piece. Grouping information by exhibit makes it easy for curators to know which exhibits - and pieces - provoke certain responses. Through an interactive wall panel, we may also be able to engage visitors with this data as well. Even though we will have to make sure we don't spread our design too thin, we may be able to create a project that appeals to multiple groups of users (i.e. both curators and visitors) by repurposing data and designs.

Design three combines tasks [2, 3, 4, 5](https://londonmeanswild.github.io/museum-experience/teamwork/ideas/2018/10/12/task-review/)

![design three, image one](/museum-experience/images/ideation/task3-1.jpg)
![design three, image two](/museum-experience/images/ideation/task3-2.jpg)


general idea: 
Allow curators to virtually test exhibits. Instead of having exhibits where visitors provide feedback, curators will create a virtual temporary exhibit that visitors can explore on the app. Similarly to how the museum has promotions for temporary exhibits, they can do something to try to promote the exploration of these virtual exhibits. Even though it might be difficult to get a representative sample of visitors, this will allow much faster feedback (task 2). Additionally, since the feedback will already be submitted electronically, summarizing it will be a lot easier (can do the same thing where you tag certain keywords in the feedback — task 5), and the data will already be assigned to each piece of artwork (task 3). Finally, this will make it easier for curators to curate exhibits (task 4) since they can test things more easily and see how they work. This is mostly based on our data that curators have to go through a lot of trouble with temporary exhibits, mostly with intent of collecting feedback. With this virtual exhibit, it will be much easier and cost effective to try out newer and more esoteric pieces.

#### written scenario 
 (1 paragraph) Convert your two tasks into written scenarios for your design. Scenarios include the steps a person will go through to accomplish the task, including references to your design. Scenarios do not need to detail every little step, but should be realistic, should be dependent upon the design you have chosen, should appropriately reference elements of your design, and should communicate how a person will accomplish the task using your design. Include images in the body of the write-up with appropriate figure numbers and captions and refer to the figures in the body of your text


#### storyboards of selected design
Include updated storyboards of your design. Reference these appropriately in your scenarios. Include images in the body of the write-up with appropriate figure numbers and captions and refer to the figures in the body of your text


