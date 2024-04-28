# Multi-threading
# Methodology
This Python script demonstrates multi-threaded matrix multiplication using the multiprocessing module. The goal is to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using varying numbers of threads (1 to 8). The script measures the execution time and CPU usage for each configuration and generates visualizations to analyze the performance.

# How to Run the Code
To run the code, simply execute the multi_threaded_matrix_multiplication.py script in a Python environment with the required dependencies installed. You can adjust the parameters such as the number of matrices, matrix size, and number of threads in the script as needed.

   ``` python multithreading.py ```

# Result Table
The table below shows the actual and expected time taken for matrix multiplication with different numbers of threads:
# output:-
Number of CPU cores: 2
Execution time with 1 threads: 12.80 seconds
Average CPU Usage during execution with 1 threads: 91.00%
Memory usage during execution with 1 threads: 1629.17 MB
Execution time with 2 threads: 12.77 seconds
Average CPU Usage during execution with 2 threads: 9.00%
Memory usage during execution with 2 threads: 1699.73 MB
Execution time with 3 threads: 8.13 seconds
Average CPU Usage during execution with 3 threads: 9.00%
Memory usage during execution with 3 threads: 1701.84 MB
Execution time with 4 threads: 8.17 seconds
Average CPU Usage during execution with 4 threads: 9.50%
Memory usage during execution with 4 threads: 1711.45 MB
Execution time with 5 threads: 6.62 seconds
Average CPU Usage during execution with 5 threads: 8.50%
Memory usage during execution with 5 threads: 1759.20 MB
Execution time with 6 threads: 8.20 seconds
Average CPU Usage during execution with 6 threads: 8.50%
Memory usage during execution with 6 threads: 1761.14 MB
Execution time with 7 threads: 7.40 seconds
Average CPU Usage during execution with 7 threads: 60.60%
Memory usage during execution with 7 threads: 1747.83 MB
Execution time with 8 threads: 6.62 seconds
Average CPU Usage during execution with 8 threads: 9.00%
Memory usage during execution with 8 threads: 1795.55 MB

# Result Graphs
Execution Time vs. Number of Threads
This graph illustrates the actual execution time (solid line) compared to the expected execution time (dotted line) for different numbers of threads. As expected, the execution time decreases initially with the increase in the number of threads, but then increases again after reaching a certain point.

# CPU Usage 
This graph displays the CPU usage as a percentage for different numbers of threads used in matrix multiplication. The CPU usage increases with the number of threads, peaking at a certain point before potentially decreasing due to overhead and resource contention.

