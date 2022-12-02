# Folder Syncronization

This Python script synchronizes two folders: source and replica. The program maintains a full, identical copy of source folder at replica folder. File creation/copying/removal operations are logged to 'log.txt'.

<!-- USAGE EXAMPLES -->
## Usage

The script takes command line arguments <source_path>, <replica_path>, <log_file_path>, and <sync_interval>. Syncing interval should be provided in minutes.

Usage: python sync_folders.py <source_path> <replica_path> <log_file_path> <sync_interval>

Example: python sync_folders.py /source_folder /replica_folder /log_folder 1
