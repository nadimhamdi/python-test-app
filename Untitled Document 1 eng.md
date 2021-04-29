So Nadim graduated from the national school of engineers in tunisia I have 1 years and 6 months of experience as a python developer, indeed I led a lot of projects that I can name the most important ones, don't hesitate to ask me questions:

therefore starting with:

the first project carried out at artmindsolutions which was put into production for  banking sector the BIAT it's a tunisian banck which consists of an attendance systeme called THIRD EYE its main role is to detect the arrival of employees through a surveillance camera, in effect this API consists of two interfaces; admin interface for adding employees and personal information; phone number, image and department and an interface for employees to see their arrival history.
this application is based on facial recognition using MTCNN and opencv as library for image processing.
coded with python, flask as a library for communication, postgresql for the database, html and css for web interfaces and jenkins for testing and deployment

#college tech lead google


then the second project which is the creation of a voice recognition model in French dedicated to the call center Communik CRM the goal of this project for the control of conversations between customers and employees for example the head of the call center banned to the employees to say bye bye to the clients, the recognition algorithm will be active as well on the server, the conversion of the speech into usable text will take place and if bye bye is detected then the manager will be warned.

this project is based on speech recognition, deepspeech as a signal processing library, machine learning, python for coding and flask for communication

and finally the last project dedicated to the Tunisian ministry of industry which is the creation of a recognition model for Arabic text in a scanned image of the official newspaper of the Tunisian republic in order to convert it to a text
indeed these texts will be put in a database linked to a web interface that it is called "artmind search engine" whose role is the search by key words or by speaker to extract the speeches of the representatives of the peoples

this project is based on text processing with the open source library called kraken, python for coding, flask for webservices, and PHP for the web interface and finally Sqlserver for the database

#agile method


before moving on do you have any questions concerning these 3 projects?

regarding Imaginepartners

the first project which concit of a resume classification api.

in fact the sorting of resume is done from the post description.

the user launches the application which has as input the description of the post in txt extension or  word, then the folder that will contain the resumes collected .

the application gives as a result the first 20 resume that can be downloaded 

this api is based on text processing with NLP and NLTK for extracting  keywords, coded with python HTML and CSS for the web interface and jenkins for the test and it's the deployment

and finally the second project that we could do its deployment with jenkins as well as its test 

it's A CHATBOt, a kind of a virtual agent designed for the automatic response to the customer and offering help, and can also extract the feelings through the text for the determination of the customer satisfaction this Chatbot can also learn new context indeed it can store the words and the questions which does not include in its database for the generation of a another version of the Chatbot which is able to understand better 

based on machine learning, NLP and NLTK for text processing  and python for coding and flask for communication



**the workflow**

we used the git flow as a workflow indeed we create a branch of featuer which uses the development branch as a parent branch which contain the complete history of the project "which is itself a branch linked to the master branch"
Once the develop branch has acquired enough functionality for a release (or a predefined release date is approaching), we fork a release branch from the develop branch this branch will only be dedicated to bug fixing, documentation generation and other delivery-oriented tasks

Once ready, the release branch is merged into the master branch and tagged with a version number



git checkout master
git checkout -b develop
git checkout -b feature_branch
# work happens on feature branch
git checkout develop
git merge feature_branch
git checkout master
git merge develop
git
branch -d feature_branch


#quit artmind

as a developer, career development is a goal, indeed integrating Fundrock's team is a step towards evolution and discovering new ways of working with a pleasant environment

furthermore I consider my skills to be well suited to this position as well as the Fundrock team.

It is therefore quite natural that I turned to your company whose sector of activity corresponds perfectly to my future professional aspirations.

( to be the best in my field )

Rigorous and versatile, I will be delighted to be able to bring my skills acquired during my studies as well as my deep enthusiasm to work alongside you.





#agile scrum method

**Waterfall or V-cycle management**

we always start with the analysis of the client's needs and the drafting of the specifications.

Once the various parties have agreed, the functional and then technical specifications of the application are drafted and validated. 

All the functionalities of the software or application and the terms of their implementation (technical choices in particular) are described before starting the development of the code

The project is then divided into tasks which are quantified, prioritized and scheduled

this results in a schedule making possible to know the start and end dates of each task, as well as of course the planned end date of the project. 

All that remains is to assign the various tasks to the team members.

