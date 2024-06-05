# Network-Scanner

This is a Python-based network scanner that can:

1. Discover active devices on a network:** Perform ARP scanning to identify IP addresses and MAC addresses of devices.
2. Scan ports on target devices:**  Perform port scanning to find open ports and identify services running on them.
3. Attempt OS detection:** Use Nmap and p0f to try to identify the operating systems of target devices.
4. Visualize network topology:** Create a 2D graph representation of network connections.

## Installation

1. Install Python: Make sure you have Python installed on your system.
2. Install Required Libraries
        pip install -r requirements.txt

Usage

To run the network scanner, use the following command in your terminal:

python network_scanner.py <target> [-p <ports>] [--os] [--topology] [--protocol]

Contributing

Contributions are welcome! If you find a bug or have suggestions for improvements, please feel free to open an issue or submit a pull request.

    
