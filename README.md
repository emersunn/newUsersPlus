# multiUsersMac

This script creates local user accounts on a macOS system, prompts the user to input each username one at a time, generates a random password for each user, makes them an admin, sets a random profile picture, and logs successful user creations and any errors encountered.

## Usage

1. Clone the repository: git clone https://github.com/emersunn/create-macos-users.git
cd create-macos-users

2. Make the script executable:
chmod +x create_users.sh

3. Run the script with sudo privileges:
sudo ./create_users.sh

The script will prompt you to input each username one at a time. When you are done, enter "done" to finish.

4. View the log file:
cat /var/log/create_users.log

The log file will contain information about successful user creations and any errors encountered.

## Configuration

The script does not currently support any configuration options. If you need to customize the script, you can modify the code directly.

## License

This script is released under the 





