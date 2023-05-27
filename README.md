# Saw_File_Mover

Client Version of Auto File Mover

This is a Python Script turned into a Windows Basic GUI executable(?)
It is designed to run continuously and every 0.5 minute it will:
    - Check the selected Source Folder for new files.
    - Sort new files into a new folder minus 3 characters.
        i.e. 12345ABC.file (& alike file names) into new folder named 12345
    - Once done, it will move new folder to selected Target Folder. 