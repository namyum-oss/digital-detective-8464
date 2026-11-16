# Mission 2

## Task 2.1 - Explore Basic Terminal Operations

| Operation | Command | What it does | What I observed |
|---|---|---|---|
| Current-directory display | `pwd` | Shows the full path of the folder I'm currently in. | It showed the location of my project folder. |
| Directory listing | `ls` | Lists files and folders in the current location. | It displayed the files and mission folders. |
| Detailed listing | `ls -l` | Shows files with extra details like permissions, size and modification date. | It displayed more information than the normal listing. |
| Change directory | `cd ..` | Moves to the parent folder. | My location changed to the folder containing my project. |
| Create directory | `mkdir practice` | Creates a new folder named practice. | A new practice folder was created. |
| Create empty file | `touch practice/notes.txt` | Creates an empty text file inside the practice folder. | An empty notes.txt file was created. |
| Copy file | `cp practice/notes.txt practice/notes-copy.txt` | Creates a copy of the original file with a different name. | A second file was created. |
| Move / rename file | `mv practice/notes-copy.txt practice/renamed-notes.txt` | Renames a file. | The copied file was renamed. |
| Display file contents | `cat practice/notes.txt` | Displays the contents of a file. | It displayed nothing because the file was empty. |

## Task 2.2 - Practise file changes safely

1. Replacing a file's contents removes the previous content and writes new content. Adding text to the end keeps the existing content and adds the new text after it. > replaces, while >> appends.
2. Copying creates a duplicate of a file while keeping the original. Moving transfers a file to another location or changes its name. cp copies, while mv moves or renames.
3. The current-directory display shows the full path of the folder I am currently working in. The pwd command displays this information.
4. A directory listing shows the files and folders present in the current location. It helps me understand the contents of a directory and find the files I need.
   
## Task 2.4 – Understand Package Managers

A package manager is a tool that helps install, update and remove software. Homebrew is a commonly used package manager on macOS. It makes software management easier by handling packages and their dependencies in one place.
