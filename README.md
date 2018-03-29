# HERO-System-Character-Records-Manager
This Program, tentativly named 'Cloak', is a program for making the HERO System Tabletop Role-Playing-Game easier to play. The System, while it provides a great deal of customization in character creation, is very complex and requires a large time investment to begin. My aim is to make that time investment much smaller by automating all the calculations and creating an ogranized interface that smooths out the process of character generation and management during a game session.\
Download the Project and Run it from the Main.java file, these files were created in eclipse so you may need to remove the package identifier line at the top.
## Updates
**2/21/2018**\
  Began Planning\
**3/1/2018**\
  Began Using SceneBuilder to create GUI for main program\
**3/15/2018**\
  completed the main fxml files for the GUI using SceneBuilder, and finished all the sub panels that are context sensitive.\
**3/26/2018**\
  Completed the Database Model in SQL Workbench
**3/28/2018**\
  Fixed the Main.java file so it would Run the GUI as it is\
  added the project to GitHub\
**3/29/2018**\
  oulined Scope beyond the CapStone aspect and began documenting project updates(retroactivly documented previous progress)
## Scope
Part of this project will be completed for my CapStone at Southwest Technical College.\
### CapStone Scope
1. Have the Character Database running live on my laptop
2. Create a program that manages that database\
* an update method for taking information from the User program and updating the database information
* a security protocol for that requires a user to enter a password before being able to update.
* a retrieval method that returns the information contained about a specific character ID
3. Create a Program that manages the GUI for creating and editing a character\
* The ability to correctly view and interact with the Demographics, Story, and Stats pages.
* A method to Save the data contained on the previously mentioned pages to a Character File.
* A connection to the database manager that gives the information about a character to the database.
* A method to retrieve data from a previously made character file.
* A connection to the database manager that gets the information about a character and loads it into the program.
### The Complete Version 1 Scope
1. Finish creating the Character Creation and Editor aspect of the Program
* The ability to correctly view and interact with all the tabs except the *Play* tab.
* all of these pages must be correctly integrated with the save, retreive, and database connection methods.
* Add tooltips and documentation to help explain the rules of character generation and the HERO system.
* Create a Tutorial guide that helps players begin creating there first character
2. Update the Database and Database handler
* Add all of the new values to the character Database
* Make sure the Handler correctly retrieves and saves them
3. Create the Session Manager portion of the program
* Determine the functionality of the *Play* Tab
* Design the layout of the *Play* tab
* Code the *Play* tab so it pulls information from the Character Data, and updates that information constantly.
### Beyond Version 1
1. Create a Battle Manager
* this manager will be able to have a list of battle participants and their data, and streamline the combat process within a central program. 
2. Create a Session Manager that is located on the Server and capable of having multiple players connected to it
* This would be the natural extension of the battle manager, and would provide a way to connect online instead of having to download indivual character files.
3. Make the System Function for the complete General HERO System instead of for my own Custom Rule Set
4. Make it so Game Masters can create their own custom rule sets for their campaigns.
5. Expand Functionality to Other Game Systems.
