# HQ Replication, paper summary

HQ Replication is combining two known approaches providing Byzantine-fault-tolerant state machine replication. One approach is replica-based approach, e.g., BFT, and the other is quorum-based approach such as Q/U.
In short HQ is using quorum-based protocol for normal execution when there is no contention. Contention is resolved with BFT approach. 