"" The project dashboard, updated very regularly, allows you to follow the progress. ""

 Finally, when the developments are completed, the product can finally be delivered to the customer for validation (testing and deployment)

**Agile management**

The main consideration of the agile philosophy is that the need cannot be fixed and that it will undoubtedly evolve as the project progresses. With simple and clear rules, it is possible to adapt to these changes and minimize or even eliminate the tunnel effect that causes many IT projects to fail.


**Scrum**
The project is organized around development "sprints" generally lasting two to four weeks.

The project begins with "sprint 0", dedicated to carrying out all preparation and implementation work: design and architecture, development environments, monitoring and integration tools, etc.

The requested functionalities are listed and described in the form of “user stories” and placed in the product backlog. At the start of each sprint the team is brought together to determine which user stories will be developed. They are quantified during "poker planning" and prioritized.

"All of the user stories or the selected tasks constitute the 'sprint backlog'."

Throughout the sprint, "daily meetings" are organized

"a daily meeting lasts only 15 minutes and all participants remain standing. This is a particularly effective way to ensure that it does not drag on. The objective of this meeting is to keep the team in sync. so that everyone has the same level of information. "

At the end of the sprint, a demonstration of the application in its current state is given to the customer. Both the customer and the end user can handle the application and check that the developments made during the sprint are in accordance with what was expected. Remarks can be made and requests for modifications made. They may or may not be taken into account in the next sprint.

On the last day of the iteration, a meeting called a "sprint review" is also organized. Now is the time for the whole team to recall the goals that have been set and the features that have been achieved and delivered.

Finally, the project team meets one last time during the sprint for the retrospective. This is an opportunity to list the processes that worked well during the sprint and those that need to be improved

if the project requires improvement then an improvement plan is put in place and the next sprint can start

#Role
The "Product Owner" or "PO": he carries the vision of the product to be achieved and is therefore generally a business expert. He works in direct collaboration with the development team and in particular is**responsible for filling out the product backlog**and**determining the priority of the user stories to be carried out**. It can be internal or external, although it is usually the customer.

The "Scrum Master" or "SM": This is a full member of the project team, and he must master Scrum because he is responsible for ensuring that the methodology is applied correctly. He should not be confused with a project manager. Its role is not to lead, but to**facilitate dialogue and work between the various stakeholders, so that the team is fully productive**

#tools

**The Burndown Chart**: this is a simple graph showing the progress of each task. It helps provide the entire team with a clear and up-to-date view of the status of work and the amount of work remaining. It is usually updated during the daily meeting.
The task board: a central tool for the scrum sprint, this project dashboard allows real-time monitoring of the progress of the various tasks. It is made up of three columns with to-do, current, and completed tasks. It is usually located in a place visible to the whole team (a board hung on the wall or displayed on a big screen) and is updated directly by developers as the activity they are working on evolves.

**The learning matrix**: this "learning matrix" aims to help project team members identify the positive points of the project and those that need improvement. Used in particular during the agile scrum retrospective, it is part of the project's continuous improvement process. The matrix is ​​divided into four quadrants: what is wrong and needs to be changed, what is going well and needs to be repeated, new ideas to try, and people liked. Each participant can stick a post-it with their ideas in the different quadrants, and then each can vote for the suggested suggestions. This ultimately helps to identify organizational priorities, especially for the next sprint, and to improve working conditions and team productivity.

**The storyboard**: this is a graphic tool to illustrate the different steps to reach a goal. The storyboard looks like a comic strip, each box representing a step, and gives an example of what is expected. This tool is intended for the description of the functional aspect and not for the design or demonstration of the graphical interface.

**The Sunset graph**: this graph allows you to follow the progress of the team as well as the progress of the project more generally. It provides a holistic view of product backlog content with an importance ranking of expected features. Thus, the speed of the team becomes clear and it is possible to anticipate any changes in delivery dates. It is also possible to follow the consumption of the budget and prevent the risk of slippage. The Sunset graph is updated at the end of each scrum sprint.

# different types of agile retrospectives
The scrum retrospective allows at the end of each sprint to identify strengths and areas for improvement on the project. There are several types of retrospectives depending on the objectives to be achieved and the project team in place. The topics covered differ according to the needs. Here are a few examples:

**Recognition**: The aim here is to emphasize what was done well rather than the negatives.

**Strengths**: identifies the main strengths of the team and defines actions to make the best use of them.

**Top 5**: The five biggest problems encountered during the project are listed so that the participants can discuss them and propose actions to remedy them.

