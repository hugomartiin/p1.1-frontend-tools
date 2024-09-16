# Practice 1.1 - Installing and configuring Web Development Tools

### 2DAW - DWEC Bilingual. 

> **Student Name**: Hugo Martin Sanchez

#### Files included in this repository:

Ennumerate and explain each one of the files included in this repo.

- File 1
- File 2
- Etc...

#### Instructions: 

- Fill your name and lastname and answer the questions in the current `README.md` file. You have to submit the activity as a GitHub repo link that has to include the 

- You can add images to this tocument with the syntax:

    ```md
    ![Text to display](link/to/the/image)
    ```

- Any other question about Markdown language you can find in the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

### Install and configure VSCode

1. **Install `VSCode` in your computer**.

 ![ ](img/visual.png)

2. **Create a new folder called `p1.1-frontend-tools`and open it as a workspace in VSCode. Copy the current `README.md` inside it**.
 
  ![ ](img/p-1.png)


3. **What functionalities do the following VSCode extensions add?**
   - **Bootstrap 5 quick Snippets**

       It adds a collections of pre-defined snippets for Bootstrap 5.

   - **Live Server**

     Creates a local server to watch the page you are developing in real time.

   - **Prettier**

     It format the code to a determinated style. 

   - **Markdown All in One**

     It brings utilities for the use of markdown like shorcuts, live preview and a table of contents.

4. **Install the extensions listed in the previous point in VSCode**.

  ![ ](img/extensions.png)


5. **What other extensions do you know that you consider interesting for developing in JavaScript**?

JavaScript (ES6) code snippets

6. **Find in VSCode the option in `Settings` to `Format On Save` and activate it. What effect has this option?**

It format the file using the prettier when the file is saved.

### Create a Hello World in JS

7. **Create an `index.html` file inside your worspace folder.**


  ![ ](img/index.html.png)

1. **Create the basic html structure using the `!` snippet and change the title to 'Hello World'**


  ![ ](img/index.png)

2.  **Create a new file called `app.js` and add this two lines**

  ![](img/apps.js.png)

1.  **Import the script in your html using one of the techniques explained in class. Explain here the technique, show the code and justify why did you choose this technique**.
  
  We add the javascript externally.

  ![ ](img/external.png)

  I use this technique because it mantains the html cleaner

2.  **Launch `index.html` in Live Server and check that the script is running. Click right button and select inspect to show the developer tools and take a look on the console.**
   
     ![ ](img/launch.png)

     ![](img/launch%20console.png)

    
3.  **Change some message in the JS code and sava changes. You can check that Live Server refreshes the web page.**

     ![ ](img/launch2.png)


### Create a simple form with Bootstrap 4. 

13. **At this point, we are going to create a page called `form.html` starting from the `Bs5-$` template provided by the Bootstrap extension we added. What files does this template import in the html by default?**
    
It adds the bootstrap css and the bootstrap javascript.

14. **Create a `<div>`with the class `.container` to wrap all the sections in the web page**
  
     ![ ](img/form.png)


15. **Add a standard navigation bar inside the nav area using the `bs5-navbar-standard` snippet inside the container**

     ![ ](img/navbar.png)


16. **Inside the main area create a form using Bootstrap to collect data from a new user who wants to register at an academy that offers courses. We can copy code from [Bootstrap Documentation](https://getbootstrap.com/docs/5.0/forms/overview/)**. 

![](img/form.main.png)

### Install Git, and upload your project to GitHub

17. **Install [git](https://git-scm.com/) in your computer**.
    
![](img/git.png)


18. **Init the git project**
    
![](img/gitinit.png)


19. **Log in to your GitHub account provided by IES Azarquiel**
    
20. **Follow the teacher on GitHub at the following link: [https://github.com/jeatzr/](https://github.com/jeatzr/)**
    
21. **Create a new empty project on GitHub named `p1.1-frontend-tools`.**
    
22. **Follow the instructions in the command line provided by GitHub to add your files, create the first commit and push it. Notice that in out case we have to add all files to the staged area with `git add .`, not just`git add README.md`** 
    
23. **To finish, submit the link of your GH repo to the task in our Classroom.**