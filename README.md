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

![model](https://user-images.githubusercontent.com/111474183/212213659-6e97f6d2-b1a8-4ebb-8a26-11768641a67f.jpg)
![view_showmodel](https://user-images.githubusercontent.com/111474183/212213676-0b81eb71-bffd-4707-b9d5-f1cee72f75af.jpg)

### Story 3: Display all items from the database
I wrote a function to display all database entries into an HTML page template. I was able to tailor which pieces of information to display in the form of a table.

![display database](https://user-images.githubusercontent.com/111474183/212213639-924f5752-d40e-4764-8ff9-b400126d80d6.jpg)


### Story 4: Details Page
Linked in the table, I had an option for the user to "view more details" on each entry. This link would direct the use to a page rendered by a function to display all details about a specific item from the database.

![details page](https://user-images.githubusercontent.com/111474183/212213628-6bb77ac8-90ca-46f5-a749-af8ba069574b.jpg)


### Story 5: Edit and Delete Functions
In the details page, I built in a function for the user to update the entry. An edit feature used the model form to simplify modifications to the data entry. In additon to update, the user has an option to delete the entry and would be redirected to a page that would ask for confirmation prior to deleting the entry.

![edit](https://user-images.githubusercontent.com/111474183/212213572-8cb753f6-a158-476f-ae6f-3ed8921e614b.jpg)
![delete](https://user-images.githubusercontent.com/111474183/212213587-7b7bb3da-35f4-4377-b809-e2456baf216a.jpg)
![confirm_delete](https://user-images.githubusercontent.com/111474183/212213595-e32cd37e-9204-400b-a5fd-2ee9f22645be.jpg)


### Story 6: API
For this project, an API for a weather app was used to provide the user with the current weather forecast. First, the function is written to request API data from the URL and convert the JSON response to Python data types. Next, a dictionary is created to pull relevent elements from the JSON response that I will want to display. This information is rendered in an HTML page.

![api](https://user-images.githubusercontent.com/111474183/212213525-9c1b0db3-d2b6-49c0-bd03-9b1a70e0c3fe.jpg)
