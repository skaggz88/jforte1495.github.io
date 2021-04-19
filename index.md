## Jeffrey Forte                     
### B.S. Computer Science
<script src="https://www.hackthebox.eu/badge/293174"></script>

### Professional Assessment
     <text> This project was incredibly insightful and helped show me new avenues on web-development and creating content that is visible on the internet. I utilized github pages over Heroku which is what I am more normally used to. This didn’t come without challenges, as there seems to be problems with my database connection. This could be for one of a few reasons. One in particular is that github pages is good for hosting content without a backend. My application does have a backend server which makes Heroku a better hosting site because it will host the server as well. 
    The fact that I know this information now shows how far I have come in the last eight weeks. My final product may not look like much, however it has come a long way from an application that simply stores information locally. This connects to a MySQL database. There was some front-end color schemes that got lost in translation, but this is to be expected and can be remedied easily.
    Github is such an invaluable tool when it comes to collaborating in a team environment. It allows developers to have a single source to push and pull from and work within providing a hub (no pun intended) where they can centralize their work. This can even be used to communicate progress to stakeholders as they can easily be given access to the project repositories. 
    Again, the front-end of my project may not look like much but that is because I am not exactly too sharp on front-end development. I pride myself on the back-end and I have created a RESTful API and a simple server for my To-Do application that utilizes MySQL database hosted on the cloud. I demonstrated my ability to create good code that is readable to others in a collaborative environment. One thing that I would say I need to focus more on while moving forward is security. My application is functioning, now I need to harden the server and the system itself to make it immune to code injections and other vulnerabilities.
    Since I chose one artifact, it is easy to see how it fits together. I started with a simple application that had a simple .html file for the front end. I reconfigured the entire application to have a frontend, and a backend. Within the backend is a simple server that queries a database. Altogether, this application demonstrates the construction of a basic, yet functioning web application barring the cloud database connectivity. For proof of concept, a local database can be used instead to demonstrate functionality. </text>





  
### Code Review
video: https://www.youtube.com/embed/5vAhP43ngRY 


### Software Engineering/Design
	The project that I have chosen is a simple “to-do” list. This is a common starting project for programmers. It is an especially common web development program. I have been dabbling in web development for a while now. I have made a couple of websites, but I want to make a web-based platform. This project was created a few months ago with the intentions of becoming a Remote Work Platform (RWP). 
	I chose this piece for my work because it demonstrates a transformation of a simple programming task into a full-blown software project. This project will be worked on even after this project is over. This course will only cover a few specific enhancements that are crucial to the development of this platform. This includes configuring a server, database storage, and applying coding best practices to the platform.
	For the first assignment, I had to restructure the entire project. I had to add a frontend and backend folder. I had to configure a web-server in the backend. This will eventually include database connectivity. The frontend runs on port 3000 while the server runs on port 5000. Most of the styling was preserved, however, the SASS functionality was lost. This will have to be reconfigured but this out of the scope of this course. 
	This part of the project was pretty straight forward and easy. There was some frustration with figuring out what should go in what specific modules. It is also hard to build this platform without the database functionality. The program saves to “local storage” which doesn’t exist when it is active on the web. This means that all of the functions will have to be modified to properly query an SQL Database. While this created some frustrations, it is to be expected. I also ran into troubles with github. I misconfigured my repository and I ended up creating merge conflicts so now I have recreate the repository. 





### Data Structures and Algorithms

        This was by far the toughest part of the project for me. I have never worked with MySQL in a Node application before. It was pretty tough. I originally created my application the same way I have made others with MongoDB. The SQL queries, however, run differently and have a different syntax. This involved having to almost completely overhaul my application. This is okay, however as the application now functions properly. It connects to a database as it is supposed to. The only thing that I seemed to have lost in this is the front end and graphics. This should be pretty easy to fix 
	I have gained invaluable experience in working with SQL and NodeJS. These are both very powerful tools that are widely used in the world of web development. One thing that I could look into more is to further secure my application to prevent code/SQL injections from happening. The actual database connection was not as big of a problem as was actually creating the queries. Now that I have overcome this obstacle, I can move forward with other things such as unit testing each individual function as well. Unit testing is an imperative part of professional code. 



### Databases
        The project that I have chosen is a simple “to-do” list. This is a common starting project for programmers. It is an especially common web development program. I have been dabbling in web development for a while now. I have made a couple of websites, but I want to make a web-based platform. This project was created a few months ago with the intentions of becoming a Remote Work Platform (RWP). 
         I chose this piece for my work because it demonstrates a transformation of a simple programming task into a full-blown software project. This project will be worked on even after this project is over. This course will only cover a few specific enhancements that are crucial to the development of this platform. This includes configuring a server, database storage, and applying coding best practices to the platform.
        This part of the assignment involved implementing a database connection. This is the big leap from the current state of this application as the original application saved all information to local storage. This is fine and good for a desktop application, but this will not work for a web application. I chose to use MySQL as the database of choice. This database is hosted on the google cloud platform and utilizes the database “wrk_rm_tables”. This is where the information for all of the actual “to-do’s” will be stored.
        To implement the connection, I had to add a “db.js” module into the back end. The code as well as the output tests this database connection and throws an error if the connection is not made. To further test the connection, a sample query was made. This is demonstrative and will be removed from the final product. 



Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)



For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/jforte1495/jforte1495.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Contact
jforte142@gmail.com


