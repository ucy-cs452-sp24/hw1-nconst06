# Homework 01 - EPL452
## Nicolas Constantinou 

## Capacity(GB)
We have two identical nodes we can in the same rack ,  the DRAM capacity 187.55 GB and the disk capacity of the node is 447.1 GB 

## Latency (us)
After measuring the DRAM and Disk latency using the mlc ,ioping and ping tools we can see that the local DRAM latency is the lowest. Also the network latency is significantly lower than the disk's latency. We can calculate the remote latency by adding the network latency and the local latency.

## Bandwidth (MB/s)
For the bandwidth we have really high speeds on local DRAM , 54723.7 MB/s . Using the fio command we can see that the disk bandwidth is 177.399 MB/s. The bottleneck bandwidth of the network is 640 MB/s as measured using iperf. This bandwidth applies for the Rack DRAM but not for the Rack Disk as the bandwith of the disk is lower that the network's. 

## Conclusion
As a conclusion we can say that is better to work with remote DRAMs than Local Disks because we can reah higher bandwidths.
