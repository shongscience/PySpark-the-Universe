## 1. Why PySpark for Astronomy?

Apache Spark has many wonderful features that we (python programmers?!  astronomers?!) even do not have to know during our life time.  

One little feature of python UDF is quite enough why we need to learn PySpark, 
since we can  apply our hand-made python function (User Defined Function; UDF) to data 
in parallel ways by utilizing hundreds or thousands of cpu cores simultaneously. 

I was amused by using the multi-thread capability of python. I could run 4 or 6 threads in parallel, which excelled my computation! 
But, now, my little 4 nodes' Spark Cluster can run 48 threads simultaneously for the same python code (python UDF). Yeh! 

Surely, this is only one of what PySpark can do. My major task is to measure graph statistics from big astronomical data sets. 
Currently, I am dealing with 18 million galaxies. For even a small linking length of 0.8 Mpc, my friends-of-friends network calculations already use up 80 Gb memory. 
Yes, this cannot be done without Spark Cluster and I need hundreds of Gb memory to complete my analyses.  
Spark can handle even 1000Gb memory in calculations easily?! Another Yeh! 

I am a pro-bigdata astronomer, strongly suggesting that we need to adopt the python/PySpark platform more actively in astronomical field. 

Try, then you will love it! 

For details, check out the wiki
