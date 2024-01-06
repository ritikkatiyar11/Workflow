# A

**MINI PROJECT**** REPORT**

ON

# STUDENT STUDY RESOURCES APPLICATION USING PYTHON & DJANGO

MINIPROJECT LAB(KCS-554)

# Submittedby:

**Ritik Katiyar** **(2000970130094)**

**Prajusha Kundu (2000970130077)**

# Prateek Baranwal (2000970130082)

**Under the supervision of:**** Ms. Raunak ****Sulekh**

![](RackMultipart20240106-1-oolkok_html_f3482e650fa73760.jpg)

# Session 2022-23

# Department ofInformation Technology

**Galgotias College of Engineering and Technology**** Greater ****Noida**

# ACKNOWLEDGEMENT

WewanttogivespecialthankstoourMiniProjectcoordinator, **Ms.**** Raunak ****Sulekh** for the timely advice and valuable guidance during designing andimplementationofthis projectwork.

We also want to express our sincere thanks and gratitude to **Dr. Sanjeev**** Kumar Singh, Head of Department (HOD)**, and Information TechnologyDepartmentforprovidinguswiththefacilitiesandforalltheencouragementand support.

Finally,weexpressoursincerethankstoallstaffmembersinthedepartmentofInformationTechnologybranch forall the support and cooperation.

**Ritik Katiyar**

**(2000970130094)**

**Prajusha Kundu**

**(2000970130077)**

**Prateek Baranwal**

**(2000970130082)**

**TABLE**** OF CONTENTS**

#

