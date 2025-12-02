# HW3A Solution - Git and Version Control
## Part 1: Repository Cloning
I successfully cloned the class repository from `https://github.com/olearydj/INSY6500` to
`~/insy6500/class_repo`.
### Key Commands Used
- `git clone <url>` - Create local copy of remote repository
- `git log` - View commit history
- `git remote -v` - Check remote repository connections
## Part 2: Portfolio Repository Creation
I created my personal course repository with:
- Professional README.md describing the project
- Proper .gitignore to exclude unnecessary files
- Organized directory structure for homework, projects, and notes
### Understanding Git Workflow
The three-stage workflow:
1. Working Directory: Where I edit files
2. Staging Area: Where I prepare commits with `git add`
3. Repository: Where commits are permanently stored with `git commit`
## Part 3: GitHub Publishing
Successfully published repository to GitHub:
- Used `git remote add origin` to connect local repo to GitHub
- Used `git push -u origin main` to upload commits
- Verified all files and commits are visible on GitHub
### The Remote Connection
My local repository is now connected to GitHub:
- `git remote -v` shows the remote URL
- `git push` will send my commits to GitHub
- `git pull` will get updates from GitHub (if changes are made on GitHub)
### Details
Complete this section with details from your setup:
- Repository URL: https://github.com/Hannahpatt/py4eda-work.git
- Output of `git remote -v`: origin  https://github.com/Hannahpatt/py4eda-work.git (fetch)
origin  https://github.com/Hannahpatt/py4eda-work.git (push)
- The output of `git log --oneline`: c7443b0 (HEAD -> main, origin/main) Add hw3a solution document
a5e2303 Initial commit: Add README and .gitignore
## Questions
### Reflections
1a. When managing different versions of work previously, I would save off multiple copies of my work,
sometimes all in the same file or folder. When using Git, you furst first the folder you want your new file,
and create it within the folder. This can create some advantages. For instance, using Git can limit the risk
of adding files to the wrong folders since you are making files within the designated folder, rather than
physically moving the file yourself. Another benefit is its ability to provide easy collaboration between
users, whereas without Git teams must share files back and forth with one another to collaborate. 

1b. The Git commit history would have been valuable during my group project in a python class. Using Git
and this history would have been valuable for easy collaboration and quick edits to our group code. FOr
instance, we used google documents to share out code. If there were edits we would have to make comments
within the document which was tedious.

2a. It is important to keep these separated due to their individual purposes. The class_repo is a read-only
reference whereas my_repo is my own work that I pushed to Github. Multiple issues could arise if these two
are not kept separate. For instance, this creates the risk to alter the instructor's files which affects
the course and other students. This can also lead to confusion with commits. For instance, not keeping these
separate can cause the commits to include instructor files/tools and your own work.

2b. I would keep one repo for both team projects and individual assignments. This grants easy access to
version history as well as limits code mix ups between assignments/projects. The only difference is that
the team project would utilize a shared Github repo whereas the indivdual assigment repo would not be shared. 

3a. The second is more useful as it provides more detail onto what exactly was changed. This commit will make
it easier to find exact changes in the future since each chnage will be properly labeled. This will also
make it easier to work with others as the detailed commits allow teammates to recognize what edits have been
made.

3b. To decide when to make a commit, "chapters" of the project need to be decided. First pertains to the data
cleaning. After cleaning the data, it can be made as a commit. This is an example of a good "unit of work"
since only one task is being done. It can be a bad idea to cram multiple tasks into a commit, thus, separating
"units of work" into chapters or tasks is cleaner overall.

### Graduate Questions
1a. It was valuable to stage README.md and .gitignore separately since they both involve creation and setup
of the project files. This is a more logical approach as the respository setup and homework creation
should be in separate commits as they are different additions. One desribes the repository setup and guide
whereas the other is an addition to that repository.

1b. You should commit the code to load data, fix the typo, and update the README file now.  Working on the
analysis of data will only serve fruitful information if the code to load the data is completed, otherwise,
the analysis would be based on wrong/no data. Along with this, a quick typo fix in the comments will
ensure that the code can be understood properly, thus allowing users to assess the code is properly
fixed before analysis is completed. Lastly, the README file can be used as documentation on the changes
made to the code used to load data, thus providing communication regarding the status of the code file.
Staging helps you make this decision becuase it lets the user choose the items that go within a commit.

1c. Using git staus helps you make decisions about what to stage and commit since it shows you all files
(completed or not), what is currently staged, and what is about to be committed. It should be used in your
work flow at any time. For example, it can be used before committing to ensure that the correct work is
set to be committed.

2a. "Distributed" simply means there is a full copy of the respository/files everywhere, meaning every person
who works with the files have a complete copy and history on their own devices. With class_repo and myrepo,
the teacher and student share files remotely and locally, both are entire copies. This is different compared to
google drive/dropbox, in which one copy is shared on a website. 

2b. This is valuable because its lack of need for wifi allows users to work anywhere, with or without wifi.
The users will only need to connect to wifi when pushing or pulling from the repository. This architechture 
is valuable to developers as it enables faster and edit friendly workflow. For instance, as the git 
functions like git status or git help don't require wifi, developers can still maintain fast workflow because
they work instantly and don't require network connection. With this, with and without wifi, developers can
easily make separate files to test new code. If it works or doesn't, the developer can quickly add or remove
these changes locally, later pushing the edits if needed.

2c. Git clone makes a copy of the files within the online remote repository, whereas git pull downloads 
new changes from the online respository and combines it with the local copy that was created with git 
clone. Different from both of these, git push uploads the changes made to the local version of the 
repository to the online remote version. I can pull from class_repo but not push to it because it is 
read-only, meaning the repository is public but not editable. However, I am the "owner" of my_repo, meaning 
I have editing access to both the local and remote versions of the repository. THis means that I can both
pull and push from/to this repository.

3a. As this is a public forum, when considering what to commit, one should take into account the professional
level of their work. This relates to all aspects of the repository, including commit update titles, code
comments, the code itself, and readme files. This work should be presented on a professional level since
potential job interviewers will want to look into the work you have created. With this, while showing the 
process of the workflow (including mistake and iterations) indicates strong problem solving and hands-on
work experience, highlighting too much of this material will make the forum appear cluttered and 
unprofessional. This is where it is key to maintain a healthy balance.

3b. The difference between a readme file for a portfolio repository and an open-sourse project is the 
personal touch. For a portfolio repository, the readme file should introduce the developer, highlight their 
key skills, and layout what can be found in the repository. This differs with an open-sourse project. In this
instance, the readme file should not cover persoanl detail, instead it should highlight the file/code
descriptions as well as how and when to use them.

3c. Developing the portfolio now rather than later has multiple benefits. Not only will this alleviate future
stress during the job search (since it will already be completed), creating the portfolio now will be easier
since the material is fresh. With this, creating it now will show strong skill progress and encourage
students to write cleaner work/code. THis will allow students to develop healthy work habits that will make
the portfolio valuable later. Some of these habits include such creating clearer edit titles, maintaining 
frequent edit updates, and consistent organization of work files.
