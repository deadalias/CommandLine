Command Line
================

When you double click on a folder to open it, you are using the Graphical User Interface of an operating system. Most people find the GUI easy and intuitive. There is another way to open folders using the Command Line Interface. Most people find the CLI more confusing at first, but it can be faster and more powerful than the GUI. In this assignment we'll practice using the CLI to make some folders. Modern operating systems have both a CLI and a GUI. They are called different things in different operating systems, so we will start with some vocabulary:

<table style="width:100%">
  <tr>
    <td><strong>Operating System</strong></td>
    <td><strong>CLI</strong></td> 
    <td><strong>GUI</strong></td>
    <td><strong>a folder is called</strong></td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>Command Prompt</td> 
    <td>File Explorer</td>
    <td>folder</td>
  </tr>
  <tr>
    <td>MacOS</td>
    <td>Terminal</td> 
    <td>MacOS Finder</td>
    <td>folder</td>
  </tr>
  <tr>
    <td>Unix</td>
    <td>shell or bash</td> 
    <td>too many to list here</td>
    <td>directory</td>
  </tr>
</table>

The Unix CLI is especially powerful. We are going to use a program called Git Bash that lets us use Unix CLI commands on a Windows computer. The Unix commands you will use in this assignment are:

`cd ~`					Change to the home directory (open the home folder)  
`cd ..`					Navigate up ("go back") one folder  
`cd <some folder>`	Open the folder named \<some folder\>  
`pwd`					Present Working Directory (the current folder)  
`ls`						List the contents of the current folder  
`mkdir`					Make a new folder  
`rmdir`					Remove an empty folder  

In this assignment you are going to create some folders. You will then take a picture of those folders with a screen shot. You will submit the screen shot to show that you have completed the assignment. You may find the PowerPoint slides 101 to 110 of the [apjavaProcessing.pptx](https://drive.google.com/file/d/1ycy6BhFFv7j2X2hooCPa4QpTbgh-TgmN/view?usp=sharing) presentation helpful.

**Step 1: Open Git Bash**

One way to open Git Bash is to click on the Start Menu and choose *All Programs | Git | Git Bash*

**Step 2: Open Windows File Explorer**

One way in Windows to open the File Explorer is to click on the Start Menu and click on *File Explorer*

**Step 3: Arrange the two windows so they are about the same size and side by side**

Your two windows should look like this  
![Image 1](/images/CLI1.png)

**Step 4: Navigate to the My Documents folder in Windows File Explorer**

"Navigate" in this context means "to go there." One way is to click on Documents under Computer in the left of the Windows Explorer window. This opens the My Documents folder to let us see its contents. So we just "navigated" to the My Documents folder.

**Step 5: Navigate to and show the contents of the My Documents folder in Git Bash**  

The following four commands should help you navigate to your documents folder. Note that you should replace `< your sfusd username >` with your sfusd username *without* the `<` and `>`.  
`cd c:`  
`cd users`  
`cd < your sfusd username >`  
`cd documents`   
![Image 2](/images/CLI2.png)

**Step 6: Use Git Bash to create a new folder called junk**

One way is to type the command `mkdir junk` (which means to make a new directory called junk) and then type the command `ls` to list the contents of the directory. Notice that the folder junk also pops up in Windows Explorer on the right. It's very important to realize we are looking at the same folder two different ways. Git Bash and Windows Explorer are actually very similar. Your two windows should look like this:  
![Image 3](/images/CLI3.png)

**Step 7: Use Git Bash to delete the folder  junk**

One way is to type the command `rmdir junk` (which means to remove the directory called junk). Again, notice that the folder junk is deleted from Windows Explorer on the right as well. And again, it's because we are looking at the same folder two different ways.  Your two folders should look like this:
![Image 3.5](/images/CLI35.png)

**Step 8: Use Git Bash to create a new folder called apjava**

See step 6 for one way of doing this

**Step 9: Navigate to the apjava folder in Git Bash**

One way is to type the command `cd apjava`. Then type the command `pwd` to confirm that your present working directory is apjava.

**Step 10: Navigate to the apjava folder in Windows Explorer**

One way is to double click on the apjava folder to open it. Your two windows should look like this:  
![Image 4](/images/CLI4.png)

**Step 11: Using Git Bash, create three folders in the apjava folder**

The three folders should have one word names that match:  
Your first name  
The month of your birthday  
Your favorite fruit  

See if you can do it without going back and looking at Step 6 again. You should see something similar to the following picture with differently named folders  
![Image 5](/images/CLI5.png)

**Step 12: Using Git Bash, navigate into the folder with your name and then navigate back out**

Type the following four commands in this order  
`cd <your first name>`  
`pwd`  
`cd ..`  
`pwd`  

**Step 13: Remove the folder with the same name as the month of your birthday**

See if you can do it without looking back at step 7.

**Step 14: Take a screen shot and save it**

One way to do this in Windows Explorer is with the snipping tool. In Windows 7 click the Start button, and then click Snipping Tool. Click and drag to capture the two windows and then choose *File | Save*. Your screenshot should look similar to the one below.  
![Image 6](/images/CLI6.png)

**Step 15: Submit your screenshot to google classroom**     
You're all done!
