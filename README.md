# Technical-Task-Problem-1

Implement a program that will launch a specified process and periodically (with a provided time interval) collect the following data about it:
CPU usage (percent);
Memory consumption: Working Set and Private Bytes (for Windows systems) or Resident Set Size and Virtual Memory Size (for Linux systems);
Number of open handles (for Windows systems) or file descriptors (for Linux systems).
Data collection should be performed all the time the process is running. Path to the executable file for the process and time interval between data collection iterations should be provided by user. Collected data should be stored on the disk. Format of stored data should support automated parsing to potentially allow, for example, drawing of charts.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

My algorithm consists of a program and a checker that checks on the RAM and CPU usage and at the same time saves every print in a file named stats.txt. The checker report prints every second or so.
The flappy bird software was developed by TimoWilken and published under a free MIT licence.

To jump you simply have to press space, up arrow or just click.
