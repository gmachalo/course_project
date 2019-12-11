# COURSE PROJECT
## REFERENCE GUIDE FOR GIT, DOCKER, POWESHELL AND BASH COMMANDS

## GIT COMMANDS
1. git init : The 'init' command would create a new git repository for you. If you already have an existing project, 'init' would create a git repository in your working directory.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_init.JPG)

2. git clone : Git clone simply replicates the content of an existing repository, and reproduces it in a new directory
![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_clone.JPG)

3. git branch : Git branch shows a list of all the branches available in a repository. It also shows what branch you are presently on

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_branch.JPG)

4. git add :If you have been working on a branch, you would need to add the files you have been working on to your index before you can stage for a commit.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_add.JPG)

5. git commit : Every time you use git commit,what you are doing is to collate all the file changes you have earlier recorded using git add ,and making it into an object.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_commit.JPG)

6. git checkout : Git checkout is necessary when you want to leave a branch.It moves you to an already existing branch.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_checkout.JPG)

7. git status : This command tells you what branch you are currently on. It identifies all the changes that have been made, and all the changes that have not yet been added and committed to that branch.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_status.JPG)

8. git log : It lists all the previous commits made on that branch, the author, the time and the date of commit. This helps you keep track your activities.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_log.JPG)

9. git pull : Pulling takes files from a remote source and merges them to your local files. That way, you would have access to the same file contents as the remote repository.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_pull.JPG)

10. git push : used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repository.

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/git_push.JPG)

## DOCKER COMMANDS
1. docker -version : This command is used to get the currently installed version of docker

![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_version.JPG)

2. docker pull <image name> : This command is used to pull images from the docker repository(hub.docker.com)
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_pull.JPG)
  
3. docker run -it -d <image-name>: This command is used to create a container from an image
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_run.JPG)
  
4. docker ps : This command is used to list the running containers

  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_ps.JPG)
  
5. docker ps -a : This command is used to show all the running and exited containers

  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_ps_a.JPG)
  
6. docker exec -it <container id> bash : This command is used to access the running container
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_exec.JPG)
  
7. docker stop <container id> : This command stops a running container
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_stop.JPG)
  
8. docker kill <container id> : This command kills the container by stopping its execution immediately
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_kill.JPG)
  
9. docker commit <container id> <username/imagename : This command creates a new image of an edited container on the local system
                                                    
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_commit.JPG)
  
10. docker login : This command is used to login to the docker hub repository 

  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/docker_login.JPG)
 
## POWERSHELL COMMANDS
 1. Get-Help : You can use this command to get help with any other command.
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get-help.JPG)
  
 2. Set-ExceutionPolicy : You can use the Set-ExecutionPolicy command to control the level of security surrounding PowerShell scripts.
  There are 4 levels of security (Restricted,Signed,Remote Signed and Unrestricted). You can set an execution policy by entering the Set-ExecutionPolicy command followed by the name of the policy. For example, if you wanted to allow scripts to run in an unrestricted manner you could type:
  
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/set_execution.JPG)
  
3. Get-ExecutionPolicy : If you're working on an unfamiliar server, you'll need to know what execution policy is in use before you attempt to run a script.

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get-execution.JPG)
 
4. Get-Service : The Get-Service command provides a list of all the services that are installed on the system

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get-service.JPG)
 
5. Get-Command : Get information about anything that can be invoked

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get_command.JPG)
 
6. Get-ChildItem : Gets the items and child items in one or more specified locations.

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get_childitem.JPG)
 
7. Get-Process : You can use the Get-Process command to display a list of all the processes that are currently running on the system.

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get_process.JPG)
 
8. Stop-Process : Sometimes, a process will freeze up. When this happens, you can use the Get-Process command to get the name or the process ID for the process that has stopped responding. You can then terminate the process by using the Stop-Process command.

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/stop_process.JPG)
 
9. Get-Alias : shows you the real name of the native PowerShell command associated with an alias.

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/get_alias.JPG)
 
10. New-Item : creates a new item and sets its value

 ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/new_item.JPG)
 
## BASH COMMANDS
 
 1. ls : Show directory contents, lists names of files.
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/ls.JPG)
 2. mkdir : Creates a directory of the specified name
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/mkdir.JPG)
 3. pwd : Displays the name of the working directory
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/pwd.JPG)
 4. rm :  Removes a specified file. This action is permanent. There is no recycle bin.
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/rm.JPG)
  
 5. rmdir : Removes a directory.
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/rmdir.JPG)
  
 6. history : Display a listing of the last commands you've run.
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/history.JPG)
  
 7. cd : Change directory. Change to certain directory name if provided
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/cd.JPG)
  
 8. cp : Copy specified file to a new named file
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/cp.JPG)
  
 9. touch : Creates a blank file with a specified name.
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/touch.JPG)
  
 10.find : search files and directories. Can use with wildcards (* ? [ ]).
 
  ![alt text](https://github.com/dchangwe/GITDemo/blob/master/images/find.JPG)
=======
## STEP BY STEP TUTORIAL ON HOW TO  USE VIM TO CREATE AND EDIT FILES FROM LINUX COMMAND LINE
STEP 1

Using powershell terminal run the ubuntu container on docker 

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/run_ubuntu.JPG)

STEP 2

Update ubuntu

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/update.JPG)

STEP 3

In order to use Vim ,you have to install it by running apt-get install command

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/install_vim.JPG)

STEP 4

To create the file, you change the directory to point where you have installed vim. 

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/change_dir.JPG)

STEP 5

Then type vim follwed by name of file.

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/create_file.JPG)

STEP 6

The Vim text editor will appear with the name of the file.

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/file_created.JPG)

STEP 7

To save the file type in a colon followed by wq and press enter

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/save_vim.JPG)

STEP 8

To edit files, in the same directory type vim follwed by name of file you want to edit

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/create_file.JPG)

STEP 9

The Vim text editor will appear with the file you want to edit. 

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/open_file.JPG)

STEP 10

Click the letter 'i' on your keyboard to enter INSERT mode in 'vim'.

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/insert_vim.JPG)

STEP 11

Edit the file by typing in the information you want

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/edit_vim.JPG)

STEP 12

When finished editing the file, click the ESC key. This takes you out of INSERT mode and -- INSERT -- disappears from the bottom left of your terminal.

![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/esc.JPG)

STEP 13

 Type in a colon followed by wq and press enter to save the edited file
 
![ Alt text](https://github.com/dchangwe/GITDemo/blob/master/images/save_vim.JPG)
