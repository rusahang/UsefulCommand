**print working directory**
The pwd command allows you to print the current working directory on your terminal. It’s a very basic command and solves its purpose very well.
**limbu@ubuntu:~$ pwd**
**/home/ubuntu**

**Change directory**
While working within the terminal, moving around within directories is pretty much a necessity. The cd command is one of the important Linux commands you must know, and it will help you navigate through directories. Just type cd followed by directory, as shown below.
### limbu@ubuntu:~# cd <directory path>

**Create directories**

The **mkdir** command allows you to create directories from within the terminal.

### limbu@ubuntu:~# mkdir <folder name>

**create Github a new repository on the command line**

echo "# YourRepo" >> README.md <br/>
git init <br/>
git add README.md <br/>
git commit -m "first commit" <br/>
git branch -M main <br/>
git remote add origin git@github.com:<username>/YourRepo.git <br/>
git push -u origin main

**or push an existing repository from the command line**

git remote add origin git@github.com:rusa<username>/YourRepo.git <br/>
git branch -M main <br/>
git push -u origin main <br/>


**How to Update GitHub Repository**

Navigate to the repository you want to update.
**limbu@ubuntu:~/Documents/UsefulCommand$**

Type the following command to add new files to the staging area before making your commit:
git add **Enter**
**limbu@Limbu:~/Documents/UsefulCommand$ git add YourFile**

Next, enter the following commands while substituting the appropriate commit message:
git commit -m "Your commit message here" **Enter**
git push origin main **Enter**