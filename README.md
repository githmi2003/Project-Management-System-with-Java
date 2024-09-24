# Project-Management-System-with-Java
This project management system, built with JavaFX GUI and Java, allows users to efficiently add, delete, update, view, and manage project details. It categorizes projects into different categories and includes additional functionality such as randomly spotlighting projects, selecting award-winning projects based on a scoring system, and visualizing the results.

Features
Adding Project Details: Users can add new projects, including information such as project ID, name, category, team members, description, and country through a user-friendly JavaFX form.
Deleting Project Details: Projects can be deleted by entering the respective project ID.
Updating Project Details: Users can update specific fields of an existing project by selecting the project ID and using the GUI prompts.
Viewing Project Details: All projects can be viewed one by one by pressing the next button.
Random Spotlight Selection: The system randomly selects a project from each category, highlighting it for quick reference.
Award-Winning Projects: Judges can score projects through the system, and the top three projects are automatically identified and visualized based on these scores.
Visualizing: A graphical visualization of the top three award-winning projects is displayed within the JavaFX interface.

File Structure
MainApplication.java: The main Java class located at src/main/java/com/example/cwjava/MainApplication.java, which contains the core functionality and launches the JavaFX GUI.
Category1.txt, Category2.txt, Category3.txt: Text files used to store category wise project details. 
allProjectDetails.txt: A text file used to store retrieved project details from category files.
RandomDetails.txt: A text file used to store randomly selected project details from category files.

How to Use
Running the Program:
Run MainApplication.java to launch the JavaFX GUI.
Use side bar buttons to add, delete, update, view project details or navigate to the spotlight showcase section.
Adding Project Details:
Click "Add" button from the side bar, and input the required project details such as project ID, name, category, team members, description, country and team logo in the GUI form.
Deleting Project Details:
Click "Delete" button from the side bar, and enter the project ID to delete the project.
Updating Project Details:
Click "Update" button from the side bar, enter the project ID, and follow the prompts to update the desired fields.
Viewing Project Details:
Click "View" Button to display all stored projects in the interface.
Spotlight Showcase:
Click "Show Case" button to navigate to the Random Spotlight Selection.
Random Spotlight Selection:
Click "Category 1", "Category 2", "Category 3" button to view randomly selected project details from each category.
Award-Winning Projects:
Judges can score projects through the interface, and the top three are determined based on the highest scores.
Visualizing:
Select "Visualize" to see a graphical representation of the top three projects within the JavaFX application.

Dependencies
Java Development Kit (JDK) with JavaFX libraries installed.
