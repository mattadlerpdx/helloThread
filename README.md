# helloThread

 * CS 532: helloT.c
 * print Hello World from a thread
 * and calculate the factorial of the input thread ID
 * demonstrates how to create a thread and join with it *
 
 
 /*
 * Assignment:
 * 1. read the code and understand it. use "man pthread" to get a listing
 *    of supported pthread functionality, and use "man <pthread func name>" to
 *    get details of individual pthread functions.
 * 2. build the code as is and run it
 *    use something like "gcc -Wall -Werror helloT.c -lpthread -o helloT" to build
 *    then run with "./helloT <numthreads>" where <numthreads> is an integer between
 *    1 and MAXTHREADS
 *    Note that the program only creates one thread at first.
 *    The output should look like this at first:

 $ ./helloT 10
 User requested 10 threads
 Hello World from thread 0 (my factorial is 1)
 Goodbye World from the main thread

 * 3. Update the code to create <numthreads> threads with each thread
 *    computing factorial and outputting accordingly. Output should look like this:

 $ ./helloT 10
 User requested 10 threads
 Hello World from thread 0 (my factorial is 1)
 Hello World from thread 1 (my factorial is 1)
 Hello World from thread 2 (my factorial is 2)
 Hello World from thread 3 (my factorial is 6)
 Hello World from thread 4 (my factorial is 24)
 Hello World from thread 5 (my factorial is 120)
 Hello World from thread 6 (my factorial is 720)
 Hello World from thread 7 (my factorial is 5040)
 Hello World from thread 8 (my factorial is 40320)
 Hello World from thread 9 (my factorial is 362880)
 Goodbye World from the main thread

 Note that it is not necessary for the threads to output in order as shown above.
 */
