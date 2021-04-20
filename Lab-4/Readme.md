# Use ' gcc 4.24.c -pthread ' to compile the C file and similarly other C files. 
The compiled files are also provided.
<br><br>
# 4.24
Value of Pi is calculated using the monte carlo technique, which involves randomization. Threads are used for the implementation of algorithm.
<br><br>
<br><br>
# 4.27
Fibonacci sequence is generated in this task using threads. The user enters the number of Fibonacci numbers to be generated using the program, and the program will then generates the given number of Fibonacci numbers.
<br><br>
<br><br>
# 7.15
Fibonacci sequence is generated in this task using threads but in this case we eliminated the pthread_join function. the pthread_join function waits for the thread to terminate by suspending the calling thread which in this case is the main() function. So eliminating pthread_join allows parent thread to continue execution regardless of the child.
<br><br>
<br><br>
# 7.17
Value of Pi is calculated using the monte carlo technique, But in this case we created an array of thread for multi-threading and used mutex locks to avoid race condition.
<br><br>
<br><br>
