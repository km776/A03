# A03
## Tutorial - Part 1
Hello there! If you're reading this, I bet you're itching to get your hands messy and delve into the world of computer programming...or you're currently grading my assignment. In that case, hey there, professor! You did say you were behind on grading, though...

#### _Note: I am going to assume you have a computer that runs Windows._

To get started with the magic of programming, we are first going to download an IDE called Webstorm. IDE stands for 'Integrated Development Environment', or in simpler terms, a place where programmers write and develop their applications/code. Visual Studio Code is a more popular example.

Because we are broke students who will definitely not pay for the subscription of Webstorm, we're going to use their free individual educational licenses. Just fill in the application [here](https://www.jetbrains.com/shop/eform/students) and make sure you apply using the 'Official document' tab of the application - then, use your NJIT email and send a picture of your Student ID. After a day or two, you should get a confirmation email of your newly available license!

I'll wait.

Just kidding, you can do something else in the meantime - download Git! (And make a GitHub account!)

Head over to this [link](https://git-scm.com/downloads) to open up the download page to install Git. Now, you might be asking:

#### _"Hey, what's the purpose of Git?"_
<sup><sub>(or you might not be asking, in which case, too bad.)</sub></sup>

  **Git** is software that helps manage version control, or track changes. It's local, which means it only runs on your system, and tracks changes in any set of files. 

  In Git, you can make a **repository**, which allows you to save versions of your code. It acts as virtual storage for your code - repositories can log history, making it very good for a detailed changelog. (You can make repositories in GitHub, too.)

#### _"So what's the difference between Git and GitHub?"_

  Great question! **GitHub** is as the name suggests, a "hub" (community) for many little "git(s)"<sup><sub>(not sure if that's the correct term.)</sub></sup>. It's hosted on the web, which makes it a service, not software. It helps programmers collaborate despite distance, because it's all based in the cloud.

  Simply put, GitHub is a treasure chest for all of your treasures (repositories, or 'repos' for short). Just as there are many different treasure chests out there, there are different web services that function similarly to GitHub, though this is the most popular service.
  
Now with all the time I've spent rambling, I'm assuming you've installed Git. Great! Let's move onto Github. Click [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2Fpricing&source=header) to be navigated to GitHub's signup page. Use your UCID and school email to get a 'PRO' subscription for free. So far, I'm not exactly sure what it does besides provide a shiny purple label on your profile but hey, it's bound to be better. 

#### _Connecting Git with Webstorm_

If you've gotten this far, I'm assuming you have installed Webstorm and Git, as well as signed up for a GitHub account.

If not, I can wait. I've got better assignments to do in my spare time anyway.

Oh, you're done? That was fast. Back in _my_ day,...

(cough) Ahem. Sorry, indulged in my old spirit there. Open up Webstorm, and pull up Settings (shortcut is Ctrl+Alt+S). From the left column, select Version Control, then Git. 

Choose the location of your Git file (this path should have 'bin' located somewhere on the path, most likely 'C:\Program Files\Git\bin\git.exe'). Sometimes, Webstorm is really smart and can automatically detect Github because it always has its GitHussy out, in which case the path might be C:\Program Files\Git\cmd\git.exe.

Click 'Test' to make sure that Webstorm is connected to Git. You should hopefully (fingers crossed) get the message that "Git Executed Successfully". Woo! Awesome job. Click OK to exit.

#### _Pushing files to GitHub_
On Webstorm's main menu, create a new project for testing purposes. Rename the file - for example, I changed mine to 'inclasstest'. Click 'Create'.

Now it'll ask you to add file to Git in the form of a dialog box. Clicking 'Add' will add your file to the local file system. You can type in a message as simple as 'Hello World!'. Once you're ready, move to the top of the application and click on 'Git', then 'Commit'. 

**Commit** acts as a camera, taking a 'snapshot' of your entire repository. A commit is an edit to a repository, whether that be one file or a set of files.

From there, you can now push your code to GitHub. Under the same toolbar at the top, press 'Git' once more, then press 'Push'. **Push** is what sends your code from your local system to the community that is GitHub. Anyone can see your revisions there. 

Your file is now on GitHub! Congratulations :)

## Glossary - Part 2 
(Words listed in order of appearance)

* Git: Version control software
* Repository: Virtual storage for code
* GitHub: A web service that allows for cross-platform collaboration due to hosting repositories on its site
* Commit: An edit to a repository
* Push: The action of sending your revised files from your local system to a code hosting, cloud-based version control platform like GitHub.

## References - Part 3
#### Links for installation:
[Webstorm](https://www.jetbrains.com/shop/eform/students)

#### Learning about software
[What is Git?](https://www.nobledesktop.com/blog/what-is-git-and-why-should-you-use-it)

#### References for learning GitHub's markdown:
[Hyperlinks](https://stackoverflow.com/questions/25465182/hyperlinks-of-readme-md-not-working-in-gitlab#:~:text=In%20Github%20the%20syntax%20to%20add%20hyperlink%20is,following%20-%20%5BText%5D%20%28full%20url%20of%20the%20section%29)
[Tiny text](https://gist.github.com/DavidWells/996ff97b915efaf026f72368c3e49185)

#### Difference between Git and Github
[Stackoverflow](https://stackoverflow.com/questions/13321556/difference-between-git-and-github), 
[GeeksforGeeks](https://www.geeksforgeeks.org/difference-between-git-and-github/#:~:text=Below%20is%20a%20table%20of%20differences%20between%20Git,maintained%20by%20Microsoft.%20%208%20more%20rows%20)

#### Installation instructions
[Intro to Github - NJIT](https://njit.instructure.com/courses/25694/files/3891026?module_item_id=881262), 
[Additional Instrutions - NJIT](https://njit.instructure.com/courses/25694/files/3891039?module_item_id=881263)

#### Understanding Github's terms
[Commit](https://www.bing.com/search?q=what+does+commit+mean+github&cvid=b8d69e26a3fb43e09090173471d1b773&aqs=edge..69i57j0l8.3271j0j1&pglt=299&FORM=ANNTA1&PC=HCTS)