**Action plan**: allows you to decide on short-term actions that will have a long-term effect on the project.

**Complexity**: Determines the best way to manage complexity within the project team.

**Scrum Values ​​**: the objective is to better understand the values ​​carried by Scrum and to assess the team's adherence rate to these values ​​in complete transparency.

#pilier

**Transparency**: Important aspects of the process must be visible to everyone. This is why SCRUM insists on creating a common language between team members and management, which requires a common understanding of the project.

**Inspection**: a regular review of the results produced is carried out in order to detect hearings. It is important that these inspections be carried out by a well-trained inspector and in an appropriate manner as this could hamper the progress of the project.

**Adaptation**: when a deviation is assessed during the inspection, the process should be adapted through actions aimed at improving the situation (3).



#jenkins
**jenkins what is it?**

Jenkins is an open-source, continuous integration-focused Java automation server. Jenkins allows developers to test their programs on the go, while allowing upgrades and additional features to be incorporated throughout the process.



**Why should developers use Jenkins?**

Easy to detect bugs from the start;
we will have an automated testing process; which provides us with Continuous Integration.



**What is an "automated test"?**

Automated testing occurs when a program (framework) tests your developed programs (web applications) without human intervention.




**What is continuous integration?**

Jenkins requires two basic conditions: a viable source code repository and a build script registered to that repository.

However, you must also have two software before installing Jenkins - Java Development Kit and Jakarta:




**What is the default security mechanism for user authentication?**


 Jenkins' default is to store user data in the internal database.




**Name at least two of the most popular plugins for Jenkins.**


maven and git amazon html




**How do you back up your files?**


The JENKINS-HOME directory contains all your personal configurations. This means that the only thing you can do to protect your files from any problems is to back up the directory.





**What is a "Jenkins pipeline"?**

The term "Jenkins pipeline" is used to describe the process from the early stages of a project's development until it is released to the public.






**What are the three basic stages of a Jenkins pipeline?**

Build the project, test it, and then deploy it.



**What is the connection between Hudson and Jenkins?**

Long ago, Hudson was the official name (an earlier version) of what is now known as Jenkins.




**Name two ways of planning a construction.**

You can either issue commits to source code management or, if you wish, you can manually request builds.





**What are the most popular environment variables?**

BUILD_ID
The current build ID, identical to BUILD_NUMBER for builds created in Jenkins versions 1.597+

BUILD_NUMBER
The current build number, such as "153"

BUILD_TAG
String of jenkins - $ {JOB_NAME} - $ {BUILD_NUMBER}. Convenient to put into a resource file, a jar file, etc for easier identification

BUILD_URL
The URL where the results of this build can be found (for example http: // buildserver / jenkins / job / MyJobName / 17 /)

EXECUTOR_NUMBER
The unique number that identifies the current executor (among executors of the same machine) performing this build. This is the number you see in the "build executor status", except that the number starts from 0, not 1

JAVA_HOME
If your job is configured to use a specific JDK, this variable is set to the JAVA_HOME of the specified JDK. When this variable is set, PATH is also updated to include the bin subdirectory of JAVA_HOME

JENKINS_URL
Full URL of Jenkins, such as https://example.com:port/jenkins/ (NOTE: only available if Jenkins URL set in "System Configuration")

JOB_NAME
Name of the project of this build, such as "foo" or "foo / bar".

NODE_NAME
The name of the node the current build is running on. Set to 'master' for the Jenkins controller.

WORKSPACE
The absolute path of the workspace








**How would you move a file from one server to another?**

just copy the working directory and paste it on the other server.



**Should you use Jenkins with Selenium?**

Yes, that is really very beneficial - this type of combination performs immediate tests whenever your program changes or changes in some way.




**Question 17: What is Ansible?**
Ansible is a configuration management tool that can be used for provisioning and can be implemented in Jenkins.





**Question 18: What is an "agent"?**
An "agent" can be thought of as a reference point - it specifies a point in the pipeline where Jenkins will be launched.




**start jenkins**

windows jenkins.exe start

ubuntu sudo /etc/init.d/jenkins start





















code quality and an easy solution


podt build: pzckzging of the project deployament and publication awa, mobile apk

analysis with tools: solaarcube;

functional test;

Performance Test ;

continuous integration ci / cd


April 5 availability
fircosoft software editor
why you want to quit artmind ===> fircosoft


