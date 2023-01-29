## unix_session_task.

#this is all about how can we clone this repo and then how we setup environment for the repo on our local system.

## HOW TO CONTRIBUTE ? 👷 OR CLONE(AND PERFORM OPREATIONS ON FILES IN TERMINAL USING COMMANDS.) ? 

**1.** Fork [this](https://github.com/rahul-habile/unix_session_task/fork) repository.

**2.** Clone the forked repository (you can clone it by executing following command in computer terminal or in VSCode terminal on home or in pwd).

```terminal
git clone https://github.com/rahul-habile/unix_session_task.git 
```

**3.** Navigate to the project directory.

```terminal
cd unix_session_task
```
**4.**  MAKE A NEW FOLDER WITH YOUR PROJECT NAME INSIDE unix_session_task & Add your project files (eg: index.html ,style.css, script.js) inside that folder
<br>

**5.**  Also Add a README file in your project folder which consists of Description/screenshots about your project !
          
 
<br>

**6.** OR You Can Navigate to the project directory(for edit the existing files eg: index.html ,style.css, script.js).

```terminal
cd task2_22.12.22_gamil_copy_using_table_in_html
```
**7.** You Can Get All Files Inside Your Current Folder Or PWd By Executing Following Command.

```terminal
ls
```
**8.** You Can Create New File(eg: fliename.html ,filename.css, filename.js)  Inside Your Current Folder Or PWd By Executing Following Command.

```terminal
touch <your file name>
```

**9.** You Can Edit Your New Created File Or Existing File In Vim Or Nano Editor(eg: fliename.html ,filename.css, filename.js, index.html ,style.css, script.js)  Inside Your Current Folder Or PWd By Executing Following Command.

```terminal
vim <your file name>
```

**10.** Type "/" and then the name of the value you would like to edit and press Enter to search for the value in the file.
<br>

**11.** Type "i" to enter insert mode.
<br>

**12.** Press ESC and then type ":wq!" then press Enter to save the changes and exit vim (If you would like to exit the file without making any changes press ESC, then type ":q!" and press Enter.).
<br>

**13.** You can also find particular files inside you current folder or PWD by executing.

```terminal
ls *.<extension of the file you want to search>
```

**14.** You can rename a particular file inside you current folder or PWD by executing.

```terminal
mv <current name> <new name>
```

**15.** You can move  a particular particular file inside you current folder or PWD to another destination or another destination to your folder by executing.

```terminal
mv <file name> <directory name> 
OR
mv <directory name> <file name>
```

**16.** You can also remove a particular file  inside you current folder or PWD by executing following command. 

```terminal
rm <file name>
```

**17.** You can also count the number of char of a particular file  inside you current folder or PWD by executing following command. 

```terminal
wc <file name>
```
**18.** You can also make a new directory by executing following command. 

```terminal
mkdir <directory name>
```
**19.** Navigate to the directory 

```terminal
cd <directory name>
```
**20.** Move Your Project To New Directory By Executing The Following Command. 

```terminal
mv <folder name> <new directory name>
OR IN CASE OF DIRECTORY TO DIRECTORY
mv -rf <directory name> <new directory name>
```
##So now your project ready to push on git(You can use following steps to upload your project on GitHub).
<br>

**21.** Create a new branch.

```terminal
git checkout -b <your_branch_name>
```

**22.** Add & Commit your changes.

```terminal
  git add .
  git commit -m "<your_commit_message>"
```

**23.** Push your local branch to the remote repository.

```terminal
git push -u origin <your_branch_name>
```

**24.** Create a Pull Request!

<br>
## OR YOU CAN UPLOAD IT TO NEW REPO WHICH YOU CREATED IN YOUR GitHub ACCOUNT.
<br>


**25.** Initialze git by executing.

```terminal
git init
```
**26.**  Add a README file in your project folder which consists of Description/screenshots about your project by executing.

```terminal
git add README.md
```
**27.**  Add your all files  by executing.

```terminal
git add .
```

**28.** For branch execute.

```terminal
git branch -M <branch name>
```
**29.** Add remote repository by executing.

```terminal
git remote add origin <your remote origin address>
```
**30.** Push your local branch to the remote repository.

```terminal
git push -u origin <your_branch_name>
```
**Congratulations!** Sit and relax your project now uploded in your remote repo.

<br>


