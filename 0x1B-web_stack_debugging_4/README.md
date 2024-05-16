epository Name: alx-system_engineering-devops

Directory: 0x1B-web_stack_debugging_4

Project Description:
This repository contains solutions for the "0x1B. Web stack debugging #4" project, focusing on web stack debugging, DevOps, SysAdmin, Scripting, and Debugging tasks. The project commenced on May 13, 2024, at 6:00 AM, and is scheduled to conclude by May 17, 2024, at 6:00 AM. The checker for the project was released on May 16, 2024, at 6:00 AM, and an auto review will be launched at the deadline.

Requirements:

General:

All files are interpreted on Ubuntu 14.04 LTS.
All files should end with a new line.
A README.md file at the root of the folder of the project is mandatory.
Puppet manifests must pass puppet-lint version 2.1.1 without any errors.
Puppet manifests must run without error.
Puppet manifests' first line must be a comment explaining what the Puppet manifest is about.
Puppet manifests files must end with the extension .pp.
Files will be checked with Puppet v3.4.
Install puppet-lint:
ruby
Copy code
$ apt-get install -y ruby
$ gem install puppet-lint -v 2.1.1
Tasks:

0. Sky is the limit, let's bring that limit higher (mandatory):
In this web stack debugging task, we are testing the performance of our web server setup featuring Nginx under pressure. After benchmarking using ApacheBench, we observed a significant number of failed requests. The task is to fix our stack to ensure that the failed requests are reduced to 0. The Puppet manifest file "0-the_sky_is_the_limit_not.pp" contains the solution.

1. User limit (advanced):
The task involves changing the OS configuration to allow logging in with the "holberton" user and opening a file without encountering any error messages. The Puppet manifest file "1-user_limit.pp" provides the solution.

Files:

0-the_sky_is_the_limit_not.pp
1-user_limit.ppi
