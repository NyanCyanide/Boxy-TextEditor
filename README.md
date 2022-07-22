# Boxy Editor
A simple editor similar to Vim, where the user can edit and create new files, Which also supports Syntax highlighting from C, C++. 

![Boxy Text Editor Preview](https://raw.githubusercontent.com/NyanCyanide/Boxy-TextEditor/main/Assets/Image1.png?token=GHSAT0AAAAAABWM7O6EXHGGK3JIYFJ4PH3MYW2I4XQ)

### Why did I do this..?
Hmm, okay! I did this for my self learning purpose, I want to know how these Vim, nano and many more text editors are created, So I learnt my self from this [Website](https://viewsourcecode.org/snaptoken/kilo/) or follow in this [Repo](https://github.com/snaptoken/kilo-tutorial). Many Thanks to them!

> What I cannot create, I do not understand - Richard Feynman
### Features
- Text Editor supports for all type of files
-  Syntax Highlighting for '.c' , '.cpp' and '.h' files
-  Find certain text in the file


![Syntax Highlighting for C file](https://raw.githubusercontent.com/NyanCyanide/Boxy-TextEditor/main/Assets/Image2.png?token=GHSAT0AAAAAABWM7O6FLMNY2BGNN3GAMIMUYW2JS2Q)

### Controls

    Ctrl + S	-	Save File
    Ctrl + Q	-	Exit from file or Editor
    Ctrl + F	-	Find Certain Text or word
### Procedure
It is about what are the steps I took to create this

    Step 1 : Disable all controls, such as Ctrl+C and Ctrl+z and many more to avoid termination of program or suspend the program
    Step 2 : Create an Interface where the Windows size is fetched and display ceratin text
    Step 3 : Trying to read files from the existing files
    Step 4 : Trying to Edit the files and also also create one
    Step 5 : Creating Find Feature to the text editor
    Step 6 : Develop Syntax highlighting for Certain extension files
    And voila Text Editor is Done
### Program Execution
To create Executable file

    Make
To Open Text Editor

    ./boxy.exe
To open Existing File

	./boxy.exe <filename>
