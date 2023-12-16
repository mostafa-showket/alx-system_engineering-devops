# 0x02-shell_redirections:

0-hello_world: script that prints `"Hello, World"`

1-confused_smiley: script displays a confused smiley `"(Ôo)'`

2-hellofile: display the content of `/etc/passwd` file

3-twofiles: display the content of `/etc/passwd/` and `/etc/hosts`

4-lastlines: display the last 10 lines of `/etc/passwd`

5-firstlines: display the first 10 lines of `/etc/passwd/`

6-third_line: displays the third line of the file `iacta` in the working directory

7-file: script that creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School`

8-cwd_state: script that writes into the file `ls_cwd_content` the results of the command `ls -la`, if the file `ls_cwd_content` already exists it would be written, if it doesn't exist it would be created

9-duplicate_last_line: duplicates the last line of the file `iacta` in the working directory

10-no_more_js: deletes all regular files (not the directories) with `.js` extension that are present in the current directory and all its subfolders

11-directories:  counts the number of directories and sub0directories in the current directory
* the current and parent directories are not taken into account
* Hidden directories would be counted

12-newest_files: displays the 10 newest files in the current directory

13-unique: takes a list of words as input and prints only words that appear exactly once

14-findthatword: display lines containing the pattern `"root"` from the file `/etc/passwd`

15-countthatword: display the number of lines that contain the pattern `"bin"` in the file `/etc/passwd`

16-whatsnext: display lines containing the pattern `"root"` and 3 lines after the n in the file `/etc/passwd`

17-hidethiswrod: display all teh lines in the file `/etc/passwd` that do not contain the pattern `"bin"`

18-letteronly: display all lines of the file `/etc/ssh/sshd_config` starting with a letter

19-AZ: replace all character `A` and `c` from the input to `z` and `e` respecteively

20-hiago: script that removes all letters `c` and `C` from input

21-reverse: script that reverse its input

22-users_and_homes: displays all users and thir home directories, sorted by users
* based on the `/etc/passwd` file

100-empty_casks: finds all emptys files and directories in the current directory and all sub-directories
* only the shows the names of the files and directories
* hidden files is listed 

101-gifs: lists all files with `.gif` extension in the current directory and all its sub-directories

102-acrostic: decodes acrostics that use the first letter of each line

103-the_biggest_fan: script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.

# Usage

for example run 
`./0-hello-world`

> this project developed during the Alx school program
