# EpicOverviewTeam

## Table of Contents
-   [General Info](https://github.com/CookIsGood/epicoverviewteam#generalinfo)
-   [Demonstration](https://github.com/CookIsGood/epicoverviewteam#demonstration)
-   [Features](https://github.com/CookIsGood/epicoverviewteam#features)
-   [To-Do](https://github.com/CookIsGood/epicoverviewteam#todo)
-   [How to Run](https://github.com/CookIsGood/epicoverviewteam#howtorun)
-   [Development](https://github.com/CookIsGood/epicoverviewteam#development)
-   [Bug / Feature Request](https://github.com/CookIsGood/epicoverviewteam#bug--feature-request) 
-   [The project status](https://github.com/CookIsGood/epicoverviewteam#theprojectstatus)
-   [Source](https://github.com/CookIsGood/epicoverviewteam#source)
-   [License](https://github.com/CookIsGood/epicoverviewteam#license)


## [](https://github.com/CookIsGood/epicoverviewteam#generalinfo)General Info
![](https://b.radikal.ru/b36/2109/c3/c72160cfc821.png)

This project contains standard features that you expect when buying or putting up for sale a game account in the Epic Seven mobile game of the same name, such as creating and editing your game accounts, viewing all accounts available for purchase, getting up-to-date information on heroes and artifacts in your personal account.

## [](https://github.com/CookIsGood/epicoverviewteam#demonstration)Demonstration
[Here is a demo version of the site](https://epicoverviewteam.herokuapp.com/)

## [](https://github.com/CookIsGood/epicoverviewteam#features)Features
- Creating/editing game accounts
- Displaying information about game accounts
- Displaying information about heroes/artifacts
- Calculating the rating and selecting the account status
- Adding/removing custom user roles/statuses (for the admin)
- Ability to assign roles/statuses to users (for the admin)
- Ability loading of images of heroes/artifacts (for the admin)

### [](https://github.com/CookIsGood/epicoverviewteam#todo)To-Do
- Improve the image loading system (for the admin)
- Add rating system and user reviews
- Improve the search for required hero/artifacts in game accounts.


## [](https://github.com/CookIsGood/epicoverviewteam#howtorun)How to Run
-   Step 1: Make sure you have Python 3.8
    
-   Step 2: Install the requirements: `pip install -r requirements.txt`

-   Step 3: Also write to the a file config.py that mail (gmail.com ) from which it is necessary to send emails. For example: email, password2 = "youremail@gmail.com", "yourpassword"

-   Step 4: Write the following data to the config.py file: 
    -  SECRET_KEY, URL_safe = 'yoursecretkey', 'yoururlsafe'
    -  admin_email, admin_password = "youremail", "yourpassword"
    
-   Step 5: Go to this app's directory and run `python start.py`

## [](https://github.com/CookIsGood/epicoverviewteam#development)Development
Want to contribute? Great!

To fix a bug or enhance an existing module, follow these steps:

-   Fork the repo
-   Create a new branch (`git checkout -b improve-feature`)
-   Make the appropriate changes in the files
-   Add changes to reflect the changes made
-   Commit your changes (`git commit -am 'Improve feature'`)
-   Push to the branch (`git push origin improve-feature`)
-   Create a Pull Request

### [](https://github.com/CookIsGood/epicoverviewteam#bug--feature-request)Bug / Feature Request
If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/CookIsGood/epicoverviewteam/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/CookIsGood/epicoverviewteam/issues/new). Please include sample queries and their corresponding results.

## [](https://github.com/CookIsGood/epicoverviewteam#theprojectstatus)The project status
At the moment, the project is under development, but the main functions have already been added!

## [](https://github.com/CookIsGood/epicoverviewteam#source)Source
The idea to write this site appeared after I saw a [service for choosing characters](http://npc233.com/play/index.php/Home/Game/ep_ss). It was with minimal functionality, and therefore I wanted to write a similar project, but with more advanced functionality, and most importantly, make this service available to ordinary users.

## [](https://github.com/CookIsGood/epicoverviewteam#license)License
GNU GENERAL PUBLIC LICENSE




