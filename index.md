# CSE 15L Lab Report
Hello incoming CSE 15L students! This is a tutorial on how to log into your course-specific account on ieng6.
### Step 1: Installing VScode
Go to the [Visual Studio Code Website](https://code.visualstudio.com/) and download the application for your OS.  
Once you install and open the app, you should see something like this: 

![image](https://user-images.githubusercontent.com/92767729/162376153-cacdee3f-10c1-4256-b595-20c74097653e.png)  
  
### Step 2: Remotely Connecting to ieng6  
First, if you are using Windows, you will need to install [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse) so that your computer can connect to other computers.  
Afterwards, look up your course-specific account for CSE15L [here](https://sdacs.ucsd.edu/~icc/index.php)  
Then, open VScode and open the terminal with the terminal -> new terminal menu option.  
Once the terminal is opened, enter the following command, with the zz replaced by the letters in your account.  
ssh cs15lsp22zz@ieng6.ucsd.edu  
If it is your first time connecting to the server, you will probably get a message stating that the authenticity of the host 'ieng6.ucsd.edu' can't be established.  
Respond yes to the prompt that asks if you want to keep connecting.  
Then you should be prompted to type in your password. If it is correct, your terminal will print out something like this:  
  
![image](https://user-images.githubusercontent.com/92767729/162377584-7fe5c2bc-7546-4645-b202-8894c4eae364.png)

### Step 3: Run Some Commands
Some commands you can run are cd, ls, pwd, mkdir and cp. These commands can be run on both your computer and the remote computer and do different things.
For example, the ls -a command prints out all the files in the directory, including hidden files.  
![image](https://user-images.githubusercontent.com/92767729/162378057-8c96c433-86f4-490c-bcbe-5000f91cabb0.png)



