### Welcome to my COMAS repo! 
 
This repo holds the files I played a major role in developing while I was helping design Marist College's "Course Offering Management & Advisory System."
In addition to myself, these files were worked on by 3 other students at Marist College. Other files and dependencies within the COMAS source code have been omitted from this repository in order to avoid posting others' code under my public repository. This code is not intended to run in its current state, but serve as a location to display code I worked on.

The code here is the first iteration of COMAS and was the result of 8 weeks of requirements gathering and another 8 weeks of coding. 

#### Context Regarding COMAS
COMAS is a web application designed for two primary reasons.
  1. to streamline the professor course scheduling process at Marist College
  2. Provide the department chair with an easy way to send his department's schedules to the registration department. 

COMAS allows professors to log into an account where they are presented with an interface that allows them to send requests to the department chair outlining the course a professor wants to teach, and it's time. In addition to this, the dashboard provides teachers with:
  * an updating calendar which displays a professor's schedule as it is being built
  * information regarding a professor's contractual credit requirements
  * information about their approved and denied courses

The dashboard handles a number of issues such as, monitoring course availability and schedule overlap, dynamically handling credit/time requirements for 3 and 4 credit courses, and more.  

The code in this repository is for the professor dashboard of our COMAS interface. It serves as the landing page for professors, and is currently the only page that professors need to interact with. 
