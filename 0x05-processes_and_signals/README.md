Processes and Signals

Overview
This repository contains solutions to various tasks related to processes and signals in the context of DevOps and shell scripting.

Files Structure
0-what-is-my-pid: Bash script to display its own PID.
1-list_your_processes: Bash script to display a list of currently running processes.
2-show_your_bash_pid: Bash script to display lines containing the word "bash" along with their PIDs.
3-show_your_bash_pid_made_easy: Bash script to display the PID and process name of processes containing the word "bash".
4-to_infinity_and_beyond: Bash script to display "To infinity and beyond" indefinitely with a sleep of 2 seconds between each iteration.
5-dont_stop_me_now: Bash script to stop the process started by 4-to_infinity_and_beyond.
6-stop_me_if_you_can: Bash script to stop the process started by 4-to_infinity_and_beyond without using kill or killall.
7-highlander: Bash script to display "To infinity and beyond" with intermittent messages and handle SIGTERM signal.
67-stop_me_if_you_can: Copy of 6-stop_me_if_you_can modified to kill the process started by 7-highlander.
8-beheaded_process: Bash script to kill the process started by 7-highlander.
100-process_and_pid_file: Bash script to create a PID file, display messages, and handle signals.
101-manage_my_process: Bash script to manage 100-process_and_pid_file with start, stop, and restart functionality.
manage_my_process: Bash script executed by 101-manage_my_process.
102-zombie.c: C program to create 5 zombie processes.
Instructions
To execute any of the scripts, navigate to the appropriate directory and run the script using ./script_name.

Author
Sylvain Kalache

License
This project is licensed under the MIT License - see the LICENSE file for details.
