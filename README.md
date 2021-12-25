# Collaborated-Projects
The following ReadMe contains detailed information on the projects I have collaborated on.


## Community Shelter and Food Pantry Logger

For our Database Systems project, my colleague and I created a webapp filled with resources for people in underserved communities. We gathered data from Google and created our own database from scratch. Our app consists of six services: food pantries, clothing banks, soup kitchens, medical assistance services, daycare services, and homeless shelters. Each of those services has the following information stored. Users have the ability to find services based on its city, county and zip code, the managers at each service, and the customers that are subscribed to each service.

We didn't want regular users to be able to make major changes to our database, so we created the role of "admin". The purpose of the admin is to edit/delete managers or users. That way, changes made to the database are secure. Currently the only admins are my colleague and me.

We used HTML and CSS to create the pages and Flask (a Python library) to navigate through them. Our database is handled through SQLite, which allows us to easily make changes to our database.

Visit our website, https://nightraven.pythonanywhere.com/, to view the full capabilities of our project. Any related diagrams (Entity Relationship Diagram, Relational Schema, and Use-Case Diagram) can be found in our slides embedded in the About page.

The following YouTube video will show a demo of our app: https://youtu.be/3Esg5ZAZu18

Main GitHub repository: https://github.com/alejandrohsanchez/Community-Shelter-and-Food-Pantry-Data-Logger


## OpenCV Cow Detection

Diamond J. Dairy is a modern dairy farm in Merced that utilizes an automated, state-of-the-art soaker system to keep their cows cool and maximize dairy production. To achieve this, they periodically spray their cows with water whenever the temperature reaches a certain range. However, with the way their soaker control system is set up, sometimes the water will spray the pen even when there are no cows present. This leads to a significant water waste.

The soaker control system determines when water should be sprayed. It has a built in temperature tracker that measures the thermal heat index. When the temperature reaches a certain point, the water in the pipe runs through the first pen for a minute, shuts off, then moves on to the next pen. Once the water runs through all of the pens, the system will shut off for 10 minutes and cool the cows through evaporative cooling, which is the conversion of water into vapor using the thermal energy in the air, resulting in a lower air temperature. This process repeats again with a 2-minute shut-off period for as long as the temperature stays within that range.

Each barn has two pens and each pen has a long pipe with multiple nozzles for the water to spray. Suppose there are no cows in a pen when the system turns on. The barn is divided into 15 sections, each separated by a supporting beam. Each section has roughly 4 nozzles, so there are a total of 60 nozzles per pen. Each gallon sprays about 1.2 - 2 gallons of water per minute. That means that there is at least 72 gallons of water wasted in one pen in the first cycle alone.

My team and I devised a solution to save water without compromising the comfort of the farm’s cows. We installed a camera at the top of a barn so that we could view both pens at the same time. This video feed is then saved in a Raspberry Pi, where it is stored in an SD Card. The recorded video feed will then be fed through our program, where we use OpenCV and YOLO weights to detect cows.

In the future, we would like to have our program work with the soaker control system to move to the next pen where there are no cows available.

The following YouTube video will show a demo of our project: https://youtu.be/VbfIQHSTxx8

Main GitHub repository: https://github.com/shiv248/OpenCV-Cow-Detection


## Task Manager

My team and I created a collaborative task manager. Every board created has a project name and a session password. This unique set of information is used by other users to join the same board. Within each board, users can create tasks and mark them as "In-Progress" or "Completed". They also have the option to write notes on the bottom or clear all of the tasks.

In future iterations, we would like to have users input the usernames of the people that are allowed in a board to make the app more secure. Any time a user logs in, the information entered will be checked with our existing database. If the user is under the session they specified, then they will be allowed to enter the board. If not, then an error message would pop up.

The following YouTube video will show a demo of our project: https://youtu.be/ZRP6-l7v8cg

Main GitHub repository: https://github.com/aditikisara/Exploratory-Computing-Projects/tree/main/CSE106-Final
