#Phase 2: Narowing down the Application#

### Project Members ###
StdID | Name
------------ | -------------
**63120** | **Syed Amir Ali Rizvi**
63173 | Muhammad zuhaib
62682 | Syed Ali Muzaffar Rizvi

##Task Finalization##

At initial we are going to implement 2 tasks of our application namely User Friendly Interface & Available For Both Wildlife Status these tasks include the ease for the user in a sense that user can easily search the both animal and plants by just capture the image of that and application is unique in that it will provide auto-detection using an image search, allow quick picture taking, provide a non-technical user-friendly interface, and promote retention through the use of gamification techniques

##Need Finding##

Mobile wildlife identification applications and websites currently exist. However, these applications are limited by their features such as:

● very complicated and technical interface,
● requiring the user to identify observations using scientific guides, or
● only providing resources for identifying certain classes, such as flowers, birds, amphibians.

One mobile and web application, iNaturalist (http://www.inaturalist.org/), provides users the ability to log observations using latitude/longitude, time and date of observation, and user entered species name. This requires the user to identify the species observed limiting its application to audiences with advanced knowledge on wildlife and plant life. Also, the design of the application makes it more suitable for less time-constrained identifications and uploads. WildObs (http://wildobs.com/) is a mobile application that allows users to share observations via text-based logs with or without photo, learn new information about species, and view other user's’ logs. However, this application relies on the user’s ability to identify wildlife or plants and doesn’t provide any other interactions between user’s besides viewing galleries. Project Noah (http://www.projectnoah.org/) is another mobile application for wildlife and plant observations that allows a user to upload pictures of flora and fauna for identification through field guides.

This application includes the ability to join missions and earn patches, which provides a gamification aspect. However, it does not provide any identification services outside of field guides or help by other users, and it doesn’t provide social interactions besides allowing users to view other’s observations. Furthermore, there are a wide range of apps that are targeted only at specific observations such as birds, reptiles, or plants and only observations in specific areas such as NYC. Within HCI literature, there are numerous resources providing guidelines for the design of mobile interfaces. One guideline developed shows how traditional guidelines for user interfaces can be transferred to mobile interfaces and expands on this knowledge to provide mobile-specific guidelines while acknowledging the challenges presented in mobile interface design. Most notably from these guidelines is designing for speed and recovery. Our main focus in this project was to develop a system with a priority of speed. This paper influenced us to include not only fast interactions, but ways to easily recover. For example, after leaving the initial camera screen, the user is always one button click away from being back on the camera screen. This reduces recovery time if a user were to accidentally exit the camera screen. The main goal of the app is to provide quick access for taking pictures so that users can snap photos of wildlife on the go without missing an opportunity due to too many steps to take a picture. However, apart from these guidelines and similar guides, there is limited research focused on the issue of designing a mobile interface in order to carry out an action under time constraints.

Thus, our application would provide insight into the mostly unexplored domain of timeconstrained interactions in mobile interfaces. Furthermore, this application will address interaction issues including user-friendly interfaces and maintaining user interactions. We designed a user friendly interface by taking the burden of identification off of the user and avoiding being overly technical or scientific so that little knowledge of wildlife/plants is needed to use the system. Furthermore, we capitalize on existing user interfaces in social media apps to provide a familiar design in a new domain. Also, gamification of the observation process via achievements will provide insight into maintaining user attention in less explored fields such as wilderness identification. We based this design decision on existing research such as research involving the popular website Stack Overflow . This research showed that badges influenced user behavior and in some circumstances increased user activity. In WildSnap, users can earn points and improve their profile achievement status by interacting more with the system and performing activities such as uploading and identifying more pictures, following other users in the WildSnap community, liking and commenting on other users pictures, etc.

Finally, much research has been conducted involving the importance of the potential connection human beings can create with nature through technology. In papers by Bronwyn, Paay, Kjeldskov et al., methods regarding using technology to promote interactions with nature are explored. The researchers determined key motivators for children to stay engaged with
technology and nature included social opportunities and opportunities to learn. We intend WildSnap to add to this work by creating an interface simple enough for beginners, such as children, to use while still encouraging users of all areas to explore their local environment and identify local plant and wildlife near their current location. Therefore, we are decided to include
social opportunities in the form of social media features (likes, comments, and friends).

##Design Alternatives##

### Design Alternative 1 ###
- At initial we want a simple static design layout for our application to make user understand each and every option easily adn we thought to have simple color combinations that looks very decent.
  
### Design Alternative 2 ###
- After that we found our first design not that much attractive so we decided to remove static pictures and add slider so that it gives more attraction to the application.
  
### Design Alternative 3 ###
- All of the application options are displayed in form of bar which will be on the center of the screen of the mobile.

### Design Alternative 4 ###
- Since diplaying option in a bar isn't that much attractive and user may not be able to find the options quickly so we decided to show them in forms of cube each option have its own cide in front of the screen and all of the features display in front of the user.

##PERSONA##
### PERSONA 1 ###

Name: Muhammad Zuhaib
Age: 22
Gender: Male
Qualification: Currently doing BS (CS)
Hobbies: Solving problems, playing Cards, writing  articles, Travelling 
Interest: Involved in local gaming zones, classes and groups, organizing events in the community, preparing food for events, Attending events, shows and exhibitions, cooking.
Problem: photo/image searching problem in other apps

**QUESTIONS**

•	What is the best snaps searching software  with extra features which other applications are not having?
o	I Natural list
o	Plant snap

•	Based on your experience, I natural list or any other application is better than us  give your  response?
o	Wild snap(yours)
o	(yes) o I natural list

### PERSONA 2 ###

Name: Syed Amir Rizvi
Age: 23
Gender: Male
Qualification: Currently doing BS (CS
Hobbies: Playing a musical instrument, painting, networking event, board games, gardening, making review of new meeting applications. 
Interest: videos games, creative writing, swimming, designing and making review of an application, football  
Problem: This form of gamification allows users to compete with each other to reach achievements and gain points by taking more pictures to identify and liking or commenting on their friends’ pictures. 

**QUESTION  **

•	What is the best snaps searching software  with extra features which other applications are not having?
o	I Natural list
o	Plant snap

•	Based on your experience, I natural list or any other application is better than us  give your  response?
o	Wild snap(yours)
o	(yes) o I natural list

•	How often do you use this application? 
o	Several times a week (YES) o Every day   o 1-3 times a month o Less than once a month 
### PERSONA 3 ###
Name: Saif ail khan
Age: 23
Gender: Male
Qualification: Currently doing BS (CS
Hobbies playing cricket watching movies hangout, friends circle
Interest: VR games, content writing, running, designing and making review of an applications, basketball
Problem: Once the system has found a match, the screen is updated with text to let the user know that we have identified their object.

**Question **
•	What is the best snaps searching software  with extra features which other applications are not having?
o	I Natural list
o	Plant snap

•	Based on your experience, I natural list or any other application is better than us  give your  response?
o	Wild snap(yours)
o	(yes) o I natural list

•	How often do you use this application? 
o	Several times a week (YES) o Every day   o 1-3 times a month o Less than once a month

### PERSONA 4 ###
Name: Syed ali muzzafar
Age: 24
Gender: Male
Qualification: Currently doing BS (IT)
Hobbies: Playing a musical instrument, painting, networking event, board games, gardening, making review of new meeting applications.
Interest: videos games, creative writing, swimming, designing and making review of applications, football
Problem: Pictures that have not yet been identified will be displayed with a label for the tagged location of the picture at the top of the screen as well as links to see which other users liked or commented on the photo.

**Question **
•	What is the best snaps searching software  with extra features which other applications are not having?
o	I Natural list
o	Plant snap

•	Based on your experience, I natural list or any other application is better than us  give your  response?
o	Wild snap(yours)
o	(yes) o I natural list

•	How often do you use this application?
o	Several times a week (YES) o Every day   o 1-3 times a month o Less than once a month

##SCENARIO ##

### SCENARIO 1  ###
A group of middle school students go on a hike with their local wildlife club. They decide to use WildSnap to keep track of various wildlife and plant life they see. The group leader creates a competition where the top 3 groups with the highest amount of points will win a prize. The groups split up and begin exploring the trails. One group runs across an insect and takes a picture with the app, which determines the insect is a Luna moth caterpillar. At the end of the hike, the group leader looks at the profile pages of each of the groups to see how many points were earned.

### SCENARIO 2  ###
A woman has advanced knowledge about wildlife identification and pursues this interest by tagging and identifying wildlife on weekends. While she is hiking one afternoon, she spots a unique looking animal and opens WildSnap. She is immediately presented with a camera and is able to take a picture before the animal runs off. She saves the picture and later uses the identify option to identify the animal.

### SCENARIO 3  ###
A family has been having an animal infestation problem in their house and would like to know if the animals were poisonous or venomous. No one in the family has any experience with wildlife identification, but the simple design of WildSnap allows them to take pictures and identify animals (insects, snakes, etc.). One evening a small snake is found in the corner of a closet, the father takes a photo from a safe distance, and identifies the snake to be a species that is non-venomous. He is then able to carefully capture and release the snake back outside.

### SCENARIO 4  ###
The animal researcher goes to jungle for research on some animmal when they goes to jungle he sees the snake they want to catch them or resarch on them but they didnt know that the snake was venomous or not they was affraid to catch snake because they didnt know much about that but then he has a wildsnap application they capture the picture of that and sees the deatils of that its venomous or not.

## STORYBOARDING ##

### STORYBOARDING 1 ###
User is very desperate to reseach of animals through the books or goto libarary to research on the animals.

### STORYBOARDING 2 ###
Suppose amir was in class an get a assigenment on search some details on rose follower and he just type the name or capture the picture of it and he get the deatils of it.

### STORYBOARDING 3 ###
Suppose zohaib do the side job of plantation one day they go to the coustomer home whom they call them to plantation on his garden but instantly coustmer give the new type of flower which zohaib didnt know about that how much water andfertlizer use to plantation these flower but zohaib can easily use these application and see the details of that flower.

### STORYBOARDING 4 ###
 saif have a many pet animals. they can easily solve the problems of his all pets by just capture the picture of that and get the solution of his problem because these application gives the details of all animal.


##Prototyping##


