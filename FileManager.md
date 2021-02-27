# FileManager

An amazingly useless tool!

This is the **ACTUAL** worst. It's just really basic terminal but without a current directory.

<h2>list</h2>

prompts you to type in the *absolute* path of the directory you want listed. There is no command to check current location or explore the directories, so your only recourse is memorizing the directories. I couldn't even start using it without leaving and checking a window to remember the topmost root is called 'Users'. Even when this command does work, it shows all files including hidden stuff. So finding what you need can be incredibly difficult. Not a good start.

<h2>info</h2>
Better. Still needs an absolute path, but the result tells you various information about the folder in an orderly fashion. What's interesting it is states both the absolute AND relative paths for the directory, implying potential functionality to change the working directory. Neat.


<h2>help</h2>
Gold star, basically tells me what the README file says. Could be better formatted, and give me more info per command. Still probably the most useful command.

<h2>mkdir</h2>
Seems to work just fine, surprisingly. Nees absolute path of new directory, but perfectly functional.

<h2>Copy</h2>
Doesn't seem to work. Prompts me for the path of the file or folder I want to 'move or copy' without ever asking me to clarify which I want.
    
<h2>move</h2>
Just deletes the target file. Same prompt as the copy file without giving the user a chance to choose one or the other.

<h2>rename</h2>
ALSO seems to just delete the target directory.

<h2>delete</h2> 
It works. Deletes end of entered absolute path. Unsurprising.

<h2>quit</h2>
Works as expected, quits file manager. Throws the following text before exiting:

    You're exiting File Manager.
    Process finished with exit code 0

Uncertain why a user would need to know that.