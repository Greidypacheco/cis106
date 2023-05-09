---
name: Greidy Pacheco
course: CIS 106
Semester: Spring 2023
Instructor: R. Alberto
---

# Question 1

  
## awk
* Description:
    * It is a scripting language to execute and displaying text by performing the operation line by line.  
* Formula: 
    * `awk + option + {awk command} + file` 

* Examples:
    * `awk -F " " '{print $1}' dracula.txt`
    * `awk -F: '{print NR, $2, $10}' 78food.txt`
    * `awk -F: '{print toupper ($1)}' 78food.txt` 

 ## cat

* Description:
    * This is used to display the content of a file.

* Formula:
    * `cat + option + file`

* Examples:
   * `cat -n great-expectastions.txt`
   * `cat -b great-expectastions.txt`
   * `cat ~/Documents/Books/great-expectastions.txt`
  
## cp
* Description:
  * It is used to execute task as copying or changing the name of a file.

* Formula:
  * `cp + file + destination`
  
* Examples:
    * `cp -r Documents/Books/ ~/`
    * `cp ~/Documents/Csv/cars.csv ~/Desktop/`
    * `cp ~/Documents/Csv/cars.csv ~/Desktop/`

## cut
* Description:
    * It support to extract a specific section of each line from a file. 

* Formula:
  * `cut + option + file(s)`
 
* Examples:
  *  `cut -d '.' -f1 pride-and-prejudice.txt`
  *  `cut -b 1-10 dracula.txt`
  *  `cut -d " " -f1,6 --output-delimiter "=" dracula.tx`
  
## Grep

* Description:
  * It help to search text in a given file. It works lien by line. 

* Formula:
   * `grep + option + search criteria + file (s)`

* Examples:
    * `grep "blood" dracula.txt `
    * `grep -i "god" dracula.txt `
    * `grep -v "dracula" dracula.txt`


## head

* Description:
   * It display the top number of lines of a given file. The default line is 10. 

* Formula:
   * `head + option + file `

* Examples:
   * `head dracula.txt`
   * `head -20 dracula.txt `
   * `head -50 dracula.txt`
  
## ls

* Description:
  * It list the files and directories inside of a given directory. 
  
* Formula:
   * ` ls + option + directory to list`

* Examples:
  * `ls -a ~/Documents`
  * ` ls -1t ~/Downloads`
  * ` ls -x ~/Books`
  
## man

* Description:
  * It is use to see option and instructions of others commands. 

* Formula:
   * `man + option + command`

* Examples:
   * `man -k file`
   * `man ls `
   * `man pwd `
  
## mkdir

* Description:
   * It is used to create one or multiples directories. 

* Formula:
   * ` mkdir + new directory name or path + new directory name`

* Examples:
  * `mkdir Photos /Backgrounds`
  * `mkdir Photos/ Background1 Photos/ Background2 Photos/Background 3`
  * `mkdir -p movies / series `
  
## mv

* Description:
   * It is used to remove or rename files and directory.

* Formula:
   * `mv + source + destination`
   * `mv + files or directory + new name`

* Examples:
  * `mv Books/ dracula.txt/ Downloads`
  * `sudo mv ~/Downloads/sample2.pdf /usr/share/`
  * `mv great-expectastions.txt great-expectastions2.txt` 
  
## tac

* Description:
   * It support to display the content of a file in reverse order. 

* Formula:
  * `tac + option + file to display`
* Examples:
  * `tac ~/Books/ great-expectation2.txt`
  * `tac ~/Downloads/sample2.doc`
  * `tac ~/Downloads/sample2.xls`
    
## tail

* Description:
 * It display the last number of lines of a given file. By default is print the last 10 lines.
* Formula:
  * `tail + option + file `

* Examples:
  `tail ~/Downloads /sample2.doc`
  `tac ~/Books/ great-expectation2.txt`
  `tac -60 ~/Books/ great-expectation2.txt`

## touch

* Description:
  * It is used for creating files.
  
* Formula:
    * ` touch + file name`

* Examples:
    * `touch movie list`
    * `touch list_movie.doc list_series.doc`
    * `touch "List of Employees.txt"`
  
    
## tr
* Description:
    * It is used to delete or change characters for a specific request.

* Formula:
   * standard output | tr + option + set + set

* Examples:
   * `cat sample2.doc | tr "?" "!"
   * `cat sample2.xls | tr ":" ","`
   * `cat movies` | tr "." "!"
    
## tree

* Description:
   * It list all the directories with all their content including other directories and files.

* Formula:
   * `tree + option + directory`

* Examples:
   * `tree -d ~/Documents`
   * `tree -a ~/Books`
   * `tree -X ~/Downloads`

# Question 2

## How to work with multiple terminals open?
 In the terminal window in the left corner , there is an option to open a second terminal.
   
## How to work with manual pages?
 Manual page can be work by using the formula ` man + option + command to be search`. By executing this formula in the terminal it will display the instruction of how to work an specific command. 

## How to parse (search) for specific words in the manual page
 The way that we find a specific word is using the -k option with the man command. For example, ` man -k ls `.

## How to redirect output (> and |)

To redirect outputs from the terminal it is used `>` and by using `>> ` it will work the same way but keeping the old data in the file. The `|` command will format the output with options to have a better look of the output. 

## How to append the output of a command to a file

To append or add more content to a file it is use `>>` after the command that we want to execute. For example, `ls -a >> files.txt`.

## How to use wildcards

Wildcards are three signs: 
`*`  It is used to substitute characters for a file name or extension to match anything after the wildcard.

`?` It substitutes specific amount of characters. 

`[]` It matches a single character in the range.

## For copying and moving multiple files at the same time

Copying  multiples files at once can be done with formula `cp +  option + files`. For example, `cp python.txt training.txt ~/Downloads`.

Moving multiple files at once can be done with formula ` mv + option + file/directory`.


## How to use brace expansion

The brace expansion is use to create files and directories as well as removing the same at one time. For example, ` touch website{1..10}.html`

## For creating entire directory structures in a single command
 It can be perform by using formula `mkdir + -p + main-directory/{directory1,directory2}/{subdirectory1,subdirectory2}`.