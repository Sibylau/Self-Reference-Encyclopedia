# Useful Linux Command
### Files opened by a process
`lsof [option][user name]`: list of open files. 
  - `lsof -u userid`: list all files opended by a user
  - `lsof -u ^userid`: list all files opened except a specific user
  - `lsof -c process_name`: list all files opened by a process
  - `lsof -p process_id`: list all files opened by a process
  - `lsof -p ^process_id`: list all files opened except a process
  - `lsof -D directory_path`: list all files opened by a directory
  - `lsof -i port_number`: list all files listening to a specific port
  - `lsof file_name`: list all processes using the file