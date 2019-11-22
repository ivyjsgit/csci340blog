---
layout: post
author: Ivy
title: Alternative Databases
---

# InfluxDB

I feel like this one may be helpful for the City of Hope project in storing volunteer activity. However, I feel like the ability to update times may be a bit more difficult since we have to update when volunteers clock out.

I like the fact that it has a built in HTTP API. I think the Chronograf program would be really great for creating things such as admin dashboards.

I feel like this DBMS is useful, but only in very specific circumstances.

 

# REDIS

Having data stored in RAM seems extremely worrying. What if the database crashes, or the power is pulled? Losing data seems extremely scary, especially when a simultaneous hardware failure occurs.

Secondly, I feel like running a REDIS DB would prove far more expensive, since you need to have large amounts of RAM. I could only recommend this to companies with a need for fast data and that have lots of money.


# Cassandra 

This one alleviates my concerns about accidental deletion and hardware failures that were present in REDIS. I would be interested in seeing if it allows you to store databases across redundant disks, since backups are useless if the disks fail.

This would be very good for data that you can't afford to lose.


# PostGIS

Like InfluxDB, I feel like this database is useful in some contexts, but I feel like being locked down to a GUI is extremely limiting to the use of this.

If it had a way to connect it to your own programs, it would be very useful in applications such as mapping and pathfinding. 

This database isn't useful for everything, but if you need to store geographic information, then it is a good option.


# Neo4J
This one is giving me flashbacks to discreet math. I like the fact that it is so easy to find relationships between nodes, but I feel like it would be difficult to code for the edges. 

I feel like this one would be much harder to program for this, but I feel like it would be easier to understand conceptually in some situations.

The Cypher syntax is a bit strange. I feel like the parens, brackets, and curly brackets are a bit too much.