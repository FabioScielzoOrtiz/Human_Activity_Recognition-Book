# **Human Activity Recognition**

The main goal of this project is to build an intelligent system able to recognize human activity in a given period of time (one second in our case) based on five different human signals (accelerometer z, x&y, and 3-axes gyroscope).

Therefore, the system will take  as input observations of those signals for humans measured in a given period of time, the the system will process them, segmenting them into one-second-blocks, later features of those blocks of signils will be extracted, and, finally, those features will be used as input by Machine earning algorithms, that will be able to recognize the activity done in that second, that is, to predict an activity for each block of signals.

In this way this system will be capable to recognize *second by second* what kind of activity a human is (streaming learning) or was (past learning) doing during a certain period of time.

In this project all the examples are *past learning*, but the implemented system would be able to predict one-second-blocks of signals collected in real time by an approapiate device for this task, like an smart watch.

The considered activities to be recognized are the following:

1. Running
2. Walking
3. Standing
4. Sitting
5. Lying


>**Project goal:** recognize human activity *per second*. That is, given some signals of a human recorded during certain period of time (like 15 minutes), recognize the activity that person was doing in each second of that period, considering a set of 5 possible of activities: *running, walking, standing, sitting, lying*. The system is suppose to be capable of processing data in real time, and therefore, recognize human activity in real time.


```{tableofcontents}
```
