# Linux-Lab3
1. Create a user account with the following attribute
   • username: “your first name”
   • Fullname/comment: “full name”
   • Password: islam
   ![image](https://github.com/user-attachments/assets/55ab5f71-ea15-4b8d-9ef7-069a018949e1)

3. Create a user account with the following attribute
   • Username: baduser
   • Full name/comment: Bad User
   • Password: baduser
   ![image](https://github.com/user-attachments/assets/6da2ca4c-73ad-4557-9beb-005710ba6e3a)

5. Create a supplementary (Secondary) group called pgroup with group ID of 30000
6. Create a supplementary group called badgroup
7. Add islam user to the pgroup group as a supplementary group
8. Modify the password of islam's account to password
9. Modify islam's account so the password expires after 30 days
10. Lock bad user account so he can't log in
11. Delete bad user account
12. Delete the supplementary group called badgroup
13. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
14. Log out and log in by another user
15. Try to access (by cd command) the folder (myteam)
16. Using the command Line
    • Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
    • Change your default permissions to be as above.
    • What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
    • Change your default permissions to be no permission to everyone then create a directory and a file to verify.
17. Starting from your home directory, find all files that were modified in the last two day.
18. Starting from /etc, find files owned by root user.
19. Find all directories in your home directory.
20. Write a command to search for all files on the system that, its name is ".profile".
21. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
22. List the inode numbers of /, /etc, /etc/hosts.
23. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.
24. Create a symbolic link of /etc/passwd in /boot.
25. Create a hard link of /etc/passwd in /boot. Could you? Why?
