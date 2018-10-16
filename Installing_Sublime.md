# Installing Sublime Text
### Hello there!
Installing stuff on school computers can be a pain, and a good IDE is important for maximizing your efficieny, so let's go through the process of installing Sublime, the text editor we will be using, on a school computer.
1. Open up the C Drive on your computer by clicking on the Windows icon in the lower left hand corner and typing `C:`, and pressing enter
2. In the toolbar "Home" tab, create a folder called `SublimeText`
3. Open up an instance of command prompt by again clicking the Windows icon and typing `cmd`, and pressing enter
4. Type `powershell` and press enter in cmd
5. When it is done loading, copy/paste the following line into it `Start-BitsTransfer -Source "https://download.sublimetext.com/Sublime%20Text%20Build%203176%20x64.zip" -Destination "C:/SublimeText/Setup.zip"` and press enter
6. Opening up the C Drive again, in the `SublimeText` folder there should be a new folder called `Setup`. Open it up, and doubleclick on the `sublime_text.exe` application, and select `Extract all`, and then `Extract`
7. The Sublime Text application should now be available in `C:/SublimeText/Setup/sublime_text.exe` (note that there will likely be 2 folders called `Setup` at this point, you want the normal `Setup` folder, not the zipped version)


Congratulations, you have now installed Sublime. Now we just have to configure your Python environment! Please note that this process is on a per computer basis, so if you go to a different computer in the school, you may have to repeat this process to install Sublime.