[1.INTRODUCTION 7](#_Toc120173249)

[2.LITERATUREREVIEW 8](#_Toc120173250)

[2.1ProblemStatement 9](#_Toc120173251)

[2.1.1Statement 9](#_Toc120173252)

[2.1.2ProblemSolution 9](#_Toc120173253)

[3.IMPLEMENTATION 9](#_Toc120173257)

[3.1ProjectScopeandFeatures 9](#_Toc120173258)

[3.2MethodologyandToolsUsed 9](#_Toc120173259)

[3.2.1OurApproach 9](#_Toc120173260)

[3.2.2DescriptionofModules 10](#_Toc120173261)

[DjangoHTML Modules– 10](#_Toc120173262)

[Python Virtual Environment– 10](#_Toc120173263)

[API Module – 10](#_Toc120173264)

[CRISPY Forms Module – 11](#_Toc120173265)

[Integration – 11](#_Toc120173268)

[3.2.3UsedTechnologies 11](#_Toc120173269)

[3.2.3.1Web Application Development 11](#_Toc120173270)

[3.2.3.2Python 12](#_Toc120173271)

[3.2.3.3HTML 12](#_Toc120173272)

[3.2.3.4VisualStudioCode 13](#_Toc120173273)

[3.2.3.5CSS 13](#_Toc120173274)

[3.2.3.6Django 13](#_Toc120173275)

[3.2.3.7Bootstrap 14](#_Toc120173276)

[3.3Implementation 15](#_Toc120173277)

[3.3.1EnvironmentSetup 15](#_Toc120173279)

[3.3.1.1Django-Installation 15](#_Toc120173281)

[3.3.1.2API-Installation 16](#_Toc120173282)

[a.You Tube- 16](#_Toc120173283)

[b.Wikipedia- 16](#_Toc120173287)

[c.Google books- 16](#_Toc120173290)

[3.3.2Project Functional Modules 17](#_Toc120173293)

[3.3.3Logical Implementation 18](#_Toc120173294)

[4.RESULT/SNAPSHOTS 21](#_Toc120173296)

[5. CONCLUSIONANDFUTURE SCOPE 26](#_Toc120173307)

[6.REFERENCES 27](#_Toc120173308)

# LIST OFFIGURES

**Figure**** 3.1.** Backend frameworks Diagram

**Figure**** 3.2.** Frontend Development

**Figure**** 3.3.** Django Official Logo

**Figure**** 3.4.** You Tube API

**Figure 3.5.** Wikipedia API

**Figure 3.6.** Google Books API

**Figure**** 3.7.** Template Files

**Figure 3.8.** Defining the logical functions coding.

**Figure 3.9.** All imported Libraries

**Figure 3.10.** Declaring classes for forms

**Figure**** 3.11.** CSS filefor styling

**Figure**** 4.1.** ScreenshotofLogin Page

**Figure**** 4.2.** ScreenshotofHome Page

**Figure**** 4.3.** Screenshotof Profile Page

**Figure 4.4.** Screenshot of Notes Page

**Figure**** 4.5.** ScreenshotofDictionary Page

**Figure**** 4.6.** ScreenshotofBooks Page

**Figure**** 4.7.** Screenshotof YouTube Page

**Figure 4.8.** Screenshot of Wikipedia Page

**Figure**** 4.9.** ScreenshotofLogout Page

# ABSTRACT

In the recent years, there has been increase in joining of new technologies into educational management. Technological Implementations in the field of Academics has helped Students as well as Professionals in very important ways. The availability of all educational resources helps the students a lot in their educational life.

There are a lot of work and activities performed by students which take maximum time in searching and implementing the task. Everyone wants to do maximum work in lesser time and in the easiest way. This project provides a lot of features like Notes, a Wikipedia page, a Todo list, a Dictionary, Books, and many more.

The project is based on a web-based application. There are many technologies used to build this project like python, and Django for the backend part and the frontend part is used for making the website attractive with the help of HTML, CSS, and bootstrap. This web-based application is designed for the school/college students to carry out an effective way of learning in a very smooth manner. The project developed is highly efficient, user-friendly and simple.

1.
# INTRODUCTION

#

In this era of digitalization, the availability of different resources on different digital devices is making our lives easy and convenient. In the field of academics too, there are many educational websites that share educational resources like short notes, video lectures, presentations and books etc. Technology has enhanced the learning experience for students. Although the basic building block of education is still reading, writing, and arithmetic, there is no doubt that today's students will also need a wider education in order to be effective contributors in the future.

Corporate companies acquire new technology day by day to solve social problems with their skills. The students learning in schools and colleges work on projects and different skills-based activities for which the content should be on various platforms and takes a lot of time to search and work on it.

In this project, we are trying to make a web application on which most of the resources are available in a single platform and easy to access for the students. This project provides a lot of features like Notes, a Wikipedia page[10], a Todo list, a Dictionary, Books, and many more. There are many technologies used to build this project like python, and Django for the backend part and the frontend part is used for making the website attractive with the help of HTML[6], CSS, and bootstrap[4].

This application helps the students to provide all the study material like searching with Wikipedia and YouTube, Conversion scale, Notes, and Different types of academic books.

1.
# LITERATUREREVIEW

#

Online learning refers to instruction that is delivered electronically through various

multimedia and internet platforms and applications. Various websites and research papers

have been developed keeping the idea of educational resource sharing and its importance

in mind. Few of them are listed here:

**1. Used Books Factory:**

It is an online platform to sell old books of different categories.[12]

**2. Vioric-Torri, C. & Alexandrache, C. (2012):**

The study reflects how educational technology influences the learning styles of students and how to form and develop the competences of learning in the new generations.[13]

**3. Tutorials Point:**

The website provides tutorials on different topics related to computer science and technology. Provides pdf notes for the same and also provides guidance for competitive exams.[13]

**4. The Physics Classroom:**

For PDF notes and tutorials related to the various fields of Physics.[14]

**5. Kelly, L., & Breault, K. (2006):**

The objective of the research project was to provide the Australian Museum with guidance on how to best develop a website that meets the needs of students and teachers in the primary and secondary levels across a range of curriculum areas. General objectives were to gain insights into how students and teachers are using the internet and what they are looking for when they access websites.[15]

**6. Aglasem:**

Online Portal that provides previous year question papers and answer keys related to different competitive exams and some universities‟ semester papers.

**7.Books:**

Used google books for books. Google Scholar, one-search, library Databases Searches everything on the internet, both scholarly and non-scholarly.[7]

  1.
# ProblemStatement

    1.
# Statement

There are on average 30 million students enrolling in UG or PG courses. Irrespective of their organization they have to do a lot of Paper and Research work. So there is always a hustle of resources going one page to another on their computers. In order to help we have built an application that will provide the maximum resources on a single click increasing their productivity.

#

    1.
# ProblemSolution

#

# Our project is solving the above mentioned problem by using modern technology. With the help of Django and Python our intention is build a universal recourse application that will be a single stop destination for a students need.

# This application in this version will be holding Notes, Todos, dictionary, ,YouTube, Wikipedia like tools that are used frequently on a few clicks .

# Students can also have an eye on their pending work on one go. Hence,This application can be very useful if anyone wanted to increase their work efficiency specially in academics field.

1.
# IMPLEMENTATION

  1.
# ProjectScopeandFeatures

1. This project should provide the various study material in just one single platform.
2. Itfacilitates the various sections of functions like Wikipedia, Todo List, YouTube search, Conversion Scale and many more.
3. Itprovidesa various workstation that helps a lot for students.
4. Thisproject canbe extended by adding features and increasing the size of memory of the application.
5. The material should be provided at maximum level by enhancing the features of the functionality.

  1.
# MethodologyandToolsUsed

    1.
# OurApproach

First, we start with building the basic wireframe of our project on paper. In the wireframing of the project we have discussed all the necessary inter-connections and after mapping all the things. After making roadmap of our project the next step was to analysis of resource needed, and figuring out what major challenges can come in front of us.

The second step was to accumulate the resources and necessary documentation for the project. We have to go through multiple tutorials and project reports that can be associated with our project.

Based on the functionality of our project we can distribute the modules in modules like base, home, homework, login, Todo, register, YouTube, Wikipedia, conversion.

At this stage we have started our learning phase for our project. Due to structured distribution of the project work everyone in the group has the clarity that what an individual needs to learn in accordance to contribute in the work.

After these steps with constant communication all of us delivered their work before time and then we started the process of integrating modules and components of the Project.

We also worked on the presentation of our project as we use beautification frameworks like Bootstrap and Tail-wind, Font Awesome. These platforms helped us to improving usability and impression of our Project.

Finally after weeks of team-work paid off and our project was in working then we started testing our project from the point of view of user. In the later part we fixed the glitches and errors during implementation part and our project was ready with the scope of scaling up and further improvements in the fast pace world of technologies.

#

    1.
# DescriptionofModules

-
## DjangoHTML Modules–

In our project we have 14 functional modules that are written in Django html format to show our content dynamically and apply necessary constraints to deliver our functions. We also used Django data tables to store the needed data in the database in forms of tables.[1]

-
## Python Virtual Environment–

A virtual environment is a tool that helps to keep dependencies required by different projects separate by creating isolated python virtual environments for them. This is one of the most important tools that most of the Python developers use. It also gives us the administrative power to create a super-user

And manage our project.[2]

-
## API Module –

For some of our features we have integrated some of the API we have used these following API's.[7],[9],[10]

- Google Books
- Python Youtube Search
- Wikipedia

-
## CRISPY Forms Module –

## For better look and feel of our forms in the project we have imported crispy forms

## in Django that formats our data with the help of context given.[3]

##

-
## Integration –

For implementing our API's in our project we have to make the class nodes in python to save data and for the integration of all the modules we have to make pythons functions and connect it to the structural body written in html.

    1.
# UsedTechnologies

The technologies are used to develop this web application are described following:

      1.
# Web Application Development

Web application development is a process of developing software applications that can run on websites. Even though web application development follows the software development process, the technology and the architecture used for it is quite different. The software application that runs on a personal computer (PC) might not depend on the internet in contrast to the web application that depends upon the remote servers. The web applications and the client-server technology have come quite far in comparison to the simple standalone phone book app made by Tim Berners-Lee in 1989.

Nowadays, web application comes in different shapes and sizes such as static, dynamic, content management system, e-commerce, and gaming to live content sharing portals. Commonly shared technology of applications mentioned above types is the backend and frontend technology. Backend development deals with the logical side of the web application. It mainly concerns the programming languages, core architecture and the logics. Those logics are mainly written in programming languages that can run on computer servers. It also influences how the data is stored, accessed and served from the servers. In Figure 1 below the green dotted line shows the backend part of the application, which consists of server-side scripts, frameworks, database and APIs.

![](RackMultipart20240106-1-oolkok_html_28c00559daadfbdc.png)

**Figure 3.1: Back-end frameworks Diagram**

On the other hand, frontend development is mostly concerned with the aesthetic and the content displaying part, which is also known as client-side development. One of its difficult challenges is to be able to show the material in the different types of devices and browser. Many devices have its own Software Development Kit (SDK) which should be followed to serve the same content that is served in the browser. Website design, usability and user-friendliness are the essential factors that are addressed during the development. The figure below is an example of how the frontend side of an application works.

![](RackMultipart20240106-1-oolkok_html_3818caf81985e630.png)

**Figure 3.2: Front-end Development**

      1.
# Python

Founded in December 1989 by Guido Van, Python is one of the most popular high-level general programming language languages . It is a dynamically typed language, often called duck typing in software engineering. It is an interpreted language; hence, it does not require any separate compiling time, but rather it is compiled to byte code and executed instantaneously. One of the reasons for Python's popularity is its readability. Because the readable code is a dream for a software engineer, it is important because one should be able to understand the importance of the code regardless of the author. The code readability indeed depends upon the author. But Python steps ahead on this game with its very linguistic 4 type programming language. It has also been touted as the easy way to learn the language. It will help programmers reduce the time spent on learning another programming language.[5]

      1.
# HTML

HTML (Hypertext Mark-up Language) is the standard mark-up languages for the Web pages. It was created by Berners – Lee in the year 1989. It is a standard which describes the structure of web pages in which series of elements co-exists. Those elements then, instructs the browser how to display the content. These elements are represented by tags such as heading, paragraph, table, section etc. It is one of two core technologies required to build a dynamic or static web page. It is a skeleton or the layout of the web page.

HTML has wide ranges of support for the contents from text to spreadsheets, video clips, animations pictures. The web page often called as a document in a technical term, the document type defined at the beginning of the page determines what type of document it is and how it should be taken by the web browser while rendering it. Being the essential part of the world wide web, it has gone through the various phases of development from 1991 till date, while HTML being the initial version and HTML5 being the latest one respectively.[6]

      1.
# VisualStudioCode

Visual Studio Code is a lightweight but powerful source code editor which runs onyourdesktopandisavailableforWindows,macOSandLinux.Itcomeswithbuilt-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem ofextensions for other languages (such as C++, C#, Java, Python, PHP, Go) andruntimes(suchas .NETand Unity).

AllourappprogrammingisdoneonVSCodeasitmakescodingeasyandcomeswitha lot of extension supportsand features.[8]

      1.
# CSS

W3C (Worldwide Web Consortium), CSS (Cascading Style Sheets) defines CSS as the language describing the presentation of Web pages, colors, fonts and the layouts.CSS allows one to stylize the HTML document according to their need. It contains a set of style rules with which the web pages could be rendered. Not only to that, but it also helps render the page responsively on the devices of different shapes and sizes.

There are two style formatting rules for the CSS. One is called inline styling, and another one is external styling. In the external styling, however, the styling rule sits in a different file. This could then be linked by a unique tag in the HTML document. The cascading part of the CSS refers to how the rules are applied to the HTML elements. The HTML 8 document is styled hierarchically. Therefore, it is the responsibility of CSS to find the precedence of the style rules, accordingly, ultimately establishing a cascading effect.

      1.
# Django

Django was introduced in 2003 when Adrian Holovaty and Simon Willison began using Python to build applications. The motivation for developing Django was the need to get applications done on a schedule of days or even hours. Two years after starting to create a web application framework, in 2005, it was released as open source. Today, 10 Django has several tens of thousands of users and development figures. [The Django Book 2009a.]

![](RackMultipart20240106-1-oolkok_html_5fac5f1785f82904.png)

**Figure 3.3: Django Official Logo**

Because Django is a web application framework based on Python, you need Python to use it. Supported versions of Python are 2.6.5 and 2.7, but Django also offers experimental support from version 3.2.3 to version 3.3. Python comes with a lightweight testing server, but for proper use, the upcoming Django-based site needs an Apache server and a mod\_wsg module. Django officially supports PostgreSQL, MySQL, Oracle and SQLite databases.

Django also loosely applies MVC architecture. It becomes evident in Django, parts of the applications you created. In essence, models.py, views.py and urls.py, and the HTML template.Models.py contains a description of the information and provides functions for creating, retrieving, updating and deleting the data. View.py transmits the site content HTML template. The role of the urls.py file, in turn, is to configure which view file is called. With this structure and file functions, editing an application does not require editing many files, which in turn saves time.[1]

      1.
# Bootstrap

Bootstrap is a massive collection of reusable and versatile pieces of code which page or app to detect the visitor's screen size and orientation and automatically adapt the display accordingly; the mobile first approach assumes that smartphones, tablets and task-specific Mobile apps are employees' primary tools for getting work done and addresses the requirements of those technologies in design. Bootstrap includes user interface components, layouts and JS tools along with the framework for implementation. The software is available precompiled or as source code. Mark Otto and Jacob Thornton developed Bootstrap at Twitter as a means of improving the consistency of tools used on the site and reducing maintenance. The software was formerly known as Twitter Blueprint and is sometimes referred to as Twitter Bootstrap. In computers, the word bootstrap means to boot: to load a program into a computer using a much smaller initial program to load in the desired program (which is usually an operating system). In the physical world, a bootstrap is a small strap or loop at the back of a leather boot that enables you to pull the entire boot on and in general usage, bootstrapping is the leveraging of a small initial effort into something larger and more significant. There is also a common expression, "pulling yourself up by your own bootstraps," meaning to leverage yourself to success from a small beginning.are written in CSS, HTML and JavaScript. Since it is also a framework, all the foundations are already laid for responsive web development, and all developers have to do is insert the code into the pre-defined grid system. There are some free tools that come as part of the package, which permit designers to build the more common website interface components, as well as more responsive ones, adding to the versatility of the framework. Responsive design makes it possible for a web [4]

**3.2.3.8 Hardware & Software Requirement**

- **Hardware Requirements**

1. Camera, Microphone and speakers
2. A desktop / laptop
3. Minimum 512 MB RAM
4. Internet Connectivity
5. Pentium-pro processor or later

- **Software Requirements**

        1. Windows 8 or higher
        2. PyCharm/Jupiter as Python interpreter with python 3.8 or higher version
        3. Django

  1.
# Implementation

# Our project has these following steps for implementation process.

    1.
# EnvironmentSetup

# We will start by setting up our project folder and establishing python virtual environment that gives isolated space for any project. We have these commands to activate virtual Environment.[2]

#

1. pip install virtualenv
2. python\<version\> -m venv \<virtual-environment-name\>
3. source env/bin/activate

#

      1.
# Django-Installation

Django is used as a tool to build web applications quicker by writing backend of the web-application in Python. We use command prompt commands to install the Django in our system in a specific folder.[1]

First we open that specific folder in Command Prompt.

Then we have to use this command line to install Django.

**...\\>** py -m pip install Django

      1.
# API-Installation

1.
# You Tube-

# Gives the search result for a keyword.[9]

# ![](RackMultipart20240106-1-oolkok_html_8e73a9fe014785c4.png)

# Figure 3.4: You Tube API

1.
# Wikipedia-

# I ![](RackMultipart20240106-1-oolkok_html_615e4041ab1fd89a.png) t will give all the information and summary about the topic.[10]

# Figure 3.5: Wikipedia API

1.
# Google books-

# Provides the books for a search query.

# ![](RackMultipart20240106-1-oolkok_html_749551573846dd3d.png)

**Figure 3.6: Google Books API**

    1.
# Project Functional Modules

These are the Functional Modules that works as a Template file for the logic and data Tables to work on these are divided into the following parts.

- Base
- Books
- Conversion
- Dictionary
- Youtube
- Todo
- Wiki
- Login logout
- Authentication
- Notes and Homework
- Profile and Register

![](RackMultipart20240106-1-oolkok_html_c19a0bf8f5f68f9b.png)

**Figure 3.7:**** Template Files**

    1.
# Logical Implementation

      1.
# Views.py

Views.py file contains all the imported modules. In this file we have to write functions and their logical code to execute our features. We also decide syntax to fetch data from the API and URLs. We have to structure how the fetched data will be used.

![](RackMultipart20240106-1-oolkok_html_8244100c78385bd1.png)

**Figure**  **3.8:**  **Defining the logical functions and coding.**

![](RackMultipart20240106-1-oolkok_html_b3aa73ba96434ca1.png)

**Figure**  **3.9:**** All imported libraries.**

      1. **Forms.py-**

ThisProject uses a lot of forms elements for that we have forms.py to make input output structures of forms and models them.

![](RackMultipart20240106-1-oolkok_html_e8a6b51663eb1089.png)

**Figure**  **3.10:**** Declaring classes for forms.**

**3.3.3.3 Urls.py-**

We have to specify all the functions and their Template file path in this file so everything is accessible.

![](RackMultipart20240106-1-oolkok_html_47cfa204cc88e9f5.png)

![](RackMultipart20240106-1-oolkok_html_1d9887df0378bd8.png)

**Figure**  **3.11**** CSS file for styling**

1.
# RESULT/SNAPSHOTS

#

  1.
# Login:

# ![](RackMultipart20240106-1-oolkok_html_4749c7ac587b1e84.png)

#

# Figure 4.1 Screenshot of Login Page

#

  1.
# Home:

# ![](RackMultipart20240106-1-oolkok_html_7d25cff3e25ba25f.png)

# Figure 4.2 Screenshot of Home Page

  1. **Profile:**

![](RackMultipart20240106-1-oolkok_html_6d59dad56324debc.png)

# Figure 4.3 Screenshot of Profile Page

  1. **Notes:**

![](RackMultipart20240106-1-oolkok_html_66c02e5669f3df06.png)

**Figure 4.4 Screenshot of Notes Page**

  1. **Dictionary:**

![](RackMultipart20240106-1-oolkok_html_9a4a19cae4db346.png)

#

# Figure 4.5 Screenshot of Dictionary Page

  1. **Books:**

![](RackMultipart20240106-1-oolkok_html_e527581d3269ce52.png)

**Figure 4.6 Screenshot of Login Page**

  1. **Youtube:**

![](RackMultipart20240106-1-oolkok_html_2155e823f454a10.png)

# Figure 4.7 Screenshot of You Tube Page

  1. **Wikipedia:**

![](RackMultipart20240106-1-oolkok_html_3fab2e658d51ff3f.png)

# Figure 4.8 Screenshot of Wikipedia Page

  1. **Logout:**

![](RackMultipart20240106-1-oolkok_html_5ba892aa63776ee8.png)

**Figure 4.9 Screenshot of Logout Page**

# 5. CONCLUSIONANDFUTURE SCOPE

This project has been done to research the concept of academics as well as skill development process to avoid material search and loss of time during study. This web application has been developed to solve the problem of time loss in searching the content by providing all the activities like Wikipedia, YouTube, Conversion Scale, and Various types of books that can help in academics as well as enhance the knowledge of the user.

While developing this project all the suitable parameters are to be taken by our team so that this application will be user friendly. In this application, various features provide a better interface to the user for reliability, and reusability, and working on it. The current model of this application may face some issues like memory shortage and a limited no of books and notes but it only depends on the number of users active at the same time.

We are trying to provide a web-based application that helps student to find all the helpful study resources in just one click. There are many technologies used to build this project like python, and Django for the backend part and the frontend part is used for making the website attractive with the help of HTML, CSS, and bootstrap.

In the conclusion, our team is trying to provide a useful application based on our knowledge and skills but it needs some good features and upgradation which can be done by future developers to provide better enhancement and make this application more effective for the users.

# 6.REFERENCES

1. Django

[https://docs.djangoproject.com/en/4.1/](https://docs.djangoproject.com/en/4.1/%20)

1. Python virtual Env

[https://docs.python.org/3/library/venv.html](https://docs.python.org/3/library/venv.html)

1. Crispy Forms

[https://django-crispy-forms.readthedocs.io/en/latest/](https://django-crispy-forms.readthedocs.io/en/latest/)

1. Bootstrap

[https://getbootstrap.com/docs/4.3/getting-started/introduction/](https://getbootstrap.com/docs/4.3/getting-started/introduction/)

1. Python[https://docs.python.org/3/tutorial/index.html](https://docs.python.org/3/tutorial/index.html)

1. HTML [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

1. Google Books [https://developers.google.com/books/docs/v1/getting\_started](https://developers.google.com/books/docs/v1/getting_started)

1. Visual Studio Code[https://code.visualstudio.com/](https://code.visualstudio.com/)

1. Youtube API [https://pypi.org/project/youtube-search-python/](https://pypi.org/project/youtube-search-python/)

1. Wikipedia [https://pypi.org/project/wikipedia/](https://pypi.org/project/wikipedia/)

1. SQLlite [https://docs.python.org/3/library/sqlite3.html](https://docs.python.org/3/library/sqlite3.html)

[12] Buy Second Hand Books, Old Books, Used Books Online in India. (n.d.). Retrieved [https://www.usedbooksfactory.com/](https://www.usedbooksfactory.com/)

[13] Viorica-Torii, C., & Carmen, A. (2013). The Impact of Educational Technology on the Learning Styles of Students. Procedia-Social and Behavioural Sciences, 851-855. About Company. (n.d.). Retrieved from

[https://www.tutorialspoint.com/index.htm](https://www.tutorialspoint.com/index.htm)

[14] The Physics Classroom. (n.d.). Retrieved from

[https://www.physicsclassroom.com/.](https://www.physicsclassroom.com/)

[15] Kelly, L., & Breault, K. (2006). Developing Educational Websites: Investigating Internet Use by Students and Teachers. In Proceedings of Thinking, Evaluating, Rethinking, ICOM-CECA Conference, Rome.
