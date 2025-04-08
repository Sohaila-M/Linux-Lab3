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

4. Create a supplementary group called badgroup ![image](https://github.com/user-attachments/assets/140a77d3-b890-4cc3-b51c-1a08333b8c3a)
    

5. Add islam user to the pgroup group as a supplementary group ![image](https://github.com/user-attachments/assets/f4ef7770-16fa-4813-bb4b-a1009a73eace)

6. Modify the password of islam's account to password ![image](https://github.com/user-attachments/assets/256ee1d3-a038-4162-a4c6-0c95fc157474)

7. Modify islam's account so the password expires after 30 days ![image](https://github.com/user-attachments/assets/63f5cf9e-84b5-4991-9835-8f84022f0516)

8. Lock bad user account so he can't log in ![image](https://github.com/user-attachments/assets/0318fc01-dff2-4dbe-be0d-cc6129afe6db)

9. Delete bad user account ![image](https://github.com/user-attachments/assets/c1a5e42c-0498-45d6-b1ad-47e16877d90c)

10. Delete the supplementary group called badgroup   ![image](https://github.com/user-attachments/assets/0b842311-e63e-4dbf-ac16-3d6ab6a69c10)

11. Create a folder called myteam in your home directory and change its permissions to read only for the owner. ![image](https://github.com/user-attachments/assets/95fa8946-7f12-4727-9539-04d374a6a12d)

12. Log out and log in by another user ![image](https://github.com/user-attachments/assets/c2fdb03b-9370-43d1-8e2c-d95b227d0e43)

13. Try to access (by cd command) the folder (myteam) ![image](https://github.com/user-attachments/assets/e1aa058b-53d7-47d9-aa84-795735fe92fd)

14. Using the command Line
    • Change the permissions of oldpasswd file to give owner read and write permissions and for group write and execute and execute only for the others (using chmod in 2 different ways)
    ![image](https://github.com/user-attachments/assets/84f32073-b83e-41fa-9d09-74e3cec4ddec)

    • Change your default permissions to be as above. ![image](https://github.com/user-attachments/assets/a594fe40-152d-4042-a28c-a5c0af0792bd)

    • What is the maximum permission a file can have, by default when it is just created? And what is that for directory.
       Maximum (default) permission for file : 666
       Maximum (default) permission for directory : 777
    • Change your default permissions to be no permission to everyone then create a directory and a file to verify.
15. Starting from your home directory, find all files that were modified in the last two day. ![image](https://github.com/user-attachments/assets/3e7688b6-9810-474e-b079-cacbdbb83406)

16. Starting from /etc, find files owned by root user. ![image](https://github.com/user-attachments/assets/817ee949-ffd3-49b7-99c6-f55c87ef6f03)

17. Find all directories in your home directory. ![image](https://github.com/user-attachments/assets/8b2dc0e2-ac9c-4723-bf81-335bf7b895ac)

18. Write a command to search for all files on the system that, its name is ".profile". ![image](https://github.com/user-attachments/assets/4e9e2367-f224-4199-bf5f-aa5268e4ef8f)

19. Identify the file types of the following: /etc/passwd, /dev/pts/0, /etc, /dev/sda  ![image](https://github.com/user-attachments/assets/646c76d9-f451-49af-aee5-4597eeaf3505)

20. List the inode numbers of /, /etc, /etc/hosts.  ![image](https://github.com/user-attachments/assets/91861b23-4ea2-46e4-9902-96fe3d17938a)

21. Copy /etc/passwd to your home directory, use the commands diff and cmp, and Edit in the file you copied, and then use these commands again, and check the output.
    ![image](https://github.com/user-attachments/assets/4196ea42-b8c3-49a2-89f4-f324e14efbed)
    ![image](https://github.com/user-attachments/assets/d3a100ef-75e3-46dd-ae5c-714d4f0730e4)


22. Create a symbolic link of /etc/passwd in /boot.
    ![image](https://github.com/user-attachments/assets/09c8e639-8ab1-4d09-9031-4363ca4e73f2)
    ![image](https://github.com/user-attachments/assets/0df7602d-87b1-4d65-af66-4249f5eeb251)


23. Create a hard link of /etc/passwd in /boot. Could you? Why?
    ![image](https://github.com/user-attachments/assets/8fb7d60b-173e-433a-bbd7-0e8b22255b39)
    No, You can't because : /etc/passwd is in the root (/) filesystem and /boot is often mounted as a separate filesystem 

   Hard links cannot cross filesystem boundaries

   ![image](https://github.com/user-attachments/assets/7a38f67a-b49c-4478-a898-24928432eb6d)

