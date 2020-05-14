# Project

SFTP Download Tool V1.0
Developed by Kaveh Majidi @ ALE

Python tool to download a directory from a remote server to a local machine using SFTP.

# Version

1.0

# Requirements

Python > 3.2

# Dependencies

Paramiko external library needs to be installed

# Installation

Download or clone from https://github.com/kaveh-ale/sftpdt.git

#  How to use?

Example : python3 sftpdt.py --ip=10.10.10.10 --username="admin" --password="serverpass" --remote_dir="backups" --local_path="/home/user/backup" -v

After execution, a log file is created in the execution path called sftpdt.log.

# Arguments

  -h, --help           
  show help message and exit

  --ip IP ADDRESS      
  IP address of the remote server

  --username USERNAME  
  username to login to remote server

  --password PASSWORD  
  password to login to remote server

  --remote_dir DIR     
  directory on the remote server to be downloaded, Ex."backups"

  --local_path PATH    
  local path as the destination for download, Ex."/home/user/backup"

  --port PORT          
  SFTP port number, default is 22

  -nolog               
  disables logging , by default logging is enabled

  -v                   
  enables verbose mode

  --version            
  show program's version number and exit


# License

This project is licensed under the MIT License

Copyright (c) [2020] [Kaveh Majidi]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
