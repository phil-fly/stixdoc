# STIX Cyber-observable Objects（SCO）
    威胁情报中具体的可观察对象，用于刻画基于主机或基于网络的信息。

- SCO会被多种SDO所使用，以提供上下文支持，如Observed Data SDO，表示在特定时间观察到的raw data；在STIX2.0中，SCO在SDO中出现时只会以Observed Data的形式出现，在STIX2.1则不限于此。
- SCO本身不包括who，when和why的信息，但是将SCO和SDO关联起来，可能会得到这些信息以及对威胁更高层面的理解。
- SCO可以捕获的对象包括文件、进程、IP之间的流量等。