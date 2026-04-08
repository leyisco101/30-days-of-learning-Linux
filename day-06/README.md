# Day 06 - [Contuniation of Manipulate Files and Directory and File Content Search and Text Processing
]

## Objective

What was the goal for today?

The goal for today was to continue learning how to manipulate files and directores in Linux and to understand how to search and filter text , which are essential for handling logs and datasets



## What I Learned

How to remove directories and their contents using rm -r.
How to delete files safely using rm -i, which asks for confirmation before deletion.
How to search for text inside files using the greg command.
How to perform case-insensitive searches using grep -i.
How to search through directories recursively using grep -r.
How to locate files and directories using find command.


## What I Built / Practiced

Practiced deleting files and directories:
   rm -r file3.txt
   rm -i file2.txt
 
Practiced deleting files and directories:

  grep "are" hello2.txt
  ls | grep "are" hello2.txt
  grep -i "good" hello2.txt
  grep -i "good" hello2.txt
  grep -i "Linus" note.txt
  grep "good" hello2.txt

  Practiced searching text in files:
  find /home -name "*.txt"
 

## Challenges Faced

Understanding when to use rm -r when deleting directories.
Learning the difference between grep, grep -i, and grep -r, It took me some time to actually figured out the differences between them through research.


## Key Takeaways

rm -r removes directories and everything inside them.
rm -i helps prevent accidental file deletion.
grep is a powerful tool for searching text within files.
find helps locate files and directories quickly in Linux systems.


## Resources
https://github.com/Najeeb-Sulaiman/linux-and-bash-scripting-guide/blob/main/02-linux-commands/04-search-and-text-processing.md



## Output

rm -r file3.txt
rm -i file2.txt
grep "are" hello2.txt
ls | grep "are" hello2.txt
grep -i "good" hello2.txt
grep -i "good" hello2.txt
grep -i "Linus" note.txt
grep "good" hello2.txt
find /home -name "*.txt"
 

