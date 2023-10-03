# Solutions for 0x02. Shell, I/O Redirections and filters

0. **0-hello_world**: Prints “Hello, World”, followed by a new line to the standard output.

1. **1-confused_smiley**: Displays a confused smiley `"(Ôo)'`.

2. **2-hellofile**: Displays the content of the `/etc/passwd` file.

3. **3-twofiles**: Displays the content of `/etc/passwd` and `/etc/hosts`.

4. **4-lastlines**: Displays the last 10 lines of `/etc/passwd`.

5. **5-firstlines**: Displays the first 10 lines of `/etc/passwd`.

6. **6-third_line**: Prints the third line of the file named `iacta`, located in the working directory, without utilizing the `sed` command.

7. **7-file**: Creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line.

8. **8-cwd_state**: Writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it.

9. **9-duplicate_last_line**: Replicates the last line of the `iacta` file located in the current working directory.

10. **10-no_more_js**: Deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders.

11. **11-directories**: Creates a script to tally the directories and subdirectories within the current directory, excluding the current and parent directories but including hidden ones.

12. **12-newest_files**: Creates a script that displays the 10 newest files in the current directory. Sorted and one line per file.

13. **13-unique**: Takes a list of words as input and prints only words that appear exactly once.

14. **14-findthatword**: Displays lines containing the pattern “root” from the file `/etc/passwd`.

15. **15-countthatword**: Displays the number of lines that contain the pattern “bin” in the file `/etc/passwd`.

16. **16-whatsnext**: Displays lines containing the pattern “root” and 3 lines after them in the file `/etc/passwd`.

17. **17-hidethisword**: Displays all the lines in the file `/etc/passwd` that do not contain the pattern “bin”.

18. **18-letteronly**: Displays, including capital letters, all lines of the file `/etc/ssh/sshd_config` starting with a letter.

19. **19-AZ**: Replaces all characters `A` and `c` from input to `Z` and `e` respectively.

20. **20-hiago**: Removes all letters `c` and `C` from input.

21. **21-reverse**: Reverse its input.

22. **22-users_and_homes**: Displays all users and their home directories, sorted by users following the `/etc/passwd` file.

23. **100-empty_casks**: Locates and lists empty files and directories in the current directory and its subdirectories, displaying only their names (including hidden ones), with each name on a separate line and ending with a newline character, all without using `basename`, `grep`, `egrep`, `fgrep`, or `rgrep`.

24. **101-gifs**: Lists sorted, case-insensitive, hidden `.gif` files' names (without extensions) in the current directory and its subdirectories, only including regular files, with each name on a separate line and ending with a newline character. It avoids using `basename`, `grep`, `egrep`, `fgrep`, or `rgrep`.

25. **102-acrostic**: Decodes acrostics that use the first letter of each line.

26. **103-the_biggest_fan**: Parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
