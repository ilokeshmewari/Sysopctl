#sysopctl v0.1.0 - System Operations Control
`sysopctl` is a custom Linux command-line utility that provides various system management functionalities. It offers a convenient way to get CPU and memory information, manage system services, list running processes, and check overall system health.

Features
1. CPU Information: Retrieve detailed information about the CPU.
2. Memory Information: Display memory usage statistics.
3. Service Management: Start and stop system services.
4. Process Management: List all running processes.
5. System Health Check: Get an overview of the system's health, including CPU, memory, disk usage, and system load.

#Installation
Download the sysopctl script.
- Make the script executable
   chmod +x sysopctl
- (Optional) Move it to a directory in your PATH, e.g., /usr/local/bin
  sudo mv sysopctl /usr/local/bin/

#Examples
- Get CPU information:
  sysopctl cpu getinfo
- Get memory information:
  sysopctl memory getinfo
- Start a service:
  sysopctl service start apache2
- Stop a service:
  sysopctl service stop apache2
- List running processes:
  sysopctl process list
- Get system health status:
  sysopctl system health

