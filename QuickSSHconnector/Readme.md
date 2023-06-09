# SSH Connection Manager

This is a simple shell script that allows you to manage and connect to various SSH connections.
It assumes that all your SSH connection are configured with ssh key authentication (if not, what are you doing?). However it might also work with password authentication, but I never tested that.

## Prerequisites

- `jq` JSON parser is required for this script to work. You can install it on Ubuntu-based systems using `apt`.
- To install `jq` on Ubuntu-based systems, run the following command: ``sudo apt install jq``

## Usage

1. Clone or download the repository to your local machine.
1. (Optional) add your script folder to PATH (see main Readme in this git)
1. Make the script executable with ``sudo chmod +x ./quickSSH``
2. Open a terminal and navigate to the directory where the script is saved. (if you didn't add the folder to you PATH)
3. Run the script using the following command: ``./quickSSH`` (if you added the folder to your PATH type ``quickSSH`` anywhere in your terminal)
4. Follow the on-screen instructions to manage and connect to SSH sessions.

