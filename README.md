# Sweet Treats 🧁
You can see the live site here.
https://sweet-treats-project.herokuapp.com/ 

<img src="https://browser-d0d4bab4-3203-42f7-9427-2507f859b0d3.ws-eu03.gitpod.io/workspace/Sweet-Treats/static/imgs/thirdprojectscreenshot.jpg" style="margin: 0;">

This project was an experiment to try and work with a database such as mongodb and python. This is my first attempt at 
building an app with different languages and frameworks like this so i decided to keep it simple. 
I chose to build a recipe app for users to add, edit, delete and view recipes (otherwise known as CRUD functionality)
and to be able to share their recipes with others using the app. 
The app follows a color theme on each page, intuitive navbar and search functionality and is very easy and straightforward to use.


> ## UX 📱
The app is for any who loves to cook and wants to try making something new. I focused this app soley on baking as there are millions of sweet dish recipes and sweet things are my favourite.
Most people who follow recipes in the kitchen use their tablet or smart phone to follow along. For that reason, I wanted the app to be responsive
yet simple as when someone is cooking, they dont want a load of pop ups and adverts opening on their device. This simple layout is easy for anyone to follow, 
including those who are not very familiar with technology.

* As a new user, I want to take a look at recipes for some ideas and see what recipes the app has to offer.
I can register an account within the app by providing a name and password.
The passwords have been secured in mongodb and have been hashed for user security. Then I can go to the 'Home' page and browse the categories of recipes, then I can click on a category, click on a recipe of my choice and start following the recipe.
To make things easier for newcomers, I added the ingredients onto the recipe card so that a user knows exactly what they need to be able to complete the recipe.
Additionally, if they dont have all the ingredients they can click on the button that says 'Buy the ingredients'. This button gives them an option to buy from amazon or tesco and the link will take them straight to their websites.
When I have finished on the app, I can then click log out on the navbar.

* As a user wanting to add a recipe to the database to share their recipes with others, I can click on 'Add new recipe' on the navbar.
Then I can simply fill in the form and when im done click 'Add recipe'. A feature I like here within this form are the color changes of input fields.
When an input field has not been filled in, it will be red to let the user know that they must enter something into that field.


* As a user wanting to edit a recipe, I can go to the profile page by clicking on profile within the navbar, find the recipe and click on it. I can click on edit and then 
edit any information i want in the form. When i'm done I can click done. As part of defensive programming, this option is only available to the user who first added the recipe.


* As a user wanting to delete a recipe, I can go to the profile page by clicking on profile within the navbar.
Find the recipe I want and then click 'Delete'. As part of defensive programming, a modal box will appear confirming whether the user really wants to delete this recipe.
This option is only available to the user who first added the recipe.


* As a user who does not have an account, I can click the 'Register an account' link and make an account to use the app.

* As the Admin of the app, I can add and delete categories by clicking on 'Manage Categories', 
then selecting the category I want and click on 'Delete'. 'Edit'. In addition, I can 'Add a new Category'.

Please see the link to the wireframe folder to view the wireframes. I included a link instead of the images within this README.md
because the images are very large. Within the folder you will find the images for the wireframes for a desktop and mobile view of
the landing page along with an example of a category page within the app and a recipe page.
Please see the folder here [static/wireframes](static/wireframes)

## Five planes of UX

* **Strategy** - 
The Business goals for this project were to get the user to register with the app to become a user. Also, use my app for recipes for baking
and enjoy the social side of the app, i.e seeing other users recipes that they upload and being able to share their recipes with the world.
-----
* **Skeleton** - 
The user would have to be able to add, view, edit and delete their own recipes as they wish but not delete or edit other users recipes.
They would also have to register and log in to have full access to the site and it's features. The users also need to be able to search
for a word that will show them all the recipes that contain that word, for easy finding of recipes.
------
* **Structure** - 
The content needed to be logically grouped together in categories and display the most logical and expected content for each page visited.
The home page contains all the different categories of recipes, then within that category the different recipes, then within that recipe,
the information on how to make that particular product. 
------
* **Scope** - 
The app needed to include links to social media pages as the app itself encourages a social theme of viewing other peoples recipes. 
The project also includes links to inspirational pages such as good cookware to invest in, recent videos for quick recipes and excellent
dishes from all over the world for inspiration to make something new. One feature heavily relied on by the each and every user is of course
the navbar from which all major actions are taken along with navigation of the entire app. This is nicely responsive thanks to Materialize CSS.
Another nice feature I wanted to include was a link to be able to buy the ingredients. On each recipe card, the ingredients displays so that each
user knows straight away if they have what is needed to make the sweet treat. If not, they can click on the tab for 'Buy Ingredients'
and they have the options of buying from amazon or tesco. 
------
* **Surface** - 
The finished appearance of the app is simple overall. This ensures that a user of any age is able to navigate their way through the app
and to be able to understand what they are looking at. The appealing image of baked goods appears on nearly every page and there is a color 
theme followed for a uniformed look. 

> # Features 🔎
## Existing Features
* Navbar - This is very obvious to the user and easy to use. It allows all users to navigate their way around the site effortlessly.
* Search bar - The search bar is intuitively placed at the top of the page where users are most likely to see it. 
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


* I have tested the JQuery by deleting some code, adding in code that will not work and see how it effects the functionality.
This was an ongoing process when I was debugging my code. Forntunately I have now debugged it all and it is all working as I want it to.
This wasn't too difficult this time as I used snippets of JQuery from Materialize CSS, the JQuery was quite simple and easy to work with.

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

