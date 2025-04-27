# Port-Scanner-KALI

A simple Python script to scan open ports on multiple target IP addresses using socket connections. This script allows you to check which ports are open on the specified targets and is customizable to scan a range of ports.

Features:
- Scan multiple targets (IP addresses) simultaneously.

- Specify a custom number of ports to scan.

- Color-coded output using termcolor to highlight open ports.

- Works with both single and multiple target IP addresses.

Prerequisites:
- Make sure you have Python 3 installed on your system. You will also need the termcolor module for colorful output.
If you don't have termcolor installed, you can install it by running: "pip install termcolor" (same goes out for other packages and versions).

- If you're using Kali Linux or another system with an externally-managed environment, consider using a virtual environment.

How it Works:
- The script establishes a socket connection for each port on the target IP address.

- If the port is open, the script prints a message indicating the open port with color-coded output.

- If the port is closed or blocked, it is silently skipped.
