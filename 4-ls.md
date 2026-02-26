# ls

The ls command is a fundamental Linux command used to list the contents of a directory.

When executed without any options, it displays the files and subdirectories within your current working directory in alphabetical order.

## options
- -l (long format): Provides a detailed list of information for each item, including file permissions, number of links, owner name, group name, size (in bytes), and time of last modification.
- -a (all): Includes hidden files and directories in the output. In Linux, hidden items have names that start with a dot (.).
- -h (human-readable): Used with the -l option (ls -lh), it displays file sizes in human-readable units like KB, MB, or GB, instead of just bytes, making them easier to read.
- -t (time sort): Sorts the files by modification time, with the most recently modified files appearing first.
- -r (reverse): Reverses the sorting order. For example, when used with -t (ls -ltr), it lists files with the oldest first.
- -F (classify): Appends a symbol to the end of each name to indicate the file type (e.g., a slash (/) for a directory, an asterisk (*) for an executable file).

## example
`ls -ltr`