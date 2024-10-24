# Linux-advanced-for-Devops
This is repository is for understanding advanced Linux commands and concept.
# Advanced Linux Commands
## File and Directory Management
- `find /path/to/search -name "*.txt"`: Search for files with a specific name pattern.
- `tar -czvf archive.tar.gz /path/to/directory`: Create a compressed archive of a directory.
- `rsync -avz source/ destination/`: Synchronize files between directories or systems.

## Text Processing
- `grep -r "search_term" /path/to/directory`: Recursively search for a string in files.
- `awk '{print $1, $3}' file.txt`: Print specific columns from a text file.
- `sed 's/old/new/g' file.txt`: Replace occurrences of "old" with "new" in a file.

## System Monitoring
- `htop`: Interactive process viewer and system monitor.
- `iotop`: Monitor disk I/O usage by processes.
- `vmstat 5`: Report on virtual memory, processes, and CPU every 5 seconds.

## Networking
- `netstat -tuln`: Show listening ports and their associated processes.
- `curl -I http://example.com`: Fetch HTTP headers from a URL.
- `traceroute example.com`: Display the route packets take to reach a network host.


