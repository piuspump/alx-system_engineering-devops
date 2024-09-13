# 0x002 Shell, I/O Redirections and Filters

### Learning Materials

- [I/O Redirection](http://linuxcommand.org/lc3_lts0070.php) on LinuxCommand.Org.
- [Special Characters](http://mywiki.wooledge.org/BashGuide/SpecialCharacters) on BashGuide.

### Exercises

1. **Print Hello, World**: Write a script that outputs `Hello, World` with a new line to the terminal.
2. **Confused Smiley**: Create a script to display the confused smiley `"(Ôo)'`.
3. **Display File**: Develop a script that shows the contents of the `/etc/passwd` file.
4. **Display Two Files**: Write a script to display the contents of both `/etc/passwd` and `/etc/hosts`.
5. **Show Last Lines**: A script to print the last 10 lines of `/etc/passwd`.
6. **First 10 Lines**: Create a script that shows the first 10 lines of `/etc/passwd`.
7. **Third Line Display**: Write a script that prints the third line of the file `iacta`. No `sed` allowed.
8. **Create Special File**: Create a file named `\*\\'"Holberton School"\'\\*$\?\*\*\*\*\*:)` containing `Holberton School` followed by a newline.
9. **Save Directory State**: Write a script that saves the output of `ls -la` into `ls_cwd_content`. Overwrite if it exists.
10. **Duplicate Last Line**: Create a script that duplicates the last line of `iacta`.
11. **Remove `.js` Files**: Write a script that deletes all `.js` files (not directories) in the current and all subdirectories.
12. **Count Directories**: A script to count directories and subdirectories, excluding the current and parent directories.
13. **List New Files**: Display the 10 newest files in the current directory, one per line, sorted by creation date.
14. **Unique Words**: A script that reads words from input and outputs words that appear exactly once, sorted alphabetically.
15. **Find Word**: Create a script to display lines containing the word `"root"` from `/etc/passwd`.
16. **Count Word**: Write a script that counts how many lines contain `"bin"` in `/etc/passwd`.
17. **Show Context**: A script that displays lines containing `"root"` and the next 3 lines in `/etc/passwd`.
18. **Exclude Pattern**: Display all lines in `/etc/passwd` that do not contain `"bin"`.
19. **Lines Starting with Letters**: Show lines from `/etc/ssh/sshd_config` that start with a letter.
20. **Replace Characters**: A script that replaces `A` and `C` in input with `Z` and `E`.
21. **Remove Letters**: Write a script to delete all occurrences of `c` and `C` from input.
22. **Reverse Input**: A script to reverse the input text.
23. **List Users and Homes**: Display all users and their home directories, sorted, from `/etc/passwd`.
24. **Find Empty Files**: Write a script that finds all empty files and directories, including hidden ones, in the current directory and subdirectories.
25. **List GIFs**: Create a script that lists all `.gif` files in the current and subdirectories, sorted by byte values, ignoring case.
26. **Decode Acrostic**: A script that decodes acrostics by reading the first letter of each line and outputs the hidden message.
27. **Most Active Hosts**: Write a script that processes web server logs in TSV format and displays the top 11 hosts or IPs making the most requests.