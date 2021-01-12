README.md
# Sweet Treats 🧁

<img src="https://browser-d0d4bab4-3203-42f7-9427-2507f859b0d3.ws-eu03.gitpod.io/workspace/Sweet-Treats/static/imgs/thirdprojectscreenshot.jpg" style="margin: 0;">

This project was an experiment to try and work with a database such as mongodb and python. This is my first attempt at 
building an app with different languages and frameworks like this so i decided to keep it simple. 
I chose to build a recipe app for users to add, edit, delete and view recipes (otherwise known as CRUD functionality)
and to be able to share their recipes with others using the app. 
The app follows a color theme on each page, intuitive navbar and search functionality and is very easy and straightforward to use.


> ## UX 📱
The app is for any who loves to cook and wants to try making something new. I focused this app soley on baking as there are millions of sweet dish recipes and sweet things are my favourite.
Most people who follow recipes in the kitchen use their tablet or smart phone to follow along. For that reason, I wanted the app to be responsive
yet simple as when someone is cooking, they dont want a lod of pop ups and advert opening on their device. This simple layout is easy for anyone to follow, 
including those who are now very familiar with technology.

* As a new user, I want to take a look at recipes for some ideas and see what recipes the app has to offer.
I can register an account within the app by providing a name and password.
The passwords have been secured in mongodb and have been hashed for user security. Then I can go to the 'Home' page and browse the categories of recpes, then I can click on a category, click on a recipe of my choice and start following the recipe.
To make things easier for newcomers, I added the ingredients onto the recipe card so that a user knows exactly what they need to be able to complete the recipe.
Additionally, if they dont have all the ingredients they can click on the button that says 'Buy the ingredients'. This button gives them an option to buy from amazon or tesco and the link will take them straight to their websites.
When I have finished on the app, I can then click log out on the navbar.

* As a user wanting to add a recipe to the database to share their recipes with others, I can click on 'Add new recipe' on the navbar.
Then I can simply fill in the form and when im done click 'Add recipe'. A feature I like here within this form are the color changes of input fields.
When an input field has not been filled in, it will be red to let the user know that they must enter something into that field.


* As a user wanting to edit a recipe, I can go to the profile page by clicking on profile within the navbar, find the recipe and click on it. I can click on edit and then 
edit any information i want in the form. When i'm done I can click done. As part of defensive programming, this option is only available to the user who first added the recipe.


* As a user wanting to delete a recipe, I can go to the profile page by clicking on profile within the navbar.
Find the recipe I want and then click 'Delete'. As part of defensive programming, a modal box will appear confirming weather the user really wants to delete this recipe.
This option is only available to the user who first added the recipe.


* As a user who does not have an account, I can click the 'Register an account' link and make an account to use the app.

* As the Admin of the app, I can add and delete categories by clicking on 'Manage Categories', 
then selecting the category I want and click on 'Delete'. 'Edit'. Or I can 'Add a new Category'.



This section is also where you would share links to any wireframes, These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

> # Features 🔎
## Existing Features
* Navbar - This is very obvious to the user and easy to use. It allows all users to navigate their way around the site effortlessly.
* Search bar - The search bar is intuitivly placed at the top of the page where users are most likely to see it. 
             This enables them to search for a category or recipe quickly using a word.
* Video - The video on the bottom of the home page let's users see the recipe of the month within the app.
* Categories - The recipe categories breaks up the recipes to a user friendly and logical display. Users can then find recipes with ease.
* CRUD Functionality - This allows the user to have control over their recipes within their own profile.
* Footer - This provides excellent links to helpful or interesting pages for further resources to the user.
* Mobile navbar- This pops out from the side to create more space on the open page.

 ## Features Left to Implement
In the future I will add an option for the user to be able to upload a photo of the product made by following the recipe.
I will also add a feature to be able to view all of the users favourite recipes in one place.
I would also like to add functionality for google to translate the pages of the app into other languages.

> ## Technologies used 🐍
**HTML** - I used HTML to write the basic code for the app to display headings, navbars, paragraphs, display a video, 
descriptions, categories, footers, links and information about the recipes.

