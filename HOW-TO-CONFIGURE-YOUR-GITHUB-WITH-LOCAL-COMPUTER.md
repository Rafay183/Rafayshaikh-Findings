HOW TO CONFIGURE YOUR GITHUB ACCOUNT WITH LOCAL COMPUTER 



Step 1: Create an account on https://Github.com by signin up / or signin

Step 2: Create Repository of any name your want to create by click "NEW" button their and so on write any link name at the start "Yourusername/<create link>"
 --  Donot select anything and click to "create Repository"


 Step 3: Download Git local on your system .. by accessing this link https://git-scm.com/downloads 

 Step 4: Install the setup of Git local (if windows, 64bit setup <downloaded from the above link>)

Step 5: after installing Git successfully without selecting anything. 
 -- Create a folder in which you want to start creating project to which you want to remotely connect origin with your github repository.. 

 Step 6: type CMD on the above created folder's address bar and enter 

 Step 7: Now, accessing Command prompt in your front directed to the folder you created in your local pc

 Step 8: type "Git init" --- Your will see this message after entering the command -> Initialized empty Git repository in <your folder directory>

 Step 9: Now, you just need to configure your email and user name of your github account

 Step 10: git config --global user.email "youremail@yourdomain.com"

 Step 11: git config --global user.name "Your Name" 

 Step 12: 
 
 git init
 git add README.md
 git add remote origin <your repository link>
 git branch -M main
 git push origin main 


 Step 13: you will get your authorization "by signing in on your browser"

Step 14: click "Authorize Ecosystem"


Thats all!

