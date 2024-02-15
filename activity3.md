# Activity 3: Practical Exercises with Linux Commands

**Objective:** In this lab, you will practice using various Linux commands to perform common tasks such as navigating the file system, creating directories and files, manipulating files, and performing system operations.

**Prerequisites:**
- Basic understanding of the Linux command line interface.
- Access to a Linux environment, either through a virtual machine or a Linux-based operating system.

**Instructions:**

1. **Create a Snapshot of the VirtualBox Virtual Machine:**
   - Open VirtualBox and select the virtual machine you want to snapshot.
   - Go to the "Machine" menu and select "Take Snapshot".
   - Provide a name and description for the snapshot, then click "Take".

2. **Start the Virtual Machine and Log In:**
   - Start the virtual machine from the VirtualBox manager.
   - Once the virtual machine has booted up, log in using your username and password.

3. **Navigate to the Home Directory:**
   - Use the `cd` command to navigate to the home directory:
     ```
     cd ~
     ```

4. **Ensure You're in the Home Directory:**
   - Use the `pwd` command to confirm that you are in the home directory:
     ```
     pwd
     ```

5. **Create Directories:**
   - Create a directory named `dev` using the `mkdir` command:
     ```
     mkdir dev
     ```
   - Confirm that the `dev` directory is created by listing the contents of the current directory:
     ```
     ls
     ```

6. **Create Files in the `linux-exercises` Directory:**
   - Create two directories named `linux-exercises` and `fullstack-exercises`:
     ```
     mkdir linux-exercises fullstack-exercises
     ```
   - Confirm that the directories are created:
     ```
     ls
     ```
   - Navigate to the `linux-exercises` directory:
     ```
     cd linux-exercises
     ```
   - Create three files named `file.txt`, `file2.html`, and `file3` using the `touch` command:
     ```
     touch file.txt file2.html file3
     ```
   - Confirm that the files are created:
     ```
     ls
     ```

7. **Clear the Terminal:**
   - Use the `clear` command to clear the terminal screen:
     ```
     clear
     ```

8. **Add Text to Files:**
   - Use the `echo` command to add dummy text to `file.txt`, `file2.html`, and `file3`:
     ```
     echo "This is file.txt" > file.txt
     echo "This is file2.html" > file2.html
     echo "This is file3" > file3
     ```

9. **Read the Contents of Files:**
   - Use the `cat` command to read the contents of `file.txt`, `file2.html`, and `file3`:
     ```
     cat file.txt
     cat file2.html
     cat file3
     ```

10. **Creating and Deleting Directories:**
    - To create a directory, use the `mkdir` command followed by the directory name.
    - To delete a directory, use the `rmdir` command followed by the directory name.
      ```
      mkdir test
      rmdir test
      ```

11. **Copying and Moving Files:**
    - To copy files, use the `cp` command followed by the source file and destination directory.
    - To move files, use the `mv` command followed by the source file and destination directory.
      ```
      cp file1.txt destination_directory
      mv file2.txt new_location
      ```

12. **Using `whoami`, `history`, and `man` Commands:**
    - Use the `whoami` command to display the current user.
    - Use the `history` command to display a list of recently executed commands.
    - Use the `man` command followed by the name of a command to display its manual page.
      ```
      man whoami
      man history
      man ls
      ```

13. **Updating and Upgrading with `sudo`:**
    - Use `sudo apt update` to update the package lists for upgrades.
    - Use `sudo apt upgrade` to install available upgrades.
      ```
      sudo apt update
      sudo apt upgrade
      ```

14. **Installing a Simple Binary with `sudo`:**
    - Use `sudo apt install package_name` to install a binary package.
      ```
      sudo apt install wget
      ```
    - Use `sudo apt install package_name` to install a binary package.
      ```
      sudo apt install tree
      ```
      

15. **Changing Password:**
    - Use the `passwd` command to change your password.
      ```
      passwd
      ```

**Conclusion:**
Congratulations! You have completed a series of practical exercises using various Linux commands. Practice these commands regularly to become more proficient in using the Linux command line interface.

