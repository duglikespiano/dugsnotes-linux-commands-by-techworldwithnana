# grep

The grep command in Linux is a powerful command-line utility used for searching plain-text data for lines that match a regular expression or pattern and printing the matching lines to the standard output. 

Its name stands for "Globally search for a Regular Expression and Print it out".

## options
- -i: Perform a case-insensitive search (ignore distinctions between uppercase and lowercase letters).
- -v: Invert the match; select lines that do not match the pattern.
- -n: Prefix each matching line with its line number.
- -c: Only print a count of the lines that match a pattern, not the lines themselves.
- -r: Recursively search through files in the current directory and all subdirectories.
- -E: Interpret the pattern as an extended regular expression (ERE). This is equivalent to using the egrep command.
- -o: Print only the matched (non-empty) parts of a matching line, with each such part on a separate output line.
- -A n: Print n lines of After context after the matching line.
- -B n: Print n lines of Before context before the matching line.
- -C n: Print n lines of Context (before and after) around the matching line. 

## usage
`grep "specific_word" filename.txt`
searches for "specific_word" in filename.txt.

## example
`ls -l | grep "Dec"` uses a pipe (|) to filter the output of the `ls -l` command, showing only lines containing "Dec".