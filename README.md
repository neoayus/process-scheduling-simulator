# Operating System Scheduling Simulator

## Project Description
This Java project simulates multiple CPU scheduling algorithms by generating a stream of random jobs and comparing the performance of six common scheduling methods. It aims to help users understand and visualize how different scheduling strategies operate in an OS environment.

## Features
- Generates customizable job streams with user-defined parameters such as:
  - Number of processes
  - Degree of multiprogramming
  - Number of CPU/IO bursts per process
  - CPU burst and IO burst ranges
  - Priority range
  - Arrival time range
  - Initial tau and alpha values for exponential averaging
  - Choice of Gaussian or Binomial random number generation
- Implements six scheduling algorithms:
  - First-Come, First-Served (FCFS)
  - Shortest-Job-First (SJF)
  - Shortest Remaining Time First (SRTF)
  - Priority Scheduling
  - Round Robin (RR)
  - Exponential Average SRTF
- Interactive visualization of:
  - Job queue, device queue, and ready queue
  - Time unit by time unit queue status and changes
  - CPU utilization, throughput, turnaround time, and waiting time
  - Individual job progress via progress bars and logs

## How to Compile and Run
1. Opent terminal in project root directory. 
2. Compile sources: ``` javac -d bin src/*.java ```
3. Run Main Class : ``` java -cp bin Main ```