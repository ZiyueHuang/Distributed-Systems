# Distributed-Systems
Lab 1 : Mapreduce, sequential and distributed fault tolerant engine

Pass all tests,

```
PASS
ok  	mapreduce	18.686s
```

Lab 2 : Raft, a distributed consensus algorithm.

Pass all tests,

```
Test (2A): initial election ...
  ... Passed
Test (2A): election after network failure ...
  ... Passed
Test (2B): basic agreement ...
  ... Passed
Test (2B): agreement despite follower disconnection ...
  ... Passed
Test (2B): no agreement if too many followers disconnect ...
  ... Passed
Test (2B): concurrent Start()s ...
  ... Passed
Test (2B): rejoin of partitioned leader ...
  ... Passed
Test (2B): leader backs up quickly over incorrect follower logs ...
  ... Passed
Test (2B): RPC counts aren't too high ...
  ... Passed
Test (2C): basic persistence ...
  ... Passed
Test (2C): more persistence ...
  ... Passed
Test (2C): partitioned leader and one follower crash, leader restarts ...
  ... Passed
Test (2C): Figure 8 ...
  ... Passed
Test (2C): unreliable agreement ...
  ... Passed
Test (2C): Figure 8 (unreliable) ...
  ... Passed
Test (2C): churn ...
  ... Passed
Test (2C): unreliable churn ...
  ... Passed
PASS
ok  	raft	188.008s
```

Lab 3 : kvraft, a distributed key value store built on raft

Pass all tests,

```
Test: One client ...
  ... Passed
Test: concurrent clients ...
  ... Passed
Test: unreliable ...
  ... Passed
Test: Concurrent Append to same key, unreliable ...
  ... Passed
Test: Progress in majority ...
  ... Passed
Test: No progress in minority ...
  ... Passed
Test: Completion after heal ...
  ... Passed
Test: many partitions ...
  ... Passed
Test: many partitions, many clients ...
  ... Passed
Test: persistence with one client ...
  ... Passed
Test: persistence with concurrent clients ...
  ... Passed
Test: persistence with concurrent clients, unreliable ...
  ... Passed
Test: persistence with concurrent clients and repartitioning servers...
  ... Passed
Test: persistence with concurrent clients and repartitioning servers, unreliable...
  ... Passed
Test: InstallSnapshot RPC ...
  ... Passed
Test: snapshot size is reasonable ...
  ... Passed
Test: persistence with one client and snapshots ...
  ... Passed
Test: persistence with several clients and snapshots ...
  ... Passed
Test: persistence with several clients, snapshots, unreliable ...
  ... Passed
Test: persistence with several clients, failures, and snapshots, unreliable ...
  ... Passed
Test: persistence with several clients, failures, and snapshots, unreliable and partitions ...
  ... Passed
PASS
ok  	kvraft	497.089s
```
