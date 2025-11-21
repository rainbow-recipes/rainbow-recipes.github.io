# Rainbow Recipes

## Team Contract
[Rainbow Recipes Team Contract](https://docs.google.com/document/d/1ii8JpiN7N2ggNPNK966_UyXlzq3T6nzf9zWfuArA9YU/edit?usp=sharing)

## Deployment
[Rainbow Recipes](rainbow-recipes.vercel.app)

## Goals for the project
*Problem*: Many college students have limited kitchen resources, limited cooking skills, limited time, limited access to grocery stores, and no access to creative recipes that respect these constraints. As a result, college students spend money to eat out, or eat non-healthy foods at fast food places or through vending machines.

*Solution*: Rainbow Recipes creates a way for students (on-campus or off) to learn and share recipes that:
* Can be made using minimal kitchen facilities (at a minimum, a toaster oven).
* Can be made out of ingredients that are available within walking distance of UH.
* Suit local taste sensibilities.
* Can be filtered via dietary restrictions (gluten-free, vegan, etc).
* Have an estimated cost per serving.
* Has an estimated number of servings per recipe.
* Has an estimate of how long it takes to make.

### Approach
There are three roles in this system: students, vendors, and admins:
* Students can both search for and contribute recipes.
* Vendors (local grocery stores and/or farmer’s markets) can login and establish a profile including their location and hours. 
* Admins can edit all content in the system, remove inappropriate content, and establish users as having the vendor role.

#### Mockup page ideas:

##### Guest Landing Page
The landing page is the first page presented to visitors when they access the Rainbow Recipes site. It gives a clear introduction to the application, guiding users towards the main features of the website. 

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/landing-page.png" />
</div>

##### User Sign Up / Log In Page

The sign in/ sign up page provides authentication functionality, allowing users to either access an existing account or create a new one to unlock all of the application's features.

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/sign-up-page.png" />
</div>

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/log-in-page.png" />
</div>

##### Home Pages

The Rainbow Recipes home page will differ slightly for each user.

A regular, logged in user will have a Recipes, Favorites, and See Vendors tab in the navigation. 

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/user-home-page.png" />
</div>

A vendor will have a Vendor, Recipes, and Favorites tab in the navigation. The Vendor page will allow a vendor to add/update their stock.

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/vendor-home-page.png" />
</div>

An admin will have an Admin, Recipes, and Favorites tab in the navigation. The Admin page will show all users, vendors, and recipes. 

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/admin-home-page.png" />
</div>

##### Recipes Page

Recipes will be shown in a grid format each including the name, estimated time to finish, a favorite button, and the rating. A filter and search will be included to make finding specific recipes easier. Users will also be able to add their own recipes.

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/recipes-page.png" />
</div>

##### Add Recipe Page

Logged in users will be able to add their own recipes through a form. They will provide the name of the recipe, the estimated time, ingredients, appliances, an image, and instructions.

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/add-recipes-page.png" />
</div>

### Risks and Mitigations

**Poor Communication**

Meeting twice a week with team members to discuss the project and progress of tasks. Discussing any concerns, disagreements, or new ideas.

**Scope Creep**

Document changes in implementation and document possible future expectations. Address this to relevant parties to be able to adjust deadlines and other factors accordingly.

**Unclear Requirements**

Make sure to ask clients for clear instructions and examples of what they want. Make sure the clients understand what is possible under their time constraints and budget.

**Poor Project Planning**

Document everything you’re planning, split it into small, manageable parts, and use milestones.

**Technical Complexity**

Ensure all team members have access to the software and hardware needed to build the project.

**Inadequate Team Skills**

Survey technical skill sets beforehand; address any challenges that cannot be overcome even after personal time dedicated to problem-solving.

**Resource Constraints**

Have a larger buffer in areas of high risk and high importance. Document any rising risks and maintain flexibility with resource reallocation.



### Use case ideas
* New user goes to landing page, logs in, gets home page, sets up profile. (How do they learn how system works?)
* Admin goes to landing page, logs in, gets home page, edits site.
* User goes to landing page, logs in, browses recipes.

### Beyond the basics
After implementing the basic functionality, here are ideas for more advanced features:
* Maps for locating vendors.
* Based upon open hours for vendors, indicate which ingredients can be bought right now.
* Ratings and review system for recipes.
* Ratings and review system for vendors.
* Notification system for vendors when new items are posted in recipes so they can update their listing to indicate whether they stock it or not.
* Notification system when price for a recipe drops substantially (i.e. a vendor puts an item on sale.)

### Milestone 1 Updated Screenshots

##### Guest Landing Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-landing-page.png" />
</div>

##### User Landing Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-user-landing-page.png" />
</div>

##### Sign Up & Sign In Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-signup-page.png" />
</div>

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-signin-page.png" />
</div>

##### Recipes Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-all-recipes-page.png" />
</div>

##### Add Recipe Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-add-recipe-page.png" />
</div>

##### User's Recipe Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-users-recipes-page.png" />
</div>

##### User's Favorites Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-favorites-page.png" />
</div>

#### Vendor's Account Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-mystore-page.png" />
</div>

#### Admin Page

<div style="box-shadow: 0px 0px 20px gray;">
  <img src="/images/m1-admin-page.png" />
</div>

### Milestone 1 Project Page
[Milestone 1](https://github.com/orgs/rainbow-recipes/projects/1)

### Milestone 2 Project Page
[Milestone 2](https://github.com/orgs/rainbow-recipes/projects/6)