## Buffer-Cache-Sim

Simulation of getBlk() function of Buffer Cache



## About Package:

Our project is the simulation of buffer cache’s getBlk()
function. We have handled all five scenarios for getBlk()
function. The language used in this package is Python.
We have used Jupyter notebook for this purpose.


## Functions and features of our package:

We have a class called BufferCache which consists of all
functions related to getBlk() function.

Some important functions of Buffer Cache Class are,
   getBlk() - This doesn’t bring block number but it gets
    the block number and makes the block busy for some
    time before freeing it.
   diskWrite() - For Scenario 3
   freeListEmpty() - For Scenario 5

We have used synchronized locks and event locks for
thread handling, since each getBlk() function is running
in a separate thread.
