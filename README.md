🐧 Linux Process Management Experiment

This project demonstrates core concepts of Linux process management through Python scripts using the os module.

📌 Project Overview

The experiment covers:

👶 Creating and managing child processes

🧠 Executing commands using exec() system calls

🧟 Simulating zombie and orphan processes

🔍 Inspecting process details via the /proc filesystem

⚙️ Demonstrating process prioritization with nice()

Each concept is implemented in a separate script for clarity and modular learning.

| File                        | Description                                               |
| --------------------------- | --------------------------------------------------------- |
| `task1_process_creation.py` | Demonstrates creating and managing child processes        |
| `task2_exec_command.py`     | Executes Linux commands in child processes using `exec()` |
| `task3_zombie_orphan.py`    | Simulates zombie and orphan process behavior              |
| `task4_inspect_proc.py`     | Reads and displays process info from `/proc`              |
| `task5_priority.py`         | Shows process priority manipulation using `nice()`        |

✅ Requirements

Python 3.x

Linux environment (Ubuntu, WSL, or any POSIX-compliant OS)

Terminal access

⚠️ These scripts are Linux-specific and will not run correctly on native Windows environments (Command Prompt or PowerShell).

🚀 How to Run

Open a terminal and run each script individually. Example:

python3 task1_process_creation.py


Follow the prompts in the terminal for each task.

📝 Notes

Task 3 (Zombie/Orphan Processes):
Open another terminal and run the following to monitor zombie processes:

ps -el | grep defunct

Use Ctrl + C to stop any long-running or hanging scripts.

For educational purposes only. Running these scripts will affect system processes momentarily — do not run on critical systems.
