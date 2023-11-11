# Portfolio of my work from semester 3

Aleksandar Garkov
Class: 
Teachers: Jean Paul Ligthart and Samuil Angelov 

## My Website
- Git Repository: 
- Research Report: https://github.com/nickybreezy/Nickster/blob/main/researchreport.md
---
## Table of contents
1. [Introduction](#1-introduction)
2. [Learning Outcomes](#2-learning-outcomes)
    2.1. [Web Application](#lo1-web-application)
    2.2. [Software Quality](#lo2-software-quality)
    2.3. [Agile Methods](#lo3-agile-methods)
    2.4. [CI/CD](#lo4-cicd)
    2.5. [Cultural Differences and Ethics](#lo5-cultural-differences-and-ethics)
    2.6. [Requirements and Design](#lo6-requirements-and-design)
    2.7. [Business Processes](#lo7-business-processes)
    2.8. [Professional](#lo8-professional)

## 1. Introduction

Welcome to my ICT and Software Engineering portfolio! This portfolio shows my work throughout the research, development and testing of my latest software projects in university. 



## 2. Learning Outcomes

| #   | Name                            | Short description                                                                                                                           | Clarification                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| --- | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Web application                 | You design and build **user-friendly, full-stack** web applications.                                                                        | **User friendly:** You apply basic User experience testing and development techniques.<br>**Full-stack:** You design and build a full stack application using commonly accepted front end (JavaScript-based framework) and back end techniques (e.g. Object Relational Mapping) choosing and implementing relevant communication protocols and addressing asynchronous communication issues.                                                                     |
| 2   | Software quality                | You use software **tooling and methodology** that continuously monitors and improve the software quality during software development.       | **Tooling and methodology:** Carry out, monitor and report on unit integration, regression and system tests, with attention for security and performance aspects, as well as applying static code analysis and code reviews.                                                                                                                                                                                                                                     |
| 3   | Agile method                    | You **choose** and implement the most suitable agile software development method for your software project.                                 | **Choose:** You are aware of the most popular agile methods and their underlying agile principles. Your choice of a method is motivated and based on well-defined selection criteria and context analyses.                                                                                                                                                                                                                                                       |
| 4   | CI/CD                           | You **implement** a (semi)automated software release process that matches the needs of the project context.                                 | **Implement:** You implement a continuous integration and deployment solution (using e.g. Gitlab CI and Docker).                                                                                                                                                                                                                                                                                                                                                 |
| 5   | Cultural differences and ethics | You **recognize** and **take into account** cultural differences between project stakeholders and ethical aspects in software development.  | **Recognize**:  Recognition is based on theoretically substantiated awareness of cultural differences and ethical aspects in software engineering.<br>**Take into account:** Adapt your communication, working, and behavior styles to reflect project stakeholders from different cultures;<br>Address one of the standard Programming Ethical Guidelines (e.g., ACM Code of Ethics and Professional Conduct) in your work.                                     |
| 6   | Requirements and Design         | You analyze (non-functional) requirements, elaborate (architectural) designs and validate them using **multiple types of test techniques**. | **Multiple types of test techniques:** You apply user acceptance testing and stakeholder feedback to validate the quality of the requirements. You evaluate the quality of the design (e.g., by testing or prototyping) taking into account the formulated quality properties like security and performance.                                                                                                                                                     |
| 7   | Business processes              | You analyze and describe **simple** business processes that are **related** to your project.                                                | **Simple:** Involving stakeholders, predominantly sequential processes with one or two alternative paths.<br>**Related:** Business processes during which the software that you are developing will be used (business processes that the software must support by fully or partially automating them).<br>**or**<br>Business processes needed for the success of your software development project (e.g., product release, market release, financial assurance). |
| 8   | Professional                    | You act in a **professional manner** during software development and learning.                                                              | **Professional manner:** You develop software as a team effort according to a prescribed software methodology and following team agreements. You are able to track your work progress and communicate your progress with the team.<br>You actively ask and apply feedback from stakeholders and advise them on the most optimal technical and design (architectural) solutions. You choose and substantiate solutions for a given problem.                       |


## LO1. Web Application

INDIVIDUAL PROJECT

  My individual project application called "Online Library" has the following key features:

1. Extensive Book Repository:
Dive into a vast and diverse collection of books encompassing various genres, from timeless classics to contemporary masterpieces.

3. Personalized Libraries and Bookshelves:
Create your unique reading space by curating personalized libraries. Add your favorite books, organize them into thematic bookshelves, and design your literary world.

4. Social Networking for Readers:
Connect with fellow book lovers, expand your reading circle, and forge meaningful connections. Follow your friends, see their reading lists, and discover new titles through their recommendations.

5. Author Interactions and Insights:
Stay updated with your favorite authors. Follow their profiles, delve into their bibliographies, and receive notifications about their latest releases.

6. Interactive Book Reviews and Discussions:
Share your thoughts through detailed book reviews.

GROUP PROJECT 

  The primary goal of the group project is to streamline the integration and orientation process for new students at Maua by developing a comprehensive web application. The impetus behind this project is the recognition of the challenges faced by incoming students in navigating the activities, locations, and organizations within the university.  
The advantages of this project are multifaceted: it simplifies the onboarding process, enhances student experience. By providing a centralized platform for essential information such as campus activities, interactive maps, and organizational directories, the web application adds significant value to the university’s service offering. It enriches the educational environment by fostering a sense of community and belonging among students. 

In the beginning we spoke with the product owner and he gave us wireframes, explaining how the application should look like.

<img src="./images/Picture2.png" alt="wireframe" style="max-width:100%;max-height:78%" />


  

<br>

### UI prototyping

I have made a lot of UI prototyping, self-studying and researching for my individual project. I researched the most famous online libraries and their UI structure and watched a few explanations on why their UI is user-friendly and effective. 

A prototype of my individual project you can see on page [Requirements and Design](#lo6-requirements-and-design)

I also did some usability tests in school with my peers. I showed my prototype and overrall the feedback was positive including some remarks and suggestions from their side.

After a final discussion with the product owner I finally decided to implement my prototype.

For the group project we had already a chosen UI from the product owner. 

### Software Development
  INDIVIDUAL PROJECT

To have a better understanding of what the most important features are in the project, I conducted a survey, which my classmates filled in, giving opinion by rating the importance of features and giving more ideas, which they believe are important. You can check the answers here: {src}
Based on the answers I prioritized my tasks accordingly.

In the begining, the difficulties i found were that the technologies I wanted to use were foreign to me and I needed to make an extensive research how the project should be structured.

The first thing that I started doing is the main page. I decided to split in half horizontally. In the upper side I have put the books that are recommended to the user based on their searches, saved books, favourite author, etc. The algorythm for this is also a user requirement which is yet to be implemented.

The second half shows the most recently added books in the database.

Regardless of the location of the user throughout the application, he/she can always access the dashboards on the left and right with list of common sections and friend list respectively.
<br>
<img src="./images/Project-images/Screenshot_3.png" alt="save_books_img" style="max-width:100%;max-height:78%" />
<br>

My second task was actually the most important feature which is the option to search and filter books by name, author, genre, etc.

I also implemented in the first weeks of the development, the option to save books in your own library. As well as viewing the details of the book with two buttons with the option to add it to a library or to read it now. If the User hasn't bought the book yet, when clicking on the "Add library" button, a prompt will appear, guiding him/her how to make the purchase. 
<br>
<img src="./images/Project-images/Screenshot_8.png" alt="save_books_img" style="max-width:100%;max-height:78%" />
<br>
The user has, of course, the option to have a view on his/her libraries and to create new ones, which feature is due to be completed. 
<br>
<img src="./images/Project-images/Screenshot_5.png" alt="libraries_img" style="max-width:100%;max-height:78%" />
<br>

I have also started one of the features, which were not as important, but which I decided to be an interesting part of my application. I have made a simple option to view your friends' profile by clicking on their name in the right navigation panel with the friend list and also to view your own profile with some of the details of the user such as 
favourite author and the number of total friends. 
<img src="./images/Project-images/Screenshot_6.png" alt="libraries_img" style="max-width:100%;max-height:78%" />

### Testing in Agile Project [(also check CI/CD)](#lo4-cicd)
I understood that you cannot go to deployment without testing. Ever. That ment that I had to research about different approaches for testing, their advantages and disadvantages. In the Netherlands Tmap HD is the most common agile method of testing. The phases used are:

    1. planning and management, this is where the Master test plan is written and the detailed test plans are started.
    2. preparation
    3. specification
    4. performance
    5. evaluation and completion 
    

GROUP PROJECT 

  I have developed the feature to be able to see an interactive campus map based on the following user story:
  
{
  User Story 3:
  As a student,
  I want access to an interactive campus map
  so that I can locate and familiarize myself with various campus buildings and activities.
  
  Acceptance Criteria:
  i.	The application should include an interactive map displaying the locations of all Mauá's buildings and classrooms. - 34 - 3-4 days
  ii.	Each building on the map should have a clickable button that, when pressed, reveals a list of activities happening in that building. - 55 - 5 days
  iii.	The map should also display the locations of cafeterias and restaurants on the campus. - 21 - 2 days
  Testing: 2 days
  Full estimation: 11 days
}


<img src="./images/Screenshot_3 (4).png" alt="interactive-campus-map" style="max-width:100%;max-height:78%" />
The number of people in the team almost matches the number of features in the projeect, so that everybody can have a part of it. 
More and more features are due to emerge and I am looking forward to do them.



## LO2. Software quality 

The software quality side includes many factors such as:

1. Integrated Development Environments (IDEs):
    Choosing the right IDE for the technologies and languages you will use is crucial for a pleasant and easy work.

2. Version Control Systems:
    Version control (Git) systems helped track the changes in the source code in both my individual project and the group project, collaborate with team members, and maintain a history of code modifications. 


3. Continuous Integration and Continuous Deployment (CI/CD) Tools:
  [CI/CD](#lo4-cicd)}

4. Code Review Tools:
   Code review tools facilitate peer code reviews, allowing developers to collaboratively review code changes, provide feedback, and ensure adherence to coding standards. For this purpouse I used github.
  <img src="./images/Screenshot_3.png" alt="github" style="max-width:100%;max-height:78%" />

6. Performance Testing Tools:
  These tools simulate real-world user loads to assess how the application performs under various conditions, identifying bottlenecks and optimizing code and infrastructure for better performance.
For the front-end side of the applications I used Google's development tool called "Lighthouse".
<img src="./images/IYRw9kB2rqEsnAj48IJ9.avif" alt="lighthouse_image" style="max-width:100%;max-height:78%" />

8. Security Scanning Tools:
  No application can be deployed without identifing vulnerabilities in the application code and configuration. These tools help developers address security issues and improve the overall security posture of the software. I used OWASP
TOP 10 vulnerabilities list to examine my code and to avoid the most common mistakes that happen securitywise in applications.
<img src="./images/Screenshot_4.png" alt="owasp_top10" style="max-width:100%;max-height:78%" />





## LO3. Agile methods

Understanding the Essence of Agile Methodology

When it comes to software development Agile methodology shines as an iterative approach that values collaboration, adaptability and customer feedback. While I possess a comprehension of principles and the various well known methods associated with it my personal approach incorporates a combination of tailored Agile concepts that align with my unique work style.

Agile promotes collaboration, frequent reassessment of project goals and iterative development cycles. These core principles seamlessly resonate with my belief, in adaptability and responsiveness. I fully acknowledge the importance of user feedback and continuous improvements allowing me to progressively enhance projects.

However I don't rigidly adhere to any method alone. Instead I have embraced a customized approach that integrates principles into my workflow. My focus lies in communication channels, constant feedback loops and incremental development. This chosen path empowers me to embrace the essence of Agile while adapting to the requirements and nuances of each project.

In essence my methodology reflects an understanding of principles while also incorporating flexibility, beyond prescribed frameworks. This adaptive mindset ensures that I remain responsive to project needs while fostering an environment to efficient development processes.
<img src="./images/agile-01-scaled.webp" alt="agile_cycle" style="max-width:100%;max-height:78%" />

## LO4. CI/CD

  CI/CD is important because it helps developers work together smoothly and deliver better, bug-free software faster. Continuous Integration catches mistakes early, and Continuous Deployment automates the process of putting the code into action. This means fewer errors, quicker updates, and happier users. Thats why I chose github actions' continuous integration workflow. 
  

<img src="./images/Screenshot_3 (2).png" alt="github-actions" style="max-width:100%;max-height:78%" />
<img src="./images/Screenshot_3 (3).png" alt="github-actions-code" style="max-width:100%;max-height:78%" />

For continuous deployment I am still weighting out the opportunities, but I have plans to stick with deployment to Azure Web App.

Every feature so far I try my best to be always tested properly so that I can keep an eye if everything is working correctly. I developed the tests by using an extention called Diffblue, which eases the work for the tests.

<img src="./images/Screenshot_4 (2).png" alt="diffblue" style="max-width:100%;max-height:78%" />

My next goal in terms of testing is to make a more extensive research on how can I improve my tests. 

## LO5. Cultural differences and ethics

  The cultural difference is mostly outlined in the group project. I am working with people with different nationalities such as from Turkey and Brasil. 
  Having a difference in the time zones of 5 hours, sometimes made it harder for us to cooperate and schedule meetings. Also understanding one's culture might be hard for somebody who hasn't participated in intercultural meetings, but at the end of the day
  if we try to understand each other's viewpoints and opinions, most of the time we can find a common way to deal with the setbacks.
  There are many books, and materials published that try to explain and dive deep into the different cultures and their charecters. Such is the book "Culture and organisations" by Gert Jan Hofstede, which was reccomended to me by my teacher Samuil Angelov,    which I would like to get familiar with soon.

## LO6. Requirements and Design 

### Design choice of my individual project
- Front end: React JS 

- Back end: Java Spring Boot

- Database: MSSQL

### UX design
In order to have a good User Experience (UX), the project has to have a user friendly User Interface (UI) and an intuitive and easy to way of navigating through the application. 
After an extensive research (mentioned in [Requirements and Design](#lo6-requirements-and-design)) I developed my own, which fits the modern etiquette of the front-end side of projects and delivers an easy and understandable way of navigation.
<br>


<img src="./images/ui-diagram.png" alt="UI" style="max-width:100%;max-height:78%" />

## LO7. Business processes
  A business process, also known as a business method or function, is like a set of organized tasks or activities that people or machines do in a specific order. When these tasks are done in a particular sequence, they create a service or product, fulfilling a specific business goal for a customer or group of customers.
  
  Business processes and software applications are closely intertwined in the realm of organizational operations. They relate to each other by Automation of Workflows, Data Management, Communication and Collaboration, Standardization and Consistency,  Decision Support, Adaptability to Change, Customer Interaction, Monitoring and Optimization, Integration of Systems and Regulatory Compliance.
  In the following image I have vizualized the business process in the point of view of the user when he wants to buy a book in my individual project. This business process also describes the automation from the server's side regarding the invoicing. 

<img src="./images/bsiness_process.png" alt="business_process" style="max-width:100%;max-height:78%" />

  In the group project, our applications has the aim to ease teachers and students with managing university-related events. It automizes the process of subscribing/unsubscribing to an event in the system and delivers a quick overview of all events in the different university buildings. It also helps organisers deliver announcements and notifications to people, who have access to the application.
<img src="./images/gp_wireframe.png" alt="gp_wireframe" style="max-width:100%;max-height:78%" />
  


## LO8. Professional  

