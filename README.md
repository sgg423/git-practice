# Lecture_5 NOTE
#### -I/O Redirection: Standard Output
- By default, standard output is screen.
- You can redirect output using “>” after a command (e.g., ls) to create and save the
output in a file
- Command “cat” displays the content of a text file.
- Using “>>” appends output to an extising file (if it already exitsts),
or create and write to a new file if it doesn’t exist.
#### -I/O Redirection: Standard Input
- By default, standard input is from keyboard.
- You can redirecct input from a file using “<”.
- You can mix “<“ and “>” together in a single line.
#### -Pipelines “|”
- Pipeline feeds output of previous command to input of next command.
- command1 | command2 | command3 | … 
- Press “q” key to exit the screen
#### -Superuser
- A superuser has all system administation authority.
- Some commands need superuser’s privilleges.
- Put “sudo” before the command if you are a superuser.
- Type “exit” to get out of a superuser session.
#### -Text Editors
##### In Linux, you can choose CLI-based or GUI-based text editors.
- vi, vim -> The granddaddy of Unix text editors, vi, is infamous for its obtuse user interface. On the bright side, vi is powerful, lightweight, and fast. Learning vi is a Unix rite of passage, since it is universally available on Unix-like systems. On most Linux distributions, an enhanced version of vi called vim is provided in place of vi. vim is a remarkable editor and well worth taking the time to learn it.
- Emacs -> The true giant in the world of text editors is Emacs originally written by Richard Stallman. Emacs contains (or can be made to contain) every feature ever conceived of for a text editor. It should be noted that vi and Emacs fans fight bitter religious wars over which is better.
- nano -> nano is a free clone of the text editor supplied with the pine email program. nano is very easy to use but is very short on features compared to vim and emacs. nano is recommended for first-time users who need a command line editor.
- gedit -> gedit is the editor supplied with the GNOME desktop environment. gedit is easy to use and contains enough features to be a good beginners-level editor.
- kwrite -> kwrite is the "advanced editor" supplied with KDE. It has syntax highlighting, a helpful feature for programmers and script writers.
### TIP
#### -Backslash
- Backslah can be used to ignore line change in command (“enter”),
to enter a long command in multiple lines.
#### -History
- Type “history” to see previous command history.
- Or, save it to a text file
