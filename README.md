# xv6-Lottery-Scheduling
A lottery scheduling code for xv6 system

Usage:
1. Download the xv6-3.tar file.

2. Unzip the .tar file.

3. Use the following commands to compile the xv6 system and run it.

```
$ make
$ make qemu-nox
```

4. In xv6 system. 

    4.1.  Use the following code to set tickets to a program.
```
tickets <num_of_tickets> <program_name>
```
For example,
```
tickets 10 spin &
```
, where spin is simply a program that runs an infinite loop.

    4.2. Use the following command to check how many ticks each process has been assigned and dump the information to stdout.
```
ps
```
  Also, use the following command to get this information every 100 xv6 ticks.
```
ps -r
```
