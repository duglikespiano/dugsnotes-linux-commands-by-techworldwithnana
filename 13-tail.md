# tail

The tail command in Linux is used to display the last part of a file, defaulting to the final 10 lines. It is a fundamental tool for system administrators and developers, primarily used for monitoring log files in real time.

## usage
`tail filename.txt`  
Displays the last 10 lines of the specified file.

`tail -n [number] filename.txt`
Displays the last [number] of lines. For example, tail -n 20 notes shows the last 20 lines. The -n can often be omitted, e.g., tail -20 notes.

`tail -c [number] filename.txt`
Displays the last [number] of bytes or characters of the file. 

`tail -f filename.log`  
This command displays the last 10 lines and then continues to output new lines as they are appended to the file. The display continues until the user manually stops it by pressing Ctrl + C.

`tail -F filename.log`
Similar to -f, but this option also continues to track the file even if it is renamed, removed, and re-created (a common scenario during log rotation). 

## example
`tail -f /var/log/messages | grep "error"`