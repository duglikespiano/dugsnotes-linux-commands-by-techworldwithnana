# diff

The diff command in Linux is a powerful command-line utility used to compare two files or directories line by line and output the differences. It highlights what changes (additions, deletions, or modifications) are needed to make the first file identical to the second.

## options
| Option |	Description	|
| --------- | --------- |
| -u | Output in unified format, which is a compact, single-section view using + (addition) and - (deletion) signs to indicate changes. This is the most common format for creating patches. |
| -r | Recursively compare files and subdirectories when comparing two directories. |
| -q | Report only if files differ without showing the actual content differences (brief mode). |
| -i | Ignore changes in case (uppercase vs. lowercase) when comparing text. |
| -w | Ignore all whitespace (spaces and tabs) within lines for comparison. |
| -y | Display differences in a side-by-side two-column format. |

## usage
`diff [options] file1 file2`  
