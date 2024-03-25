Web Stack Debugging #0

Overview
This project is part of a series aimed at training individuals in the art of debugging web stacks. The ability to debug a web stack is crucial for Full-Stack Software Engineers and requires practice to master. In this series, broken or bugged web stacks will be provided, and the goal is to fix them, ultimately creating a Bash script that, when executed, brings the web stack to a working state.

Task Description
In this particular task, you're required to ensure that Apache runs on a container and returns a page containing "Hello Holberton" when queried at the root.

Docker Setup
To solve this task, you'll be given a Docker container. If you prefer to install Docker locally, instructions are provided for various operating systems.

Task Execution
Start Docker container: docker run -p 8080:80 -d -it holbertonschool/265-0
Verify container status: docker ps
Issue curl command to check response: curl 0:8080
If the response is not as expected, debug and fix the issue within the container.
Document the commands used to fix the issue in your answer file.
Repository Information

GitHub repository: alx-system_engineering-devops
Directory: 0x0D-web_stack_debugging_0
File: 0-give_me_a_page
