# Python Live Project
## Introduction
For the end of my Python course at the Tech Academy, I worked with my peers on a live project utilizing Azure DevOps and Agile/Scrum principles. This 2-week sprint utilized various Python and Django features in order to create databases, interact with APIs, and display these collections of data onto a webpage. 

Throughout the 2-week sprint, we were assigned various stories to complete. In addition to applying my skills in Python, Django, SQLite, and HTML/CSS, I was also able to apply my knowledge in utilizing version control. The advantage of the live project is that I am expected to create my own branches, keep it up to date with the master branch, commit changes, test my code, and make pull requests to the main branch. This process, in addition to the daily stand-ups and agile/scrum methodology, gave me great sense of working on a working development team. 

## CRUD Functionality
This project's main focus was implementing CRUD Functionality: create, read, update, and delete. Each story represented one of the four CRUD operations components.

### Story 1: Building the Basic App
I created an app within the existing project using CommandLine and registering the app with the main project. I also created base and home templates with will build the basic front-end of my app's homepage.

### Story 2: Create the Model
I created a database model for the app I am building: a collection of Portland, OR's best restaurant dishes. After creating the model, I created a model form to take in user input and a view function to render that form on the page and save the input into the database. 

### Story 3: Display all items from the database
I wrote a function to display all database entries into an HTML page template. I was able to tailor which pieces of information to display in the form of a table.

### Story 4: Details Page
Linked in the table, I had an option for the user to "view more details" on each entry. This link would direct the use to a page rendered by a function to display all details about a specific item from the database.

### Story 5: Edit and Delete Functions
In the details page, I built in a function for the user to update the entry. An edit feature used the model form to simplify modifications to the data entry. In additon to update, the user has an option to delete the entry and would be redirected to a page that would ask for confirmation prior to deleting the entry.

### Story 6: API
For this project, an API for a weather app was used to provide the user with the current weather forecast. First, the function is written to request API data from the URL and convert the JSON response to Python data types. Next, a dictionary is created to pull relevent elements from the JSON response that I will want to display. This information is rendered in an HTML page.