**CSS** - I used some css to target and style elements individually to tailor the app to my preference.

**Materialize CSS** - I used materialize to style nearly all of my app. I wanted to try this as I had never used it before. After gaining 
knowledge of Materialze CSS I do prefer Bootstrap, but I'm glad I tried it to see how different it was and to see what I could learn by using it in this project.
https://materializecss.com/

**JQuery** - This project uses JQuery to simplify DOM manipulation. The app uses Jquery to open modals, drop down menus, open the navbar on the mobile device,
Open an accordion display of recipes and open the link options to buy the ingredients at two different stores.
https://jquery.com/  - This is the official site for JQuery but I used the JQuery snippets in Materialize CSS.

**Gitpod** - This project was written in gitpod and stored in my repositories in my profile on github.

**Python** - I used Python to insert responsive data into html code to be displayed accordingly in the app.

**Flask** - Hand in hand with Python, Flask was used in this project to add functionality, add routes and enable actions made by the user.

**Mongodb** - This was used to store data for the app. This includes, the recipes, categories and users.
https://www.mongodb.com/

**Heroku** - I used Heroku to deploy the app.
https://www.heroku.com/home

**Random Key Generator** - I used a fort knox password from this site to generate a secure password for my secret key.
https://randomkeygen.com/

**Images** - I got the Images from google to give some style and color to the landing page, as well as to the categories.

**Gitignore** - This was used to hide my env.py file so that my secret key would be kept secure.

**Balamiq** - I used this program to create the wireframes for the project.
https://balsamiq.com/wireframes/desktop/ 

**Requirements.txt file** - This file let's me see which frameworks need to be installed for the app to run.


> ## Testing 🧮
* I have thouroughly checked all pages and their functionality on my laptop while writing the code and also after deployment on my phone and tablet.

* I have used validators to validate my CSS code. I used this program:
https://validator.w3.org/#validate_by_input

I have tested my JQuery by .........................


* I tested the funcionality of the navbar on the home page on a laptop and mobile device by clicking on each and every page to check the link 
to the page works properly. On the home page I also tested the footer links by clicking on them and each link opens a new tab to view the page
as well as each icon to social media pages.

* To test the register functionality for a new user, I left the input fields empty and they would not submit the information as I programmed
a minimum character reuirement for the name and password. The JQuery is used to show that the field needs to be filled in.

* To test the log in functionality, I typed a correct name but the wrong password and the log in was not sucessful. Then I typed in the wrong 
name but correct password and it still didn't work. This all worked well and only opened a profile when the correct credentials were entered.


* I tested the delete functionality a lot as I was developing the app to make sure they had actually been erased from not only the app as it 
is seen but also on Monogdb. I clicked on delete on a recipe, then clicked yes when the pop up modal asked me if i really wanted to delete it.
When it redirected me back to the profile page, I could see that it had been deleted. To make sure that it had also been deleted on Monogdb 
I logged into my account there and went to my cluster, then collections and I could see that it had also been deleted on mongodb.

* I tested the edit and add functionality in the same way I tested the delete functionality. First I added or edited on the app itself as a user
would, then I went to Monogdb to check that the data had been added or edited there.

* I checked the video worked on the home page by playing it within the app and also playing it on a mobile device to make sure it was responsive.

* Then I checked the search bar. To do this I typed a word and then clicked reset to make sure the search reset itself. After that I typed a word
from a recipe such as 'chocolate', then all the recipes that has that ingredient in the title displayed itself.

* Finally, I checked all the categories and recipes to make sure that the recipes had been placed into the correct categories. 




> ## Deployment 💻
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

> ## Credits

> ## Content 📖
Most of the app.py and env.py was imitated from Code Institutes tutorial video for a mini project. I used the sme principles to make this project,
then I tweaked it to fit my needs for the app and added extra content and styling.

> ## Media 🎞️
The photos used in this site were obtained from google.

> ## Acknowledgements 🙏
I received inspiration for this project from great recipe apps that are already out there! There are a lot of changes I will make to this 
project in the future but I kept it simple for now as I have a deadline for my project. I'm looking forward to going back and making great 
changes and developments to my app in the near future.