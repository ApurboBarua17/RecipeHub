# RecipeHub

This is our final project for CS337. RecipeHub is a simplistic recipe-sharing web application where users can register, log in, submit their recipes, and browse recipes submitted by other users. The application is built in Node.js and Express and employs basic session handling and JSON file storage for its data. Logged-in users may add a recipe via a small form provided. Recipes are given a title, ingredients, steps, and optionally an image. Recipes are visible to all users, irrespective of whether they are logged in or just guests

# Authors  
Ashutosh Dayal  
Apurbo Barua

# Dependencies  
Node.js  
Express.js  
express-session  


# How to run this program
# 1. Install required packages
npm install express express-session
# 2. Run the server
node server.js
```
go to:

```
http://localhost:3000
```

---

### Usage  
- Register a user at `/register` page.  
- Log in and access the recipe submission form.  
- Add recipes with title, ingredients, steps, and image URL (optional).  
- Browse all recipes from the homepage or at `/recipes/view`.  
- Logout once you're done so the session can be cleared securely.

---

### Features  
- User login and registration with session support  
- Add and view recipes  
- Recipe data stored in JSON files  
- Protected routes for authenticated users  
- Responsive and clean UI with a simple layout
