# 1967_TheeDiameter

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1967_TheeDiameter/blob/main/1967_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , dfs

## What was the key point and the hard part?

At first ,I thought checking all distance between 2 node will give the answer. 

Because we have only 10000 nodes and 9999 edges, O(10000 * (10000+9999)) will work in 2 seconds.

This algorithm got passed , but I thought there will be more simpler way.

I found out that one of endpoint nodes will be all ways far away from any nodes.

So, after doing one dfs , find out most far away nodes, and do dfs again starting from that node and the max distance will be the answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
