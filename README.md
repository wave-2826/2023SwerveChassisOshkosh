# SwerveControllerArrays2023
# FRC2023Competition

# Reset offset values
1. Line up wheels (parrallel, facing forward) with bevel gears facing inward.
2. Look on Shuffleboard to find the abs position of CANcoders (under the CANcoder tab).
3. Change offset value in VS code under Constants - lines 36, 41, 46, and 51.
4. Deploy code to robot.
5. Power cycle the Robot if it does not work.

# Controls
1. "X" toggles field orianted driving (default is off).
2. Left analog stick conrtols forward/backward movement (Y axis), and strafe right/left (X axis).
3. Right analog stick controls rotating/turning left/right (X axis).

# Questions
1. How to run auto and change default commands

# How to add source code to a current repository
1. Create a new folder under C:\Wave2826 and rename it by the repository name in Github.
2. Open folder from Visual Studio Code from WPI.
3. Open a new Terminal in the editor.  
4. Type "git init" in the terminal
5. Type git remote add origin <URL> where URL is the copied from the remote Git repository under Code tab.
6. Type "git pull origin master" to pull surce code from remote repository to local.
7. You may create a new branch. Type "git checkout -b <branch_name>". Your local repository will switch to the new branch. Check at the bottom left of the status bar for the repository name.
8. Copy all source code into the new folder.
9. Type "git status" to see the list of unstaged files and folders.
10. Type "git add ." to stage all unstaged files.
11. Type "git commit -m "somecomments" to commit all staged files and folders
12. Type "git push" to add all commited source code to remote repository <branch_name>
13. Check Github to make sure the new branch is loaded with updated source files.  