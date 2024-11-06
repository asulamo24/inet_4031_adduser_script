# INET4031 Add Users Script

## Program Description
This script automates the process of adding multiple users to a Linux system. It reads from an input file that lists users and their details and creates accounts, sets passwords, and assigns groups accordingly.

## Program Operation
1. Prepare an input file with user details, formatted as `username:password:last name:first name:group1,group2`.
2. Run the script using the following command:
   ```bash
   sudo python3 create-users.py < create-users.input

