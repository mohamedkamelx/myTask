# Linux

## Linux Commands

| Command | Description |
|---------|-------------|
| pwd   | Shows the current directory |
| mkdir | Create a folder |
| vim or nano  | Open/edit a file |
| cat   | Display the contents of a file |
| cd    | Change directory |
| cd..   | go back |
| cd~   | go home |
| man   | Shows the manual of a certain command |
| ls   | Shows the current directory files |
| ls  l | Shows the current directory files and permissions|
| touch   | create new file |

## Permissions in Linux
Not every body in Linux can read, write or execute files.
- r = read permission
- w = write permission 
- x = execute permission

Permissions for:
- User (u)
- Group (g)
- Others (o)

Example:
- chmod o-x file.sh 
  - (o) others ,(-x) removes the permission for excuting the files .
 
Example:
- chmod g=r file.sh 
  - give a read permission for the group .

## Bash Scripts

The first line of a Bash script is the bash location (#!/bin/bash)

For example:
```bash
#!/bin/bash
mkdir folder1
ls
```
to run this file => ./hello.sh


## Linux Commands
| Command | Description |
|---------|-------------|
| top   | Shows running processes |
| htop  | Better interface |
| ps    | has more functionalities|




```ps
    ps faux | grep counter.py
    kill 5927
```
- this will search for running task with keyword counter.py

## Sudo apt

Package manager

## Secure Shell (SSH)

Communication protocol that allows you to connect to a remote machine.

SSH username@IPaddress -p Portnumber
