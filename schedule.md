---
title: "Schedule"
layout: splash
---

<style type="text/css">
span.discussion { color: #dc267f; font-weight: bold }
span.lecture { color: #fe6100; font-weight: bold }
</style>

## Schedule of topics and readings

This schedule is tentative, and it is neither [_sound_](https://en.wikipedia.org/wiki/Soundness) (that is, if a particular reading or topic is listed here, that doesn't mean we'll cover it!) nor [_complete_](https://en.wikipedia.org/wiki/Completeness_(logic)) (that is, if a particular reading or topic is *not* listed here, that doesn't mean we *won't* cover it!).

The course will alternate between <span class="discussion">Discussion</span> and <span class="lecture">Lecture</span> days.  For days marked <span class="discussion">Discussion</span>, you must turn in your [reading response](course-overview.html#what-to-include-in-your-reading-response) for that day's reading assignment on Canvas **by 5pm Pacific time on the day prior to the day of class**.  For example, for the paper to be discussed on Wednesday, September 29, you must turn in your reading response on Canvas by 5pm Pacific time on Tuesday, September 28.

| Date             | Topic                                          | Notes
|------------------|------------------------------------------------|------------------------------------------------------------------------------------------------------------
| Friday, 9/24     | [Course overview](course-overview.html)        | 
| Monday, 9/27     | <span class="lecture">Lecture</span>: distributed systems: what and why?; time and clocks; Lamport diagrams | Start-of-course survey due by start of class today
| Wednesday, 9/29  | <span class="discussion">Discussion</span>: Jim Waldo et al., ["A Note on Distributed Computing" (1994)](readings/note-distributed-computing.pdf) | Reading response due 5pm PT on Tuesday, 9/28; scribes' wiki write-up due 11:59:59pm PT on Wednesday, 10/6
| Friday, 10/1     | <span class="lecture">Lecture</span>: causality and happens-before; network models; state and events; partial orders; total orders; Lamport clocks
| Monday, 10/4     | <span class="discussion">Discussion</span>: Leslie Lamport, ["Time, Clocks, and the Ordering of Events in a Distributed System" (CACM 1978)](readings/time-clocks.pdf) **(skip the section "Physical Clocks")**  | Reading response due 5pm PT on Sunday, 10/3; scribes' wiki write-up due 11:59:59pm PT on Monday, 10/11
| Wednesday, 10/6  | <span class="lecture">Lecture</span>: vector clocks; delivery vs. receiving; properties of executions: FIFO delivery, causal delivery, totally-ordered delivery
| Friday, 10/8     | <span class="discussion">Discussion</span>: Reinhard Schwarz and Friedemann Mattern, ["Detecting Causal Relationships in Distributed Computations: In Search of the Holy Grail" (_Distributed Computing_, 1994)](readings/holy-grail.pdf) **(sections 1-3 only)**  | Reading response due 5pm PT on Thursday, 10/7; scribes' wiki write-up due 11:59:59pm PT on Friday, 10/15
| Monday, 10/11    | <span class="lecture">Lecture</span>: implementing FIFO delivery; unicast/broadcast/multicast; implementing causal broadcast
| Wednesday, 10/13 | <span class="discussion">Discussion</span>: Kenneth Birman, André Schiper, and Pat Stephenson, ["Lightweight Causal and Atomic Group Multicast" (TOCS, 1991)](readings/cbcast.pdf) **(sections 1-5 only)** | Reading response due 5pm PT on Tuesday, 10/12; scribes' wiki write-up due 11:59:59pm PT on Wednesday, 10/20
| Friday, 10/15    | <span class="lecture">Lecture</span>: introduction to distributed snapshots; Chandy-Lamport snapshot algorithm
| Monday, 10/18    | <span class="discussion">Discussion</span>: K. Mani Chandy and Leslie Lamport, ["Distributed Snapshots: Determining Global States of Distributed Systems" (TOCS, 1985)](readings/chandy.pdf) | Reading response due 5pm PT on Sunday, 10/17; scribes' wiki write-up due 11:59:59pm PT on Monday, 10/25
| Wednesday, 10/20 | <span class="lecture">Lecture</span>: Chandy-Lamport wrap-up: limitations, assumptions, properties; uses of snapshots; centralized vs. decentralized algorithms; safety and liveness
| Friday, 10/22    | <span class="discussion">Discussion</span>: Bowen Alpern and Fred B. Schneider, ["Defining Liveness" (_Information Processing Letters_, 1985)](readings/liveness.pdf) | Reading response due 5pm PT on Thursday, 10/21; scribes' wiki write-up due 11:59:59pm PT on Friday, 10/29
| Monday, 10/25    | <span class="lecture">Lecture</span>: reliable delivery; fault classification and fault models; two generals problem
| Wednesday, 10/27 | <span class="discussion">Discussion</span>: Joseph Y. Halpern and Yoram Moses, ["Knowledge and Common Knowledge in a Distributed Environment" (JACM, 1990)](readings/common-knowledge.pdf) **(sections 1-4 only)** | Reading response due 5pm PT on Tuesday, 10/26; scribes' wiki write-up due 11:59:59pm PT on Wednesday, 11/3
| Friday, 10/29    | <span class="lecture">Lecture</span>: implementing reliable delivery; idempotence; so-called "exactly-once" delivery; reliable broadcast; implementing reliable broadcast; preview of replication
| Monday, 11/1     | <span class="discussion">Discussion</span>: Felix C. Gärtner, ["Fundamentals of Fault-Tolerant Distributed Computing in Asynchronous Environments" (ACM _Computing Surveys_, 1999)](readings/fault-tolerance.pdf) | Reading response due 5pm PT on Sunday, 10/31; scribes' wiki write-up due 11:59:59pm PT on Monday, 11/8
| Wednesday, 11/3  | <span class="lecture">Lecture</span>: reasons to do replication; total order vs. determinism; strong conistency (informally); primary-backup replication; chain replication; latency and throughput
| Friday, 11/5     | <span class="discussion">Discussion</span>: Robbert van Renesse and Fred B. Schneider, ["Chain Replication for Supporting High Throughput and Availability" (OSDI 2004)](readings/chain-replication.pdf) | Reading response due 5pm PT on Thursday, 11/4; scribes' wiki write-up due 11:59:59pm PT on Friday, 11/12
| Monday, 11/8     | <span class="lecture">Lecture</span>: handling node failure in replication protocols; consistency models (read-your-writes, FIFO, causal, strong); introduction to consensus; problems equivalent to consensus; the FLP result; introduction to Paxos
| Wednesday, 11/10 | <span class="discussion">Discussion</span>: Michael J. Fischer, Nancy A. Lynch, and Michael S. Paterson, ["Impossibility of Distributed Consensus with One Faulty Process" (JACM 1985)](readings/flp.pdf) | Reading response due 5pm PT on Tuesday, 11/9; scribes' wiki write-up due 11:59:59pm PT on Wednesday, 11/17
| Friday, 11/12    | <span class="lecture">Lecture</span>: Paxos: the interesting parts; Multi-Paxos
| Monday, 11/15    | <span class="discussion">Discussion</span>: Leslie Lamport, ["Paxos Made Simple" (2001)](readings/paxos-simple.pdf) | Reading response due 5pm PT on Sunday, 11/14; scribes' wiki write-up due 11:59:59pm PT on Monday, 11/22
| Wednesday, 11/17 | <span class="lecture">Lecture</span>: fault tolerance of Paxos; brief mention of other consensus protocols: Viewstamped Replication, Zab, Raft; passive vs. active (state machine) replication
| Friday, 11/19    | No class (Thanksgiving break)
| Monday, 11/22    | <span class="discussion">Discussion</span>: Tushar Chandra, Robert Griesemer, and Joshua Redstone, ["Paxos Made Live: An Engineering Perspective" (invited talk, PODC 2007)](readings/paxos-made-live.pdf) | Reading response due 5pm PT on Sunday, 11/21; scribes' wiki write-up due 11:59:59pm PT on Monday, 11/29
| Wednesday, 11/24 | <span class="lecture">Lecture</span>: eventual consistency; strong convergence and strong eventual consistency; intro to application-specific conflict resolution; network partitions; availability; the consistency/availability trade-off; anti-entropy with Merkle trees; gossip; quorum consistency
| Friday, 11/26    | <span class="discussion">Discussion</span>: Giuseppe DeCandia et al., ["Dynamo: Amazon’s Highly Available Key-value Store" (SOSP 2007)](readings/amazon-dynamo.pdf)  | Reading response due 5pm PT on Thursday, 11/25; scribes' wiki write-up due 11:59:59pm PT on Friday, 12/3
| Monday, 11/29    | <span class="lecture">Lecture</span>: sharding; consistent hashing; online systems vs. offline systems, raw data vs. derived data; intro to MapReduce
| Wednesday, 12/1  | <span class="discussion">Discussion</span>: Jeffrey Dean and Sanjay Ghemawat, ["MapReduce: Simplified Data Processing on Large Clusters" (OSDI 2004)](readings/mapreduce.pdf)  | Reading response due 5pm PT on Tuesday, 11/30; scribes' wiki write-up due 11:59:59pm PT on Wednesday, 12/8
| Friday, 12/3     | <span class="lecture">Lecture</span>: MapReduce: examples, approach to fault tolerance, combine functions; course wrap-up
| Thursday, 12/9   | **No final exam.**  Enjoy your winter break!
