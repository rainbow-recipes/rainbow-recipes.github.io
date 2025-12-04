<style>
  @import url('/style.css');
</style>

# Rainbow Recipes

---

## Table of Contents
- [GitHub Organization](#GitHub-Organization)
- [Deployment](#deployment)
- [Overview/Goals](#goals-for-the-project)
- [Mockup Pages](#mockup-page-ideas)
- [Use Case Ideas](#use-case-ideas)
- [Beyond the Basics](#beyond-the-basics)
- [Risk and Mitigations](#risks-and-mitigations)
- [User Guide](#user-guide)
- [Developer Guide](#developer-guide)
- [Milestone 1](#milestone-1)
- [Milestone 2](#milestone-2)

---

## Rainbow Recipes GitHub Organization
[Rainbow Recipes](https://github.com/rainbow-recipes)

## Team Members

[Rainbow Recipes Team Contract](https://docs.google.com/document/d/1ii8JpiN7N2ggNPNK966_UyXlzq3T6nzf9zWfuArA9YU/edit?usp=sharing)

## Deployment
Deployed Site: [https://rainbow-recipes.vercel.app/](https://rainbow-recipes.vercel.app/)

[![ci-rainbow-recipes](https://github.com/rainbow-recipes/rainbow-recipes/actions/workflows/ci.yml/badge.svg)](https://github.com/rainbow-recipes/rainbow-recipes/actions/workflows/ci.yml)

---

## Project Goals
College students often have limited kitchen supplies and may lack basic cooking skills. With busy school schedules and part-time work, they have little time to not only learn and prepare meals, but to go out and buy groceries. As a result, it's easy to fall into the habit of eating out or even forgetting to eat. 

Rainbow Recipes aims to solve this issue, targeting students at UH Mānoa, by providing a system that students can use to learn or share quick, simple, and easy to prepare recipes:
* Uses minimal kitchen facilities and supplies.
* Ingredients are available within walking distance of UH.
* Suits local taste.
* Can be filtered via dietary restrictions (gluten-free, vegan, etc).
* Has an estimated cost per serving, estimated number of servings, and estimated prep-time.

### Approach
There are three roles in this system: students, vendors, and admins:
* Students can both search for and contribute recipes.
* Vendors (local grocery stores and/or farmer’s markets) can login and establish a profile including their location and hours. 
* Admins can edit all content in the system, remove inappropriate content, and establish users as having the vendor role.

### Mockup Pages

**Guest Landing Page**

The landing page is the first page presented to visitors when they access the Rainbow Recipes site. It gives a clear introduction to the application, guiding users towards the main features of the website. 

<img src="/images/mockup/landing-page.png" />

**User Log In / Sign Up**

The log in / sign up page provides authentication functionality, allowing users to either access an existing account or create a new one to unlock all of the application's features.

<img src="/images/mockup/log-in-page.png" />

<img src="/images/mockup/sign-up-page.png" />

**Home Pages**

The home page will differ slightly for each user.

A regular, logged in user will have a Recipes, Favorites, and See Vendors tab in the navigation. 

<img src="/images/mockup/user-home-page.png" />

A vendor will have a My Store, Recipes, Favorites, and See Vendors tab in the navigation. The My Store page will allow a vendor to add / update their stock.

<img src="/images/mockup/vendor-home-page.png" />

<img src="/images/mockup/my-store-page.png" />

<img src="/images/mockup/edit-store-page.png" />

An admin will have an Admin, Recipes, Favorites, and See Vendors tab in the navigation. The Admin page will show all users, vendors, and recipes. 

<img src="/images/mockup/admin-home-page.png" />

**Recipes Page**

Recipes will be shown in a grid format each including the name, estimated time to finish, a favorite button, and the rating. A filter and search will be included to make finding specific recipes easier. Users will also be able to add their own recipes.

<img src="/images/mockup/recipes-page.png" />

**Add Recipe Page**

Logged in users will be able to add their own recipes through a form. They will provide the name of the recipe, the estimated time, ingredients, appliances, an image, and instructions.

<img src="/images/mockup/add-recipes-page.png" />

### Use Cases

**User**

<img src="/images/usecase/usecase-user.png" />

**Admin**

<img src="/images/usecase/usecase-admin.png" />

**Vendor**

<img src="/images/usecase/usecase-vendor.png" />

### Entity Relationship Design

<img src="/images/erd.png" />

### Beyond the Basics
After implementing the basic functionality, here are ideas for more advanced features:
* Maps for locating vendors.
* Based upon open hours for vendors, indicate which ingredients can be bought right now.
* Ratings and review system for recipes.
* Ratings and review system for vendors.
* Notification system for vendors when new items are posted in recipes so they can update their listing to indicate whether they stock it or not.
* Notification system when price for a recipe drops substantially (i.e. a vendor puts an item on sale.)

### Risks and Mitigations

* **Poor Communication**:
  Meeting twice a week with team members to discuss the project and progress of tasks. Discussing any concerns, disagreements, or new ideas.
* **Scope Creep**:
  Document changes in implementation and document possible future expectations. Address this to relevant parties to be able to adjust deadlines and other factors accordingly.
* **Unclear Requirements**:
  Make sure to ask clients for clear instructions and examples of what they want. Make sure the clients understand what is possible under their time constraints and budget.
* **Poor Project Planning**:
  Document everything you’re planning, split it into small, manageable parts, and use milestones.
* **Technical Complexity**:
  Ensure all team members have access to the software and hardware needed to build the project.
* **Inadequate Team Skills**:
  Survey technical skill sets beforehand; address any challenges that cannot be overcome even after personal time dedicated to problem-solving.
* **Resource Constraints**:
  Have a larger buffer in areas of high risk and high importance. Document any rising risks and maintain flexibility with resource reallocation.

---

## User Guide

#### Landing Page

This is the landing page that all users see first. In the top left corner you can create an account or sign in. Prospective vendors may access the Vendor Sign Up page to fill out an application to be a vendor. In the navigation you can also access the Recipes page, Vendors page, and About page, as well as view different recipe categories.

<img src="/images/m2/m2-landing-page.png" />

#### Recipes Page

Here you can find all the recipes created by the UH community. On the left you can filter based on food type, appliances, cost, and preparation time. Click on the recipes to access the full instructions or click the heart to favorite it for later. You can aso search for a specific recipe at the top or add your own recipe.

<img src="/images/m2/m2-recipes-page.png" />

#### Vendors Page

The Vendors page shows all the local vendors available for you to purchase ingredients from. Clicking the card for the vendor will lead you to the individual vendor's page.

<img src="/images/m2/m2-vendors-page.png" />

#### Vendor Store Page

In this page you can find the the opening hours and groceries that this vendor sells wiht their prices and availability.

<img src="/images/m2/m2-vendor-store-page.png" />

#### About Page

The About page includes information about how this project came to be and it's purpose.

<img src="/images/m2/m2-about-page.png" />

#### Favorites Page

In the Favorites page you can see all the recipes you have favorited.

<img src="/images/m2/m2-favorites-page.png" />

#### Profile Page

The Profile page is where you can see your personal data as well as edit your profile.

<img src="/images/m2/m2-profile-page.png" />

---

## Developer Guide

### Installation
Download and install PostgreSQL [here](https://www.postgresql.org/download/).

Then create a database using the command,
<pre>$ createdb rainbowrecipes</pre>

### Cloning the Repository
Clone the repository
<pre>$ git clone https://github.com/rainbow-recipes/rainbow-recipes.git</pre>

After cloning install the necessary dependencies
<pre>
$ cd rainbow-recipes
$ npm install
</pre>

### Linking to your database
Make a copy of the `sample.env` file and rename it to `.env`, then set the database URL to point to the database you made in the installation step.

<pre>
DATABASE_URL="postgresql://username:password@localhost:5432/rainbowrecipes"
</pre>

Change your datasource in `/prisma/schema.prisma` to use the right database url
<pre>
datasource db {
  provider = "postgresql"
  // for local development
  url      = env("DATABASE_URL")
  // for Vercel
  // url       = env("POSTGRES_PRISMA_URL")
  // directUrl = env("POSTGRES_URL_NON_POOLING")
}
</pre>

### Running Locally
To run the webpage locally,
<pre>$ npm run dev</pre>

The webpage will ran at [http://localhost:3000](http://localhost:3000)

---

## Milestone 1 

[Milestone 1 Project Page](https://github.com/orgs/rainbow-recipes/projects/1)

**Guest Landing Page**

<img src="/images/m1/m1-landing-page.png" />

**User Landing Page**

<img src="/images/m1/m1-user-landing-page.png" />

**Sign Up & Sign In Page**

<img src="/images/m1/m1-signup-page.png" />

<img src="/images/m1/m1-signin-page.png" />

**Recipes Page**

<img src="/images/m1/m1-all-recipes-page.png" />

**Add Recipe Page**

<img src="/images/m1/m1-add-recipe-page.png" />

**User's Recipe Page**

<img src="/images/m1/m1-users-recipes-page.png" />

**User's Favorites Page**

<img src="/images/m1/m1-favorites-page.png" />

**Vendor's My Store Page**

<img src="/images/m1/m1-mystore-page.png" />

**Admin Page**

<img src="/images/m1/m1-admin-page.png" />

---

## Milestone 2 

[Milestone 2 Project Page](https://github.com/orgs/rainbow-recipes/projects/6)

**About Page**

<img src="/images/m2/m2-about-page.png" />

**Vendors Page**

<img src="/images/m2/m2-all-vendors-page.png" />

**Edit Recipe Page**

<img src="/images/m2/m2-edit-recipe.png" />

**Detailed Recipe Page**

<img src="/images/m2/m2-detailed-recipe-page.png" />

**Profile Page**

<img src="/images/m2/m2-profile-page.png" />

**Vendor Store Page**

<img src="/images/m2/m2-vendor-store-page.png" />

## Milestone 3

[Milestone 3 Project Page](https://github.com/orgs/rainbow-recipes/projects/7)
