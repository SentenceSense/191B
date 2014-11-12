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

###Heuristic Evaluation/Checklist
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
 
###User Testing

For actual user testing, you have to plan for the kind of user you will recruit and how many, when the sessions will be, what tasks you will ask them to do, what interface they will use, how you will record their actions and evaluations (e.g. a quick survey), and when you will take your findings and make changes to the interface.  Those planned design changes appear on a sprint.

A good resource for a User Testing Plan: http://it.toolbox.com/blogs/<wbr />enterprise-solutions/sample-<wbr />usability-test-plan-17826. (Note: Some important elements of a User Test Plan are missing from this template. Use this resource purely as a start point for your User Test Plan.) 
