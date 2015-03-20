#Linux Scheduler Test

####CS3753 (Operating Systems)
Spring 2012
University of Colorado Boulder
Programming Assignment 3


##Folders
handout - Assignment description and documentation

##Executables
./testscript - A simple bash script for running a few sample test cases
./pi - A simple program for statistically calculating pi
./pi-sched - A simple program for statistically calculating pi using
             a specific scheduling policy
./rw - A simple i/o bound example program.
./rr_quantum - A simple program for determing the RR quantum.

##Examples
Build:

 ```bash
 make
 ```

Clean:

 ```bash
 make clean
 ```

pi:

 ```bash
 ./pi
 ./pi <Number of Iterations>
 ```

pi-sched:

 ```bash
 ./pi-sched
 ./pi-sched <Number of Iterations>
 ./pi-sched <Number of Iterations> <Scheduling Policy>
 ```

rw:

 ```bash
 ./rw
 ./rw <#Bytes to Write to Output File>
 ./rw <#Bytes to Write to Output File> <Block Size>
 ./rw <#Bytes to Write to Output File> <Block Size> <Input Filename>
 ./rw <#Bytes to Write to Output File> <Block Size> <Input Filename> <Output Filename>
 ```

testscript:

 ```bash
 ./testscript
 ```

rr_quantum:

 ```bash
 sudo ./rr_quantum
 ```
