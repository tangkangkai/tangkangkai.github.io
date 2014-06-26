---
layout: post
title: "BFS and DFS"
date: 2014-06-25 07:33:17 -0700
comments: true
categories: algorithm
---
Recently I've been doing [LeetCode Problems](https://oj.leetcode.com/problems) and found it's tons of fun. Meanwhile I felt my lacking of solid way solving basic questions, e.g. the topic of the post today : BFS and DFS.I searched through the Internet and found [this post](http://www.codeproject.com/Articles/32212/Introduction-to-Graph-with-Breadth-First-Search-BF) really helps me a lot.  

Basically it's important to know which data structure we use to implement the algorithm, for DFS we use Stack and for BFS we use Queue.

**The steps for DFS:**  
>Step 1: Push the root node in the Stack.  
Step 2: Loop until stack is empty.   
Step 3: Peek the node of the stack.  
Step 4: If the node has unvisited child nodes, get the unvisited child node, mark it as traversed and push it on stack.   
Step 5: If the node does not have any unvisited child nodes, pop the node from the stack. 


**The steps for DFS:**  
>Step 1: Push the root node in the Queue.  
Step 2: Loop until the queue is empty.  
Step 3: Remove the node from the Queue.   
Step 4: If the removed node has unvisited child nodes, mark them as visited and insert the unvisited children in the queue. 


