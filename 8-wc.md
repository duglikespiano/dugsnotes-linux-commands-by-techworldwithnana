# wc

The wc command in Linux (short for word count) is a command-line utility used to count the number of lines, words, characters, and bytes in a file or from standard input. 

## options
| Option |	Description	|
| --------- | --------- |
| -l or --lines | Prints only the line count. |
| -w or --words | Prints only the word count. |
| -c or --bytes | Prints only the byte count. |
| -m or --chars | Prints only the character count, which can differ from the byte count in multi-byte  character sets (like Unicode). |
| -L or --max-line-length | Prints the length of the longest line in the file. |

## usage
`$ ls -1 ~/Documents | wc -l`  
25


## example
`$ wc filename.txt`  
10  50  350 filename.txt
