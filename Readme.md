# Shell Scripts to make your life a little bit easier

This repository contains all my custom shell scripts, including:

- **SSH Quick Connect Script:** Allows quick access to saved SSH connections.
- **PHP Switcher:** Quickly switches between two specified PHP versions.

## How to Add a Script Folder to PATH

Adding a script folder to your system's `PATH` variable allows you to run the scripts in that folder from anywhere in your system.

1. Create a folder for your scripts, if you haven't already.
2. Open your terminal and run the following commands: ``echo 'export PATH="/path/to/your/scripts/folder:$PATH"' >> ~/.bashrc``


Make sure to replace `/path/to/your/scripts/folder` with the actual path to your scripts folder.

3. Once you've added this line to your `.bashrc` file, reload it by running: ``source ~/.bashrc``


4. Your scripts folder is now added to your system's `PATH` variable. You can now run your scripts from anywhere in your system by simply typing their name in the terminal.

## How to Make Scripts Executable

Before you can run a script, you need to make sure it is executable.

1. Open your terminal and navigate to the directory where your script is saved.

2. Run the following command to make the script executable: ``sudo chmod +x scriptname`` 


Make sure to replace `scriptname` with the actual name of your script
