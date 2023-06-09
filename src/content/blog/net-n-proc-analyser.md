---
author: Samael
pubDatetime: 2023-05-03T15:57:52.737Z
title: Host Based Network and Process Analyser
postSlug: net-n-proc-analyser
featured: false
ogImage: https://user-images.githubusercontent.com/53733092/215771435-25408246-2309-4f8b-a781-1f3d93bdf0ec.png
tags:
  - Hardware-Projects
description: Smooth Client and Server Communication guide for optimal data transfer
---

[Get the experience on the **Instagram**](https://www.instagram.com/reel/CrtaradIham/?igshid=YmMyMTA2M2Y=)

# 🌟 The Ultimate Guide to Smooth Communication Between Client and Server 🌐

In today's interconnected world, effective communication between clients and servers is essential for seamless data exchange and system operations. Whether you're a network administrator or a technology enthusiast, understanding the methodology and tools for establishing a robust client-server connection can greatly enhance your digital experience. 🚀

## 📚 The Methodology of the Project

To ensure successful communication between clients and servers, we have devised a two-stage approach:

### A. Communication of Client and Server over the Same Network

In this stage, we focus on establishing a connection between the client and server within a local area network (LAN). We create virtual machines using tools like QEMU VirtManager to simulate client and server environments. These virtual machines have their own dedicated resources such as storage, RAM, and CPU, allowing us to run multiple instances on a single workstation. We recommend using lightweight and efficient operating systems like Parrot OS and Elementary OS for this purpose.

```py
import socket

# Create a socket object
server_socket = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

# Define the server address and port
server_address = ('localhost', 1234)

# Bind the socket to the server address
server_socket.bind(server_address)

# Listen for incoming connections
server_socket.listen(1)

# Accept a client connection
client_socket, client_address = server_socket.accept()

# Receive data from the client
data = client_socket.recv(1024)

# Process the received data
# ...

# Send a response back to the client
response = "Hello, client!"
client_socket.send(response.encode())

# Close the client socket
client_socket.close()

# Close the server socket
server_socket.close()

```

```py

import socket

# Create a socket object
client_socket = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

# Define the server address and port
server_address = ('localhost', 1234)

# Connect to the server
client_socket.connect(server_address)

# Send data to the server
data = "Hello, server!"
client_socket.send(data.encode())

# Receive a response from the server
response = client_socket.recv(1024)

# Process the received response
# ...

# Close the client socket
client_socket.close()

```



### B. Analyzing Outputs and Providing Actionable Insights

Once the client-server communication is established, we analyze the data exchanged between them to gain valuable insights. The received data is stored in .xyz format and then converted into a more readable .csv format using a Python script. The .csv files contain information about the system, processes, and network connections.

## 🖥️ Setting Up the Virtual Machines

To create the virtual machines, follow these steps:

1. Install the preferred Linux distribution on each virtual machine using an .iso image file.
2. After installation, remove the .iso file and reboot the virtual machine.
3. Update the operating system by running the command `sudo apt update && sudo apt upgrade`.
4. Install the necessary packages such as `net-tools` for network configuration, `python3` for running the project, and `pip` for installing required Python files.

## ⚙️ Running the Client-Server Connection

To establish the client-server connection, execute the following commands:

- **Server:** `python3 server.py <ip.addrs.SERVER> <port number>`
  Example: `python3 server.py 192.168.122.222 5421`

- **Client:** `python3 client.py <ip.addrs.SERVER> <port number>`
  Example: `python3 client.py 192.168.122.222 5421`

These commands initiate the connection between the server and client. The server listens for incoming data, while the client transfers system information, process details, and network information. The data transferred is displayed on the server's console, providing insights into the communication sequence.

## 📊 Analyzing the Received Data

To analyze the received data, execute the command:

`python3 analyser.py`

This command converts the created .xyz files into .csv format, which can be easily viewed and analyzed. The .csv files open in applications like Excel, with each element separated by commas. The Sysinfo.csv file provides information about the system's architecture, kernel module, operating system, RAM, and storage. The Procinfo.csv file contains process IDs, process names, statuses, and start times. The Netinfo.csv file includes process IDs, network statuses, local and remote IP addresses, and ports.

```py

# Import necessary libraries

# Function to search query by process ID
def search_by_process_id(process_id):
    # Read Procinfo.csv file
    # Search for process_id in the file
    # Print the entire row of matching process_id

# Function to search query by local IP
def search_by_local_ip(local_ip):
    # Read Netinfo.csv file
    # Search for local_ip in the file
    # Print the entire row of matching local_ip

# Function to search query by process name
def search_by_process_name(process_name):
    # Read Procinfo.csv file
    # Search for process_name in the file
    # Print the entire row of matching process_name

# Function to search query by network status
def search_by_network_status(network_status):
    # Read Netinfo.csv file
    # Search for network_status in the file
    # Print the entire row of matching network_status

# Main function
def main():
    # Display options for user to choose from
    # Read user's choice
    
    # Based on user's choice, perform corresponding search
    if user_choice == '1':
        # Ask for process ID from user
        # Call search_by_process_id function with process ID
    elif user_choice == '2':
        # Ask for local IP from user
        # Call search_by_local_ip function with local IP
    elif user_choice == '3':
        # Ask for process name from user
        # Call search_by_process_name function with process name
    elif user_choice == '4':
        # Ask for network status from user
        # Call search_by_network_status function with network status
    else:
        # Invalid choice, display error message

# Call the main function to start the analysis
main()

```


## 📈 The Final Analysis and Actionable Insights

To perform the final analysis, run the Python script:

`python3 FinalAction.py`

This script presents the user with four options:

1. **Search by Process ID:** Retrieve information based on process ID.
2. **Search by Local IP:** Retrieve information based on local IP address.
3. **Search by Process Name:** Retrieve information based on process name.
4. **Search by Network Status:** Retrieve information based on network status.

Based on the

 chosen option, the script provides actionable insights and recommendations. It assists in troubleshooting issues, identifying resource-intensive processes, and monitoring network connections.

## 🔒 Ensuring Security and Future Enhancements

As technology evolves, so do security requirements. It is crucial to stay updated with the latest security practices and protocols. Consider the following enhancements for a more secure and efficient client-server communication:

- Implement Transport Layer Security (TLS) for encrypted data transfer.
- Utilize secure authentication methods such as API keys or OAuth for client-server authentication.
- Regularly update and patch operating systems and software to address security vulnerabilities.

## 🚀 Conclusion

Smooth communication between clients and servers is the backbone of efficient data transfer and system operations. By following this guide, you'll be equipped with the knowledge and tools to establish a strong client-server connection within a local area network. Analyzing the exchanged data and deriving actionable insights will further empower you in managing and optimizing your network.

So, gear up and embark on your journey to seamless client-server communication. Explore the endless possibilities and unlock the true potential of your network! 🌐✨









