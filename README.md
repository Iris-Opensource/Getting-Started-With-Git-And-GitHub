# Welcome to Getting-Started-With-Git-And-GitHub 🎉

We are Glad to have you onboard for this event.

The current iteration of Tech-Matrix has two subdivisions :
* [Getting Started With Git and GitHub]()
* [Hacktoberfest Challenge](https://hacktoberfest.digitalocean.com)

# Getting-Started-With-Git-And-GitHub

It is a 1 hour hand's on workshop where You will get to know about the Git and GitHub. This is a begineer friendly workshop where the only prerequite is to eagerness to learn. Here you will make hand's on contribution and learn your way towards contribution to openSource community. Let's Get Started.

## Making Your First Contribution

**First off, if you don't have git set up on your machine, [install it here](https://docs.github.com/en/get-started/quickstart/set-up-git).** <br/>
Once that's done, come back here and follow these steps ! <br /><br />

   #### 1. Fork this repository
   #### 2. Clone the repository
  Now clone the **forked repository** to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon to copy the url of the repo. <br />
  Open your terminal and run the following git command:<br />
   ```
   git clone <url you just copied>
   ```
Remember to clone **your forked repository** , not the original one.

#### 3. Create a branch

Change to the repository directory on your computer (if you are not already there):<br />
   ```
   cd Getting-Started
   ```
   
   Now create a branch using the git checkout command: <br />
   ```
   git checkout -b your-new-branch-name
   ```
   
 #### 4. Add the necessary details
   
   Woohoo! You're almost there! Open the `contributors-list.md` file and add your name and a little about yourself ! <br />
   
#### 5. Commit your changes

If you go to the project directory and execute the command `git status` in the terminal, you'll see there are changes. <br />
   Add the changed files to the branch you just created using the `git add` command: <br />
   ```
   git add contributors-list.md
   ```

   Now commit those changes using the git commit command:
   ```
   git commit -m "your message"
   ```
   
#### 6. Push your changes to GitHub

Push your changes using the command `git push`:
   ```
   git push origin <add-your-branch-name>
   ```
   
 #### 7. Submit your Pull request for review
 
 Go to your forked repository on GitHub and click on the `Compare & pull request` button. <br />
 Submit your Pull Request, after ensuring that the base repository is `Tech-Matrix/Getting-Started` and head repository is  `<your-username>/Getting-Started` <br/><br />
 
  ### ✨Congrats ! You just made a contribution ! ✨
   All you have to do now is sit tight and wait for us to merge your PR :)
