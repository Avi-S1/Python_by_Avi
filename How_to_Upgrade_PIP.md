## How to Upgrade PIP in Windows

In this column, you’ll get to know about how to upgrade PIP in Windows from scratch.

**Here are the topics to be reviewed:-**

<ol>
  <li> Upgrade PIP in Windows </li>
  <li> Check the version of PIP </li>
  <li> Downgrade PIP to a previous version </li>
</ol>

In order to upgrade PIP in Windows, you’ll need to open the Windows Command Prompt, and then type/copy the command below.   
Note that the following method would only work if you already added Python to Windows path.   
Don’t worry if you don’t know what it means, as you’ll see the full steps to upgrade pip in the next section.
  
        python -m pip install --upgrade pip



***Steps to upgrade PIP in Windows***

(1) First, type Command Prompt in the Windows search box

(2) Next, open the Command Prompt, and you’ll see the following screen with your user name 
(to avoid any permission issues, you may consider to run the Command Prompt as an administrator):  

`C:\Users\Ron>`

(3) In the Command Prompt, type “cd\” to ensure that your starting point has only the drive name:


`C:\Users\Ron>cd\`

(4) Press Enter, and you’ll see the drive name C:\>


`C:\>`

(5) Locate your Python application path, which is the folder where you originally installed Python.

_**Here is an example of a Python application path :point_down:**_

`C:\Users\Ron\AppData\Local\Programs\Python\Python39`

(6) Once you retrieved the Python application path, type the following command in the Command Prompt:

“cd” followed by your Python application path

For our example:  
`C:\>cd C:\Users\Ron\AppData\Local\Programs\Python\Python39`

(7) Press Enter, and you’ll see:   
`C:\Users\Ron\AppData\Local\Programs\Python\Python39>`

(8) To upgrade PIP, type/copy this command, and then press Enter:

          
          
          python -m pip install --upgrade pip

This is how the command would look like in the Command Prompt:   
`C:\Users\Ron\AppData\Local\Programs\Python\Python39>python -m pip install ––upgrade pip`

(9) You’ll notice that the latest version of PIP would be installed:
Successfully installed pip-21.1.1
Steps to check the version of PIP in Windows

To check the version of PIP at any time, you’ll need to use the Python Scripts path, rather than the Python application path.

(1) First, type “cd\” to ensure that your starting point has only the drive name:   
`C:\Users\Ron>cd\`

(2) Then, locate your Python Scripts path. The Scripts folder should be located within the Python application path.

For our example, the Python Scripts path is:   

`C:\Users\Ron\AppData\Local\Programs\Python\Python39\Scripts`

(3) Type “cd” followed by the Python Scripts path (then press Enter):    
`C:\>cd C:\Users\Ron\AppData\Local\Programs\Python\Python39\Scripts`

(4) Finally, type the following command to check the version of PIP:

            
            
           pip --version

For our example:   
`C:\Users\Ron\AppData\Local\Programs\Python\Python39\Scripts>pip ––version`

(5) Press Enter, and you’ll see the PIP version:   
`pip 21.1.1`

## Now, what if you’d like to revert back to a previous version of PIP?

***You can easily downgrade to a previous version of PIP by following the steps below.
Steps to downgrade PIP to a previous version***

(1) Get to the Python application path. If you are currently set to the Python Scripts path, you can 
simply type “cd..” (and then press Enter), and you would revert back to the Python application path:
C:\Users\Ron\AppData\Local\Programs\Python\Python39>

(2) Let’s say that you want to downgrade the PIP version to 18.1

To do that, simply type the following command, and then press Enter:

              
              
            python -m pip install pip==18.1

(3) You should now see the version of PIP that you specified:
Successfully installed pip-18.1
Final Words

If you’re using Anaconda, you may want to check this tutorial that explains how to upgrade PIP in Anaconda.

Finally, if you need to install PIP, you may wanna review the pip documentation.
