## Lab Report 1

**Part 1: Installing visual studio code**

Step 1: The first thing that must be done is dowloading visual studio code from the official website. You can use this [link](https://code.visualstudio.com/download) and download the appropriate version of visual studio code depending on the number of bits and the operating system that you are using.

Step 2: After installing you can access the zip file from your downloads and open it. This will look as follows (on MacOS):

<img width="290" alt="Screen Shot 2022-04-06 at 10 24 37 PM" src="https://user-images.githubusercontent.com/65454241/162126937-20b53f88-58ea-40e6-8baa-39cd69e07bac.png">

Step 3: Click on the zip file and take the following steps in order to be able to use visual studio and get it on your applications.


**Part 2: Remotely connecting**
Step 1: In order to remotely coonect to the server you must first be able to change your password for your UCSD account, you can do this via tis [link](https://sdacs.ucsd.edu/~icc/index.php). It will look as follows:
<img width="869" alt="Screen Shot 2022-04-06 at 10 45 56 PM" src="https://user-images.githubusercontent.com/65454241/162128846-4452dc50-5626-470f-be9a-33d16e291c2a.png">


Step 2: Once you have done this you should be able to see your unique user code. It would be "cs15l22" followed by three letters that are unique to your account.

Step 3: Open up a terminal and type the following command in order to establish remote control. Also note that the hostname would follow the user and it would be '@ieng6.ucsd.edu'. Refer to the command below.

`$ ssh user@hostname`.

Step 4: After this you will be prompted to enter the password. The password will not actually show. This is expected and you should not worry as the password is hidden for security reasons. If you have correctly entered the password you should be able to enter. After you have logged in, it will look as follows:

<img width="282" alt="Screen Shot 2022-04-06 at 11 15 39 PM" src="https://user-images.githubusercontent.com/65454241/162132654-f1837158-e6a7-413c-9878-994c33aee266.png">


**Part 3: Trying some commands**
After you have connected there are a variety of commands that you could try on the remote server. 

`cd` - is a command that can help you navigate between the directories in the remote server.


`ls` - it is a command that lists all of the files in the current working directory in the remote server. 



You can create files with the following command:
`cat /home/linux/ieng6/cs15lsp22/public/hello.txt`

If you wish to logout of the remote server in your terminal you must run the following commands:
 - Ctrl-D
 - `exit`


**Part 4: Moving files over SSH with scp**
