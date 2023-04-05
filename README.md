# Safe-File
This project involves creating a reference monitor using the security layer functionality in Repy V2 to implement a defensive security system. The reference monitor acts as an access control concept that mediates all access to objects by subjects, allowing, denying, or changing the behavior of any set of calls.

# Design Paradigms
The design paradigms used in this project are accuracy, efficiency, and security. The security layer should only stop certain actions from being blocked, use a minimum number of resources, and prevent attackers from circumventing the security layer.

# Defensive Security System
The defensive security system created in this project keeps a backup copy of a file in case it is written incorrectly. The system creates two copies of the same file, one is a valid backup to read from, and the other is written to. The system checks if the file contents start with 'S' and end with 'E', and only updates the original file with the new data if the new data is valid. The system should not produce any errors, and normal operations should not be blocked or produce any output.

# Test Applications
The project also involves writing test applications to ensure the reference monitor behaves properly in different cases and to test attacks against the monitor. The attacker's objective is to bypass the A/B restrictions or cause the security layer to act in a disallowed manner.

# Usage
To use this project, simply clone the repository to your local machine and use Repy V2 and Python to run the reference monitor. The program must produce no output when run normally and must be submitted as a repy file called reference_monitor_[netid].r2py in Gradescope.

# Contributing
If you wish to contribute to this project, please fork the repository and make your changes in a separate branch. Once you have made your changes, submit a pull request with a clear description of your changes and why they are necessary.

# Acknowledgments
This project was developed as part of a coursework for access control and reference monitors. We would like to acknowledge the instructor and teaching assistants for their guidance and support throughout the course.
