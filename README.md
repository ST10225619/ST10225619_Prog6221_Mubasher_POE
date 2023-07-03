# ST10225619_Prog6221_Mubasher_POE
Final POE for PROG6221 ST10225619
ST10225619
Mubasher Hussain
Prog6221
ReadMe

github link: https://github.com/ST10225619/ST10225619_Prog6221_Mubasher_POE.git

Instructions:
- First download the project and save it.
- Then open visual Studio and select the option "Open project solution"
- Navigate to donwloadled Folder and open "wpfApp3"
- Program will open with all its necessary classes.

Classes Description:

MainWindow:
The MainWindow class represents the main window of the application. It is responsible for handling user interactions related to saving recipe names. It contains event handlers for the "Save Name" and "Add Details" buttons. The SaveRecipeName() method is used to save a recipe name entered by the user and add it to the recipe list. The buttonAddDetails_Click() method is responsible for opening the RecipeDetailsWindow to add further details to the recipes.

RecipeDetailsWindow:
The RecipeDetailsWindow class represents a window where users can add details to a recipe. It receives a list of recipes as a parameter and populates a combo box with the available recipe names. Users can select a recipe, enter ingredient details, such as name, quantity, calories, unit of measurement, food group, and steps, and save the ingredient to the selected recipe. The buttonViewRecipes_Click() method allows users to view the list of recipes. It also includes a text box for entering steps and handles the text changed event with the textBoxSteps_TextChanged() method.

RecipeListWindow:
The RecipeListWindow class represents a window that displays the list of recipes. It receives the list of recipes as a parameter and populates a combo box with the available recipe names. Users can select a recipe from the combo box and click the "View" button to display the recipe's details. The viewRecipeButton_Click() method retrieves the selected recipe, constructs a string with the recipe details, and displays it in a text block within a scroll viewer. This class provides a way for users to view the saved recipes and their corresponding ingredients.


Improvement based on lecturers Feedback:

So I did not do so well in terms of the previous part(Part 2). The feedback I recived was of the following things I could improve on, such as using try and catch methods to handle exceptions much better. Some of my methods were not working. Such as the scaling methods. The Reset method was not working because of a minor syntax error in the method. I have improved on capturing and viewing the recipe details as not all my details were captured in Part 2. Overall I Have improved in capturing the data entered from the user. However I failed to add the filter feature for filtering by calories and foodgroup.


Screenshots:
![image](https://github.com/ST10225619/ST10225619_Prog6221_Mubasher_POE/assets/102403687/48f8d926-4a04-4631-856b-c42eb4169d3c)

