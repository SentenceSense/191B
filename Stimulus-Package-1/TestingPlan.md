# Test Plan

“This document describes the scope, approach, resources and schedule of intended test activities. It identifies amongst others test items, the features to be tested, the testing tasks, who will do each task, degree of tester independence, the test environment, the test design techniques and entry and exit criteria to be used, and the rationale for their choice,and any risks requiring contingency planning. It is a record of the test planning process.” From "Test Plan | Software Testing Fundamentals." 2011. 27 Sep. 2012 <http://softwaretestingfundamentals.com/test-plan/>

## Part I:  Software Testing Plan 

### Sentence Sense website redesign

### Team Sentence Sense

### Team Members

Pen Han Chang, Tsz Hang Ng, Derick Nguyen, Dylan Shigekawa, Darien Vidaure

### November 11, 2014


#### Revision History (what changed since last time, since this document will continue throughout the project in the following quarters)

-Created for Stimulus Package 1 (November 11, 2014)
 
#### Introduction:

* Test to see if users are able to go to the chapters that they want
* Test to see if all the games work
* Test to see if all the button works in the navigation bar
* Test to see if the website can be shown on any web browser
* Test to see if the website can be shown on any device (such as tablets, smart phones and laptop computers)
  * How do interactive modules work in devices other than laptops? Touch interface works with modules?

##### Specify the goals/objectives.

* Users are able to view the website and connect to any page and chapter that they want
* Users are able to go to any page and any chapter directly and easily
* Users are able to play games without any obvious problems

##### Specify any constraints.

* Developing for a wide range of screens and devices
* Some content of the chapters is still not provied by the client

##### Assumptions and Dependencies

       -Assumptions:

       * Users already have experience using a web browser to browse websites
       * Users can simply manage to play the game easily

       -Dependencies:
       
       * Currently, the HTML snippets plugin for WordPress is a big dependency because without it we wouldn't be able to show the modules within the site.



#### Test Item Pass/Fail Criteria:

* Test to see if all the games work:
  * Test will pass if no errors come up during the running of the game. Alternatively, test will fail if errors occur and game renders unplayable.
* Test to see if all the button works
  * Test will pass if all buttons do intended action. Test will fail if button reacts differently than expected
    * Game button - activate games
    * Next button - directs to next section/chapter
    * Back button - driects to previous section/chapter
    * Exit button - closes current application
    * Submit button - submits the work

* Test to see if the website can be shown on any web browser
  * Test will pass if website will show up on major browsers. Test will fail if the enitre page does not appear in the browser.
    * Chrome
    * Firefox
    * Internet Explorer
    * Safari
* Test to see if the website can be shown on any device (such as tablets, smart phones and laptop computers)
  *Test will pass if website can be shown on screens larger than 7 inches. Test will fail if website will not appear on screen.
    * Android Tablet 7 inches and larger
    * iPad 7 inches and larger
    * Laptop/Computer screen (see browser test)


Test Deliverables:

       -Test Reports
       -Feedback Reports

 

## Part II:  User Testing Plan

### Heuristic Evaluation/Checklist
For the Heuristic Evaluation we will use the Nielson's 10 usability principles to evaluate our system:
1. Visibility of system status
2. Match between systems adn the real world
3. User control and freedom
4. Consistency and standards
5. Error prevention
6. Recognition rather than recall
7. Flexiblity and efficiency of use
8. Aesthetic and minimalist design
9. Help users recognize, diagnose, and recover from errors
10. Help and documentation

Using these 10 principles we would evaluate the entire website's interface (using its current state) as well as the individual modules' interfaces (using mockups since we don't have them all fully developed yet). We could perform this evaluation by each individual team member going through the 10 heuristics and then comparing and discussing our findings as a team. 
 
### User Testing

#### Usability Defined
The International Organization for Standardization or ISO's definition of usability is the "effectiveness, efficiency and satisfaction with which a specified set of users can achieve a specified set of tasks in particular environments."

#### Costs of Not Testing
A product that is not usable creates unnecessary costs:
 
* Increased customer support costs,
* Increased development costs to correct problems,
* Increased documentation costs to support a weak product,
* Loss of users.

#### Testing What?
The usability testing will investigate the Sentence Sense prototype.  The Development Team will use the results of the test to refine the user interface for the Sentence Sense
 
The test is directed towards the Viewer functionality.  Authoring functionality will not be tested at this time.
 
A number of usability issues have been identified, and the usability test is directed towards these.
 
The display of documents and non-documents in the various panes,
* Navigation menu,
* Chapter list,
* The search function,
* User – Game interaction,
 
#### Materials
Set-up sheet,
* Task lists,
* Device with a browser (computer,
* Observation sheets,
* Questionnaires.

#### Users
Three users with teaching experience, three ESL students and three young students will be recruited to participate in usability testing.

#### Location
The testing will either be performed in the ICS 193 room or remotely from the user’s home.

#### Equipment
A personal computer or laptop with a working browser will be used.

#### Set-up Sheet
The Usability Test team will use the Set-up sheet to ensure that the testing room is set-up properly before the users arrive. It will include a checklist of necessary material and equipment for the test, as well as the preamble that will be given to the participants.
 
Checklist:
* A personal computer/laptop with a working browser,
* Ensure that Sentence Sense will show up on the device,
* Task list,
* Questionnaire

#### Task List
Users will be given a task list that outlines the tasks they must perform during the test. Each task in the test will have an associated question and evaluation scale.  A five-point scale, with appropriate labels, will be used for the usability testing. Also, some tasks may be accompanied by short questions to help the team if the User is testing remotely. The users will circle the appropriate number on the scale, as well as write any comments they may have in the "Notes" section.  

The testers will be asked to time their session for each part so the team will have a rough estimation if some interactions are taking too long.

If an error or unexpected occurrence is encountered, the tester will be asked to record the action that causes the error, and the error encountered.

#####Benchmark Tasks:

 Navigation
* 1.	Navigate to the Chapter 1 – overview page
* 2.	Navigate to Chapter 1 – Section  2
* 3.	Navigate to Chapter 1 – Section 3
* 4.	Navigate to Chapter 5 – overview page
* 5.	Navigate to the website homepage

Search
* 1.	Using the search bar, navigate to the page that talks about the structure of a sentence
* 2.	Using the search bar, navigate to the page that talks about the parts of sentence

Games
* 1.	Click the button on the homepage that says ‘Try This’
* 2.	Play the game that appears

#### Measures
* Time to do tasks – the time for each section will be recorded
* Errors – unexpected occurrences and errors will be asked to be recorded
* Thinking out loud – testers will be asked to think out loud and will be recorded
* Questionnaires – these will ask the user about their satisfaction and ask for suggestions for improvement


#### Qualitative Data
For users that will be testing in person:
* Users will be encouraged to talk aloud during the testing.  They should discuss their problem-solving strategies, give their points-of-view, and make whatever comments they like throughout the session.  Members of the Usability Test Team will take notes throughout the session in order to collect this qualitative data.

For remote testers:
* A set of questions that accompanies the task list will help gather quantitative data.


#### Observations
The members of the Usability Test Team will record their observations on Observation sheets during the testing.

#### Questionnaire
After the test, each of the participants will be given a questionnaire, and asked to complete it before leaving. However, if a participant is in a rush, he/she will be asked to take the questionnaire with them, complete it, and email the results.
