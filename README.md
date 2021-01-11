<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">
README.md
Sweet Treats
This project was an experiment to try and work with a database such as mongodb and python. This is my first attempt at 
building an app with different languages and frameworks like this so i decided to keep it simple. 
I chose to build a recipe app for users to add, edit, delete and view recipes (otherwise known as CRUD functionality)
and to be able to share their recipes with others using the app. 
The app follows a color theme on each page, intuitive navbar and search functionality and is very easy and straightforward to use.


UX
The app is for any who loves to cook and wants to try making something new. I focused this app soley on baking as there are millions of sweet dish recipes and sweet things are my favourite.
Most people who follow recipes in the kitchen use their tablet or smart phone to follow along. For that reason, I wanted the app to be responsive
yet simple as when someone is cooking, they dont want a lod of pop ups and advert opening on their device. This simple layout is easy for anyone to follow, 
including those who are now very familiar with technology.

As a new user, I want to take a look at recipes for some ideas and see what recipes the app has to offer.
I can register an account within the app by providing a name and password.
The passwords have been secured in mongodb and have been hashed for user security. Then I can go to the 'Home' page and browse the categories of recpes, then I can click on a category, click on a recipe of my choice and start following the recipe.
To make things easier for newcomers, I added the ingredients onto the recipe card so that a user knows exactly what they need to be able to complete the recipe.
Additionally, if they dont have all the ingredients they can click on the button that says 'Buy the ingredients'. This button gives them an option to buy from amazon or tesco and the link will take them straight to their websites.
When I have finished on the app, I can then click log out on the navbar.

As a user wanting to add a recipe to the database to share their recipes with others, I can click on 'Add new recipe' on the navbar.
Then I can simply fill in the form and when im done click 'Add recipe'. A feature I like here within this form are the color changes of input fields.
When an input field has not been filled in, it will be red to let the user know that they must enter something into that field.


As a user wanting to edit a recipe, I can go to the profile page by clicking on profile within the navbar, find the recipe and click on it. I can click on edit and then 
edit any information i want in the form. When i'm done I can click done. As part of defensive programming, this option is only available to the user who first added the recipe.


As a user wanting to delete a recipe, I can go to the profile page by clicking on profile within the navbar.
Find the recipe I want and then click 'Delete'. As part of defensive programming, a modal box will appear confirming weather the user really wants to delete this recipe.
This option is only available to the user who first added the recipe.


As a user who does not have an account, I can click the 'Register an account' link and make an account to use the app.




This section is also where you would share links to any wireframes, These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features
Navbar - This is very obvious to the user and easy to use. It allows all users to navigate their way around the site effortlessly.
Search bar - The search bar is intuitivly placed at the top of the page where users are most likely to see it. 
             This enables them to search for a category or recipe quickly using a word.
Video - The video on the bottom of the home page let's users see the recipe of the month within the app.
Categories - The recipe categories breaks up the recipes to a user friendly and logical display. Users can then find recipes with ease.
Add, Edit, Delete, view recipes - This allows the user to have control over their recipes within their own profile.
Footer - This provides excellent links to helpful or interesting pages for further resources to the user.
Mobile navbar- This pops out from the side to create more space on the open page.

Features Left to Implement
In the future I will add an option for the user to be able to upload a photo of the product made by following the recipe.
I will also add a feature to be able to view all of the users favourite recipes in one place.


Technologies Used
In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

JQuery
The project uses JQuery to simplify DOM manipulation.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

Contact form:
Go to the "Contact Us" page
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z
Media
The photos used in this site were obtained from ...
Acknowledgements
I received inspiration for this project from X