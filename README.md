# Cake
What's it take to bake a pretty cake?

## Exercise 1
### First you will each be assigned an ingredient:
* flour
* sugar
* fats (milk, butter, etc)
### Steps
1) You will clone this repository
2) Create a new feature branch for your ingredient
3) Add ONLY YOUR ingredient to the ingredients.txt file:
```
2.75 cups flour
1 tablespoon baking powder
0.75 teaspoon salt
1 cup milk
2 teaspoons vanilla
1 cup butter
1.75 cup sugar
5 eggs
```
4) Commit your new branch and push it up to github
5) Create a pull request against master
### I will merge your PRs in the order they were created
* You will have to fix PRs with perge conflicts

## Exercise 2
### We will do the same thing as exercise 1 for the instructions
* You have the same ingredients assigned
### Steps
1) You will clone (or pull from) this repository
2) Create a new feature branch for your instruction
3) Add ONLY YOUR instruction to the instructions.txt file:
```
Preheat oven to 350°F.
butter cake pan
mix flour, baking powder, salt, milk.
mix in vanilla, butter, and sugar
mix in eggs
pour cake batter into prepared pan
bake at 350 for 30 minutes
make andrew do all the dishes
```
4) Commit your new branch and push it up to github
5) create a pull request against the master
### I will merge your PRs in the order they were created
* You will have to fix PRs with perge conflicts

## Conclusion
* In exercise 1 git is very good at merging simultanious changes on different lines
* In exercise 2 git is slightly less good at merging changes on the same line
* Temporary feature branches (github flow) is the defacto standard for most modern projects
* Persistent branches (git flow) are used where you need to maintain multiple long-lived backwards compatible branches (a library with many different versions) and requires alot more work cherrypicking changes between them
