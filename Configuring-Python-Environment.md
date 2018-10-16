# Configuring your Python Environment
If by now you don't have Sublime or some equivalent IDE installed, you will likely have to update your `PATH` environment variable in order to be able to run Python scripts on it, so let's do that now. Please note that this will be on a per account, per computer basis, so if you log on to another computer in the school, you will have to do this stuff again to get Python working.    
  
This sounds harder than it actually is. Chaging the value of your `PATH` environment variable, is so that when you run a Python file, it knows where to look for an interpreter. This is acheived through 2 simple commands in the command prompt.
1. Open up command prompt by clicking the Windows icon in the lower left hand corner of the screen and typing `cmd`, and hitting enter
2. Copy paste the following command into cmd: `setx PATH "%PATH%;C:/...`, and hit enter (you should get some message like `The specified value was saved`)
3. Close cmd
4. Open cmd again as in step 1, and copy paste `setx PATH "%PATH%;C:/...", into cmd and hit enter

That wasn't so bad! Now you should be able to open Sublime (see Installing_Sublime.md), and create a new file
