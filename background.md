---
layout: default
title: Background---GI-Dagstuhl IoT Hackathon 2017
---

## Background

### The Internet of Things (IoT)

The rollout of IoT faces two fundamental and often conflated challenges: (i) How to enable
communication function for all heterogeneous IoT devices, and (ii) how to securely communicate the data
associated with the things represented by one or many IoT devices. The latter is the heart of the IoT vision,
providing access to everything from door lock status and lighting levels in home automation to the flow of water
measured by a municipal meter in a smart city, an individual's blood-glucose level, and the soil pH measured
across a field by a truck-mounted sensor.

Today's communication frameworks are built using the host-to-host paradigm of the Internet Protocol (IP),
binding the embedded devices with their associated real-world things at the network level. Moreover, there is
a tendency to emphasize device-to-device connectivity, which leads to a series of mappings to meet the needs
of applications to access the associated real-world data. On the long-term, the status quo is considered to be
inefficient and error-prone, finally preventing (or at least significantly complicating) large-scale deployment of
the IoT.

### From Host-to-Host to Information-centric Communication

Information-Centric Networking (ICN) is a promising approach to address the needs of IoT applications natively at the network level.
Instead of sending packets between source and destination devices identified by numeric IP addresses, in ICN the network disseminates the named and secured pieces of data, forwarding directly on names that carry application semantics.
The inherent requirement to secure each data at the time of production allows data replication anywhere in the network and preserving security properties of the data over its lifetime.
Recent research showed that ICN has potential to simplify the communication stack, enhance security, and unify core application functionality.

So far, several trials exist to apply the ICN model to the IoT world.
This includes porting of ICN stacks (e.g., CCNLite, NDN-RIOT) to IoT platforms (e.g., RIOT) for constrained devices.
However, there is still very limited experience with conceptual approaches and available codebases.
The hackathon will be a great venue to explore concepts, functionality in available implementations, point out problems, and suggest enhancements through practical coding.