* I deployed the app and checked it on my phone however I discovered something crucial to the functionality of the search bar! 
The search bar only worked when a user was logged in, so I had to remove the search bar from displaying until a user creates an account on
the app and logs in. So glad I checked it on my phone before submitting the project.




> ## Deployment 💻
For this project, I used Github to create a repository using a template provided to me by Code Institute. 
When created, I used Gitpod to write my code for the app.I saved my work and after each major change or addition to the project
I pushed it to Github to be stored. When I finished the project I deployed it to Heroku using the following process:


1. Find the correct repository on Github.
2. Open repository using the green GitPod button at the top right side of the page.
3. In terminal run "pip3 freeze --local > requirements.txt" command to create a .txt file. 
   Heroku needs this to know what dependencies the app uses.
4. In the terminal run the "echo web: python app.py > Procfile" command to create a Procfile that Heroku needs.
5. Check the Procfile hasn't got a blank line under the first line. If it has then delete the blank line.
6. Go to Heroku and log in to the account already registered with them.
7. Once logged in, go to the dashboard and click on "Create New App".
8. Under "Create New App" click on the button called "App Name".
9. Give the app a unique name although do not contain spaces within the app name.
10. Select the correct region closest to current location.
11. Click "create app".
12. Set up automatic deployment by clicking on the "Github" icon inside of the "Deployment Method" section.
13. Under the "Deployment Method" section there is another section called "Connect to GitHub", 
    check that the correct GitHub profile is displayed inside it.
14. Insert repository name inside the "Connect to Github" input field. Then click on "Search".
15. When the repository shows, click on the "connect" button.
16. Before clicking the "Enable Automatic Deployment" button, click on the settings tab.
17. Click on "Reveal Config Var".
18. Here tell Heroku which variables are required, but do not include quotes for the key or the value.
19. Insert variables of (IP, PORT, MONGO_URI, MONGODB_NAME, SECRET_KEY).
20. Go to GitPod and make sure that the requirements.txt and Procfile have been pushed to the correct repository.
21. Go to Heroku and click on "Enable Automatic Deployment".
22. Select the branch. Select the (master) branch.
23. Click "Deploy Branch"
24. Wait for Heroku to build the app.
25. When Heroku has finished building and the site is deployed click "View" to launch the new app.

## Local Deployment:
To run the code locally you can download a zip file which contains all of the code and files to build the app within the Github repository.
When the files have downloaded, a program such as VScode can be used to open them.

## Setting up the project on MONGODB_NAME
1. Go to 'mongodb.com'.
2. Click on the 'Start Free' button from the main landing page.
3. Then fill in the form with your details.
4. To create a cluster to work with the project, click 'Shared Clusters' or 'Create a Free Cluster'.
5. Then select a Cloud provider. AWS is my personal choice.
6. Select the region closest to your area. Make sure to select the region closest to you that is free as some have to be paid for.
   you can of course pay for extra services with MONOGDB if you wish but for this project I kept it simple with the free version.
7. Ater that choose the Cluster Tier. I chose the M0 Tier, which is the 'free forever' tier.
8. Scroll down to the bottom, and select 'Cluster Name'. Create a name for your cluster.
9. Finally, click on the 'Create Cluster' button.
10. Then click on 'Database Access' under the Security section on the
    left, to create the database user credentials.
11. Click on 'Add New Database User', and use the default SCRAM authentication
    method by creating a username and password. Only use letters and numbers if possible so as to not create further compliactions 
    within the project.
12. Set privileges to 'Read and Write to the Database', and then click 'Add User'.
13. Now click on 'Network Access' within the Security menu,
    to whitelist the IP address and make sure that it has access to our database.
    Click 'Add IP Address', and select 'Allow Access From Anywhere', to access this from our workspace, and then later on Heroku.
    Put the IP addresses of the hosts here, so this can act as a further security feature, and can help to prevent unauthorized access to the data.
14. Go back to our Clusters tab.
15. Now click on the 'Collections' button. Then click 'Add My Own Data'.
16. Give the database a name using camelCase.
17. Then you can add a collection. I added the collection 'Recipes'.
18. To create the first document within the collection click on 'Insert Document'. 
    Documents are stored in a format that's JSON-like, so it needs to have curly brackets and key-value pairs.
19. Type in the fields you want to be displayed within the document. I inserted a basic cookie recipe with the ingredients, 
    description, name and method.
20. Once that's filled-in, click on the 'Insert' button and wait for it to insert that into the database.
21. Now the first document has been created on MONGODB.
22. When the app has been created and the functionality has been added, the data can then be added via the app instead of in MONGODB.
    But this is how I set up the database at the start of the project.

> # Credits

 ## Content 📖
Most of the app.py and env.py was imitated from Code Institutes tutorial videos for a mini project. I used the same principles to make this project,
then I tweaked it to fit my needs for the app and added extra content and styling.
Manojlovic1998's project for https://recipe-pot.herokuapp.com/ was very inspiring and helpful. 
I used the steps for the Heroku deployment video at codeinstitute to create the deployment
section of this readme.md and then tailored it to my project as they explained the steps very well.


 ## Media 🎞️
The photos used in this site were obtained from google.

 ## Acknowledgements 🙏
I received inspiration for this project from great recipe apps that are already out there! There are a lot of changes I will make to this 
project in the future but I kept it simple for now as I have a deadline for my project. I'm looking forward to going back and making great 
changes and developments to my app in the near future.