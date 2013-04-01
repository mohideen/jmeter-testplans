JMeter - Test Plans
===========

Collection of test plans used to evaluate performance of Fedora Commons with HDFS storage.

The read datastream test plan includes a BeanShell script to verify the integrity of downloaded file via hashing. The script also preempts the JMeter memory leak issue for large file downloads. See Bug 41921 - https://issues.apache.org/bugzilla/show_bug.cgi?id=41921


