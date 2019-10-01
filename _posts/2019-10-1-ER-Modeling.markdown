---
layout: post
author: Ivy
title: ER Modeling
---
Here is my Draw.io drawing

![img]({{site.baseurl}}/assets/images/ER_Draw_IO.png)

Early on when I was making this diagram, I tended to forget important practical things such as the time of the bid, and to record sales. However, I fixed this when I got to my Vertabelo Diagram.

![img]({{site.baseurl}}/assets/images/Vertabelo_Lab_1-2019-10-01_10_43.png)

I added features such as the Sales table, storing the time of a bid, and adding a start and end time to a listing. This allows users to see how long a bid will be going on for, and it also allows us to stop the bidding at the end time. Bids are basically for linking customers to listings with an amount. 

In a real site, it would be more realistic to add an address and billing details feature for the Customer table, but I feel like this is unnessicary for this lab.

I used incrementing ID's for every type of table, so that overlapping keys do make it impossible to differentiate between two instances.

I did not add a percent profit key to the Sale table, but depending on how you wish to implent it, it may be faster to just calculate the 5% instead of manually storing it.