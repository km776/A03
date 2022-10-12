# A03
## Tutorial - Part 1
Hello there! If you're reading this, I bet you're itching to get your hands messy and delve into the world of computer programming...or you're currently grading my assignment. In that case, hey there, professor! You did say you were behind on grading, though...

#### _Note: I am going to assume you have a computer that runs Windows._

To get started with the magic of programming, we are first going to download an IDE called Webstorm. IDE stands for 'Integrated Development Environment', or in simpler terms, a place where programmers write and develop their applications/code. Visual Studio Code is a more popular example.

Because we are broke students who will not pay for the Webstorm subscription, we're going to use their free individual educational licenses. Just fill in the application [here](https://www.jetbrains.com/shop/eform/students) and make sure you apply using the 'Official document' tab of the application - then, use your NJIT email and send a picture of your Student ID. After a day or two, you should get a confirmation email of your newly available license!

I'll wait.

Just kidding, you can do something else in the meantime - download Git! (And make a GitHub account!)

Head over to this [link](https://git-scm.com/downloads) to open up the download page to install Git. Now, you might be asking:

#### _"Hey, what's the purpose of Git?"_
<sup><sub>(or you might not be asking, in which case, too bad.)</sub></sup>

  **Git** is software that helps manage version control or track changes. It's local, which means it only runs on your system and tracks changes in any set of files. 

  In Git, you can make a **repository**, which allows you to save versions of your code. It acts as virtual storage for your code - repositories can log history, making it very good for a detailed changelog. (You can make repositories in GitHub, too.)
  
#### _"Then, what does GitHub do?"_

Simply put, GitHub is a treasure chest for all of your treasures (repositories, or 'repos' for short). Just as there are many different treasure chests out there, there are different web services that function similarly to GitHub, though this is the most popular service.

GitHub has many functions 
on its service. For one, **branching** allows you to safely develop or test features without risking the functionality of the main application. The _main branch_, formerly known as the main branch, is the most stable version of whatever you're developing.

**Cloning** allows you to duplicate repositories from any branch. It's like having the recipe for a pie, and duplicating that same recipe so you can experiment 
with it during your own time. Note that cloning is just a copy and paste of the history of it too, whereas branching creates new functionalities or updates from a specific, isolated point in time.

Cloning helps when you're the only person making changes in the repository. Branching is better with multiple people. Why? If multiple people were editing the same content and then tried to push their changes, _only the first push would be accepted_. The other edits wouldn't be accepted, and this is called a **merge conflict**. 

Let's say a developer is satisfied with a feature on their isolated branch. They want to bring it to the main branch, or **merge** it into the main branch. This is done with a **pull* request - however, if a repository requires reviews, a request may need a specific number of approvals. 

A different developer is working on another branch, but they want to retrieve some code without changing their current working copy of their repository. They'd use the **'fetch'** command, which downloads the contents of a remote repository. The difference between 'fetch' and 'pull' is that 'fetch' brings local copies and metadata, whereas 'pull' directly changes your copy of the repository. 

Finally, let's say both developers want to show each other their changes. Here's where **'remote'** comes in! This isn't the same as a local repository - instead of providing a display of the project's current state, it allows you to push your changes or pull the changes of others. For context, this is what the 'fetch' command would bring. It's a common repository, or in even simpler terms, the place where your code is stored.

#### _"So what's the difference between Git and GitHub?"_

  Great question! **GitHub** is as the name suggests, a "hub" (community) for many little "git(s)"<sup><sub>(not sure if that's the correct term.)</sub></sup>. It's hosted on the web, which makes it a service, not software. It helps programmers collaborate despite the distance because it's all based in the cloud.
  
Now with all the time I've spent rambling, I'm assuming you've installed Git. Great! Let's move to Github. Click [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2Fpricing&source=header) to be navigated to GitHub's signup page. Use your UCID and school email to get a 'PRO' subscription for free. So far, I'm not exactly sure what it does besides providing a shiny purple label on your profile but hey, it's bound to be better. 

#### _Connecting Git with Webstorm_

If you've gotten this far, I'm assuming you have installed Webstorm and Git, as well as signed up for a GitHub account.

If not, I can wait. I've got better assignments to do in my spare time anyway.

Oh, you're done? That was fast. Back in _my_ day,...

(cough) Ahem. Sorry, indulged in my old spirit there. Open up Webstorm, and pull up Settings (the shortcut is Ctrl+Alt+S). From the left column, select Version Control, then Git. 

Choose the location of your Git file (this path should have 'bin' located somewhere on the path, most likely 'C:\Program Files\Git\bin\git.exe'). Sometimes, Webstorm is smart and can automatically detect Git because it always has its Gitussy out, in which case the path might be C:\Program Files\Git\cmd\git.exe.

Click 'Test' to make sure that Webstorm is connected to Git. You should hopefully (fingers crossed) get the message that "Git Executed Successfully". Woo! Awesome job. Click OK to exit.

#### _Pushing files to GitHub_
On Webstorm's main menu, create a new project for testing purposes. Rename the file - for example, I changed mine to 'inclasstest'. Click 'Create'.

Now it'll ask you to add the file to Git in the form of a dialog box. Clicking 'Add' will add your file to the local file system. You can type in a message as simple as 'Hello World!'. Once you're ready, move to the top of the application and click on 'Git', then 'Commit'. 

**Commit** acts as a camera, taking a 'snapshot' of your entire repository. A commit is an edit to a repository, whether that be one file or a set of files.

From there, you can now push your code to GitHub. Under the same toolbar at the top, press 'Git' once more, then press 'Push'. **Push** is what sends your code from your local system to the community that is GitHub. Anyone can see your revisions there. 

Your file is now on GitHub! Congratulations :)

## Glossary - Part 2 
(Words listed in order of appearance)

* Git: Version control software
* Repository: Virtual storage for code
* Branching: Developing or testing features in an isolated area that doesn't affect the main program
* Cloning: Duplicating repositories from any branch, has the metadata of the repository
* Merge Conflict: A disagreement in edits towards a branch, where multiple developers edit the same content
* Merge: Combines sequences of commits into one unified one (frequently used for two branches)
* Pull: A request in which you inform others of the changes you've made; the goal is to merge but may require approval
* Fetch: Downloads the contents of a remote repository
* Remote: The place where your code is stored - can push your changes or pull the changes of others before any of the other requests happen
* GitHub: A web service that allows for cross-platform collaboration due to hosting repositories on its site
* Commit: An edit to a repository
* Push: The action of sending your revised files from your local system to a code hosting, cloud-based version control platform like GitHub.

## References - Part 3
#### Links for installation:
[Webstorm](https://www.jetbrains.com/shop/eform/students), [Git](https://git-scm.com/downloads)

#### Learning about software
[What is Git?](https://www.nobledesktop.com/blog/what-is-git-and-why-should-you-use-it)

#### References for learning GitHub's markdown:
[Hyperlinks](https://stackoverflow.com/questions/25465182/hyperlinks-of-readme-md-not-working-in-gitlab#:~:text=In%20Github%20the%20syntax%20to%20add%20hyperlink%20is,following%20-%20%5BText%5D%20%28full%20url%20of%20the%20section%29)
[Tiny text](https://gist.github.com/DavidWells/996ff97b915efaf026f72368c3e49185)

#### Differences between...
[Git and Github - StackOverflow](https://stackoverflow.com/questions/13321556/difference-between-git-and-github), 
[Git and Github - GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/#:~:text=Below%20is%20a%20table%20of%20differences%20between%20Git,maintained%20by%20Microsoft.%20%208%20more%20rows%20)
[Cloning and Branching - Github Community](https://github.com/orgs/community/discussions/22286)

#### Installation instructions
[Intro to GitHub - NJIT](https://njit.instructure.com/courses/25694/files/3891026?module_item_id=881262), 
[Additional Instrutions - NJIT](https://njit.instructure.com/courses/25694/files/3891039?module_item_id=881263)

#### Understanding Github's terms
[Commit - search](https://www.bing.com/search?q=what+does+commit+mean+github&cvid=b8d69e26a3fb43e09090173471d1b773&aqs=edge..69i57j0l8.3271j0j1&pglt=299&FORM=ANNTA1&PC=HCTS)
[Branches - search](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches), [Git Branch - W3Schools](https://www.w3schools.com/git/git_branch.asp)
[Cloning - GitHub Docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)
[Pull Requests - GitHub Docs](https://docs.github.com/en/pull-requests), [Defining the mergeability of pull requests - GitHub Docs](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests), [Merging a pull request - GitHub Docs](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request#about-pull-request-merges)
[Git Merge - Atlassian Bitbucket](https://www.atlassian.com/git/tutorials/using-branches/git-merge)
[Fetch - CareerKarma](https://careerkarma.com/blog/git-fetch/#:~:text=The%20git%20fetch%20command%20is%20used%20to%20download,changes%20your%20local%20working%20copy%20of%20a%20repository.)
[About remote repositories - GitHub Docs](https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories), ["What is 'git remote'..."](https://stackoverflow.com/questions/5617211/what-is-git-remote-add-and-git-push-origin-master/5617350#5617350)
