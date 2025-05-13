# Linux-System-Resource-Monitor-Bash-Script-
# Project Description
This project is a Bash-based system monitoring tool designed for Linux systems, specifically built and tested on Kali Linux. The script continuously monitors CPU usage, memory usage, and disk space in real-time and alerts the user when any of these resources exceed a defined usage threshold (default is 80%).The script uses native Linux command-line utilities o extract system resource information and processes it using tools. It displays live system stats in the terminal and prints alert messages—with a timestamp and red color formatting—whenever a resource's usage becomes critically high.

# Key Features
-Real-time monitoring of CPU, RAM, and disk space
-Alert system with timestamps and color-coded warnings
-Customizable threshold settings
-Easy to run and modify
-Lightweight and doesn't rely on external packages

# How to use the scrpit 
To run this Linux system monitor, first ensure you're using a Linux-based OS such as Kali Linux or VS Code. Save the script to a file, such as monitor.sh, and make it executable using the chmod command. Once it's executable, you can run it directly in your terminal.After starting the script, it will display real-time information about CPU usage, memory usage, and disk space. The script continuously updates this data every two seconds and will display a red alert message if any usage exceeds the defined threshold (default is 80%). Th
