# Linux-Lab3
1. Create a user account with the following attribute
   • username: “your first name”
   • Fullname/comment: “full name”
   • Password: islam
   ![image](https://github.com/user-attachments/assets/55ab5f71-ea15-4b8d-9ef7-069a018949e1)

2. Create a user account with the following attribute
   • Username: baduser
   • Full name/comment: Bad User
   • Password: baduser
   ![image](https://github.com/user-attachments/assets/6da2ca4c-73ad-4557-9beb-005710ba6e3a)

3. Create a supplementary (Secondary) group called pgroup with group ID of 30000
  ![image](https://github.com/user-attachments/assets/d9acb776-0f12-472b-bff4-86d939ae8182)

4. Create a supplementary group called badgroup
    ![image](https://github.com/user-attachments/assets/140a77d3-b890-4cc3-b51c-1a08333b8c3a)

5. Add islam user to the pgroup group as a supplementary group ![image](https://github.com/user-attachments/assets/f4ef7770-16fa-4813-bb4b-a1009a73eace)

9. Modify the password of islam's account to password
10. Modify islam's account so the password expires after 30 days
11. Lock bad user account so he can't log in
12. Delete bad user account
13. Delete the supplementary group called badgroup
14. Create a folder called myteam in your home directory and change its permissions to read only for the owner.
15. Log out and log in by another user
16. Try to access (by cd command) the folder (myteam)
17. Using the command Line
    • Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
    • Change your default permissions to be as above.
    • What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
    • Change your default permissions to be no permission to everyone then create a directory and a file to verify.
18. Starting from your home directory, find all files that were modified in the last two day.
19. Starting from /etc, find files owned by root user.
20. Find all directories in your home directory.
21. Write a command to search for all files on the system that, its name is ".profile".
22. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda
23. List the inode numbers of /, /etc, /etc/hosts.
24. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.
25. Create a symbolic link of /etc/passwd in /boot.
26. Create a hard link of /etc/passwd in /boot. Could you? Why?
