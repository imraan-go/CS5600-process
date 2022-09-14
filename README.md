# CS5600-process

## Question 1

The CPU utilization is 100%. Because we have commanded the program to run two processes with 100% cpu instruction set. Therefore, the CPU kept running intstruction and didn't have to wait for any I/O.

## Question 2

It took 10 total time to complete.


## Question 3

It now took 6 CPU time. The switching order matter. Because when the CPU is waiting for I/O to finish, it can run other process instruction. That is why it took less time than the question 2.

## Question 4

It took 9 total time to complete. With the SWITCH_ON_END flag, CPU waited for I/O to complete instead of running other instruciton in the meantime. Thereforce, it took more time than question 3.


## Question 5



This took 6 CPU time just like question 3. SWITCH_ON_IO is the default behaviour.


## Question 6

It took 27 CPU time to complete. System resources are not being utilized effectively.


## Question 7

With this IO_RUN_IMMEDIATE flag, it takes significantly less time to comlete all process. It is good idea to run I/O process immediately so that the CPU can do other work while it waits for the I/O to finish.


## Question 8

* -s1-l3:50,3:50 takes 12 CPU time.

* -s 2 -l3:50,3:50 -c -p takes 13 CPU time.

* -s 3 -l3:50,3:50 -c -p takes 13 CPU time as well.

IO_RUN_* does not have any effect on the outcome.

SWTICH_ON_END increases execution time significantly for all of the runs.