# recipe-finder
click to visite website # The Recipe Finder
https://pranayainchwar.github.io/recipe-finder/

![recipefinderviewpage](https://github.com/pranayainchwar/recipe-finder/assets/122523118/5bea2916-03d8-4ad9-826d-7a7736712d21)
After the Searching Recipe 
![recepifinder](https://github.com/pranayainchwar/recipe-finder/assets/122523118/baa8b6a5-c25e-435e-8108-9c9fed6e0160)

To see click on link : https://pranayainchwar.github.io/recipe-finder/

 The application is called "The Recipe Finder," and it allows users to search for their favorite recipes. Here is a step-by-step explanation of the project:

Header Component:

Import and define a header component.
The header has a black background with white text.
It includes a logo and a search bar.
The logo is an image with the app name "The Recipe Finder."
The search bar includes an input field for searching recipes.
Recipe Component:

Import and define a recipe component for displaying individual recipes.
The component displays the recipe's cover image, name, and two clickable text elements.
Clicking "Ingredient Recipe" opens a dialog displaying the ingredients and their weights.
Clicking "See Complete Recipe" opens a new page with the complete recipe.
App Component:

Import necessary libraries, components, and styles.
Set up the main application component, which is a functional component named "App."
Use state to manage the timeout for making API requests and the list of recipes.
Define a function "fetchRecipe" that makes API calls to retrieve recipes based on a search query.
Handle text input changes, debouncing the input to prevent excessive API calls.
Display the header with the app name and search bar.
Display a list of recipe cards using the Recipe Component. The data for these cards is fetched from the API.
Styling:

Define styles for various components, including the header, recipe container, and dialog for displaying recipe details.
Use styled-components to apply CSS styles in a component-based manner.
API Integration:

The application integrates with an external recipe API (Edamam) to fetch recipes based on user search queries.
The API key and ID are stored as constants.
Dialog for Ingredients:

A dialog is used to display recipe ingredients and their weights.
The dialog includes a "See More" button to open the complete recipe in a new tab.
There's also a "Close" button to dismiss the dialog.
Loading Placeholder:

If there are no recipes to display, a placeholder image is shown with a loading message.
Root Component:

Import React and ReactDOM to render the application.
Create a root element in the HTML with the ID "root."
Render the main application component inside a React.StrictMode.
Global Styles:

Some global styles are defined for the body and code elements.
Application Entry Point:

The application is initiated by rendering the "App" component at the root element in the HTML document.
