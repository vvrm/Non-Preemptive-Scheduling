# Non-Preemptive-Scheduling

A scheduling approach which is non pre-emptive similar to shortest job next in nature.   
 
The priority of each job is dependent on its estimated run time, and also the amount of time it has spent waiting.  
Jobs gain higher priority the longer they wait, which prevents indefinite postponement.  
The jobs that have spent a long time waiting compete against those estimated to have short run times.  
 
The priority can be computed as :  
 
                                Priority = 1+ Waiting time / Estimated run time
 
 
The Process Data is given by User and Sorted by Arrival Time.  
