# cs-gsc-hackathonS2023
Computer Science Hackathon Spring 2023 -- 
Group Members
---------------
-Dominik Chally
-Kayley Clark
-Manas Mathur
-Max Mayer-Mader

Project Idea - Pantry Pal
-------------
A web application to effortlessly manage your grocery list and discover delicious new recipes with our user-friendly web application that seamlessly tracks available recipes and stores with corresponding recipes. Users will be able to log into an account, log specific recipes they like and also be able to track what groceries they need.

Main features
----------------
- Tracking groceries/ingredients
   - Have a seperate list that shows when you bought a certain item.
- Creating a catalog of saved/liked recipes
- Find/display recipes with ingredients you have
   -(for demo we are going to have fixed recipe list)
- Being able to match ingredients with recipes containing those ingredients

Additional Features
--------------------
- Have recipes from web 
- If you are missing ingredients show recipes close
- Show subtitute recipes.
- Option on recipe not saved to add all ingredients to grocery list


TO-DO List
---
Dominik- figure out account and how to store user data (i.e. Their grocery list and recipe list)

Goal For tonight
----------



Git commands
------
cloning a repo
git clone <url of repo>



Branching
I followed this tutorial if you want to understand more, there are pictures
   https://www.freecodecamp.org/news/how-to-use-git-and-github-in-a-team-like-a-pro/
---
1. When about to make some changes you always want to make sure you are up to date with the current repository. To do so call .\n
   git pull        (do this a lot so you are always up to date)
2. We want to work on a specific branch so we are not all pushing changes to the main branch so we can review the code. To do so look on GitHub website and look at the issues tab. once you know what you need to work on (If there is not already a branch made for you) create a new branch naming it the issue. 
3. You Then want to make your git to the new branch. Do so by changing your branch by
    git checkout <name-of-branch>
4. Once you are in branch you can then start working on the file and do your changes.
5. Once you have solved the problem you want to\n
   git add .
6. Then you want to commit the changes with\n
   git commit -m <message of commit>
7. then you want to push the commit with\n
   git push
8. Then there should be a pull request on the GitHub navBar and then review and then merge. once it has merge you can delete the branch.


