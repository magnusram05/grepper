# grepper

## Extend ThreadPoolExecutor to create a custom implementation for the following use case

### Write a Java program that mirrors Linux *grep command*. 

* Given a text to search and the folder where it has to be searched, it should print all the files in the folder 
that contains the search text.
* Calculate the elapsed time for each task completion.
* Configure the thread pool as per the application needs and the available hardware.  That is, minimum no. of threads that should always be available 
to execute the tasks, max. no. of threads allowed and *custom thread name*.

Note: Custom thread name is very important because we should be able to quickly troubleshoot production issues. 
Without a thread name, it is very inefficient and stressful to identified which pool's thread failed.
