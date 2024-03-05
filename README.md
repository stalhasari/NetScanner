**Description:**

This Python program allows you to scan devices on your network. Using the Scapy library, ARP packets are sent and responses are received. This helps you discover active devices on your network.

**Usage:**

1. Run the program.
2. Enter the desired IP address.
3. The program sends ARP requests to scan devices on your network.
4. Displays the responses.

**Installation:**

1. Install Python on your computer.
2. Install the required libraries by typing `pip install scapy` into the terminal.
3. Run the program: `python netscanner.py -i <IP_ADDRESS>`

**Notes:**

- The program may require administrator (root) permissions to function properly.
- It may take some time to receive responses from devices, please be patient.
