Step 1: Set the lab_file shell variable
First, set the lab_file variable to the path of the file editing_final_lab.txt:


lab_file="editing_final_lab.txt"
This assigns the file path to the lab_file variable.

Step 2: Edit the file using vim
Open the file in vim:

You can open the file stored in the lab_file variable using the following command:


vim "$lab_file"
This will open the editing_final_lab.txt file in vim.

Enter Visual Mode in Vim:

To enter visual mode in vim, press:


v
This starts the visual mode, where you can select text.

Move the cursor to the first column of the first line:

Navigate using the arrow keys or by typing 0 to move the cursor to the beginning of the line.

Remove the last seven characters from the first column on the first line:

To delete the last seven characters from the first column, you can use the following steps:

Move the cursor to the beginning of the first column if not already there.
Press 7 (this counts the next seven characters).
Press d to delete.
Alternatively, you can use the following vim command directly in normal mode to remove the last seven characters from the first column on the first line:


0d7l
This means:

0: Move to the start of the line.
d: Delete.
7l: Move seven characters to the right and delete them.
Preserve only the first four characters of the first column:

After deleting the last seven characters, you want to keep only the first four characters. If you want to delete everything after the first four characters, do the following:

Move the cursor to the fifth character.
Press d$ to delete everything to the end of the line from that point onward.
Save and quit the file:

To save the changes and exit vim, type:


:wq
Step 3: Edit the file using nano
Open the file in nano:

You can open the file in nano using the following command:


nano "$lab_file"
Navigate to the first column:

Use the arrow keys to move to the beginning of the first line.

Remove the last seven characters from the first column:

Use the arrow keys to move the cursor to the beginning of the line. Then, use Ctrl + K to cut the last seven characters.

Alternatively, you can use the arrow keys to highlight the last seven characters and press Ctrl + K to delete them.

Preserve only the first four characters:

Make sure only the first four characters are kept. If necessary, use the arrow keys to move the cursor and remove any additional characters.

Save and quit the file:

To save the file and exit nano, press Ctrl + X, then press Y to confirm saving, and then press Enter to confirm the file name.

Summary of Commands:
Set the lab_file variable:


lab_file="editing_final_lab.txt"
Open the file in vim:


vim "$lab_file"
Enter Visual Mode in Vim:

Press v.

Delete the last seven characters in vim:

Press 0d7l.

Keep only the first four characters:

Press d$ (or use the delete method).

Save and quit in vim:

Press :wq.

Open the file in nano:
nano "$lab_file"
Remove the last seven characters in nano:

Use Ctrl + K to cut the characters.

Save and quit in nano:

Press Ctrl + X, then Y, then Enter  

![image](https://github.com/user-attachments/assets/8c344c1d-c92b-409f-8339-ec69395a3c0f)
