# Split Markdown for Ulysses import

Split Markdown file into smaller sections based on h1 h2 headings.
Then drag folder structure to Ulysses III

**split\_md\_05.py**

2014-05-06 18:15

Python Script for Splitting Markdown files into smaller files and folders
based on header levels:

# Header 1 becomes numbered sub folders (groups)

## Header 2 becomes numbered markdown files (sheets)

Main folder can then be dragged into Ulysses archive, either "iCloud" or "On My Mac")

Handy when importing big projects from other Markdown sources.

Also generates combined .marked file to be opened in Marked 2.1

Modify these variables in the script to change the output:

```Python
num_files = True #Add numbers to filenames.
no_spaces = True #Remove spaces in filenames.
split_level = "###" #The heading level to stop splitting at. By default h3 - h6
```

_2014 (cl) RoyRogers56_