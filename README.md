# ee451-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [EE451 Assignment 3 Solved](https://www.ankitcodinghub.com/product/ee451-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100470&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE451 Assignment 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1. Login to the USC Discovery Cluster

<ul>
<li>The host is: discovery.usc.edu</li>
<li>The username and password are the same as your USC account. You are able to use ssh to login to the cluster (remember to replace YOUR USC NET ID with your actual usc net ID.):
ssh YOUR_USC_NET_ID@discovery.usc.edu
</li>
<li>Do not run your program in the login node</li>
<li>After login, use the ‘srun’ command to run your program on a remote node. For
example:
</li>
</ul>
srun -n 1 ./&lt;your executable &gt;

2. Spark Examples

To run a Spark python program, for example, the ‘pi.py’ (the provided example used

to calculate the pi (π) value), follow the steps:

<ol>
<li>Login to the Discovery cluster</li>
<li>Load the JDK needed by the Spark framework
module load openjdk/1.8.0_202-b08
</li>
<li>Install Spark:</li>
<li>Run the example (Note that directly copying the command from the PDF file sometimes introduces some unnecessary space characters (depending on the PDF reader). You may need to manually delete these spaces so that the command can work correctly.):
srun -n 1 ./spark/bin/spark-submit ./spark/examples/src/main/python/pi.py
</li>
<li>Expected output: There is a lot of console output of the Spark framework. If the program runs correctly, you can find a line similar to:
Pi is roughly 3.145080
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
wget https://ftp.wayne.edu/apache/spark/spark-2.4.7/spark-2.4.7-bin-hadoop2.7. tgz

tar xvf spark-2.4.7-bin-hadoop2.7.tgz mv spark-2.4.7-bin-hadoop2.7 spark

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3. Introduction

</div>
</div>
<div class="layoutArea">
<div class="column">
The objective of this assignment is to gain experience with programming using the MapReduce programming model [1] in Apache Spark Cluster programming framework [2]. Apache Spark supports SCALA, python and java as programming languages. This as- signment uses python as the programming language. If you use any other language, please provide detailed instructions for running the program in your submission.

4. K-means Clustering

Based on the discussion slides, complete the Map (mapToCluster) and Reduce (updatemeans) functions (you are only allowed to modify these two functions) of kmeans.py to imple- ment the K-means clustering algorithm under the MapReduce programming model [15 points]. Run the program and submit the produced output file (kmeans output)[5 points] and your code.

Note: In your K-means implementation, if a data point has multiple closest cluster centers, you should select the first one (the cluster center with the smallest index).

You can use the following command to run your kmeans implementation (data.txt and means.txt are the provided standard inputs.):

srun -n 1 ./spark/bin/spark-submit kmeans.py data.txt means.txt

5. Triangle Counting

Based on the discussion slides, write a program which uses the map/reduce functions in Apache spark to count the number of triangles in a graph. The input graph and the description of its format is provided in the file named: p2p-Gnutella06.txt.

A python helper program named readgraph.py is provided which reads the input file and populates the nodes and edges to help you get started (you can run it using: python readgraph.py).

Your program (Please name it as trianglecounting.py) should produce an output file (Name the output file as ’triangle output’.) which contains the number of triangles to which each vertex belongs to. [25 points]. Run the program and submit the code and the output file produced.

You should be able to run your program using the following command:

srun -n 1 ./spark/bin/spark-submit trianglecounting.py p2p-Gnutella06.txt

6. Submission

• Code: ‘kmeans.py’ and the output file ’kmeans output’.

• Code: ‘trianglecounting.py’ and the output file ’triangle output’.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
• Report: Write clearly how to compile and run your code. Report the screenshots of the execution on the Discovery cluster.

You may discuss the algorithms. However, the programs have to be written individually. Submit the code, produced files and the report via Blackboard. Make sure your program is runnable.

Note: You must use the Spark MapReduce programming model to implement the K-means and triangle-counting algorithms. Implementation using pure Python code without invoking the Spark framework is NOT acceptable.

References

<ol>
<li>[1] &nbsp;“MapReduce, http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce- osdi04.pdf</li>
<li>[2] &nbsp;“Apache Spark,” https://spark.apache.org/</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea"></div>
</div>
