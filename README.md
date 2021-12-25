# Collaborated-Projects
Here is all of the information on the projects I have collaborated on and are not in my profile.

-------------------------------------------------------------------------------

Community Shelter and Food Pantry Logger

For our Database Systems project, my colleague and I created a webapp filled with resources for people in underserved communities. We gathered data from Google and created our own database from scratch. Our app consists of six services: food pantries, clothing banks, soup kitchens, medical assistance services, daycare services, and homeless shelters. Each of those services has the following information stored. Users have the ability to find services based on its city, county and zip code, the managers at each service, and the customers that are subscribed to each service.

We didn't want regular users to be able to make major changes to our database, so we created the role of "admin". The purpose of the admin is to edit/delete managers or users. That way, changes made to the database are secure. Currently the only admins are my colleague and me.

Visit our website, https://nightraven.pythonanywhere.com/, to view the full capabilities of our project. Any related diagrams (Entity Relationship Diagram, Relational Schema, and Use-Case Diagram) can be found in our slides embedded in the About page.

-------------------------------------------------------------------------------

OpenCV Cow Detection

Diamond J. Dairy is a modern dairy farm in Merced that utilizes an automated, state-of-the-art soaker system to keep their cows cool and maximize dairy production. To achieve this, they periodically spray their cows with water whenever the temperature reaches a certain range. However, with the way their soaker control system is set up, sometimes the water will spray the pen even when there are no cows present. This leads to a significant water waste.

To combat this, my team and I devised a solution to save water without compromising the comfort of the farm’s cows. We installed a camera at the top of a barn so that we could view both pens at the same time. This video feed is then saved in a Raspberry Pi, where it is stored in an SD Card. The recorded video feed will then be fed through our program, where we use OpenCV and YOLO weights to detect cows.

In the future, we would like to have our program work with the soaker control system to move to the next pen where there are no cows available.
