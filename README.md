Download Link: https://assignmentchef.com/product/solved-neural-network-project-ii
<br>



<ol>

 <li>1. Implement the Kohonen algorithm and use it to fit a line of neurons</li>

</ol>

to a disk.  (That is, the data set is {(x,y) |  0 &lt;= x &lt;= 1, 0&lt;=y&lt;=1} for  which the distribution is uniform while the Kohonen level is linearly ordered.) Do this when you use only a few neurons (15) , when

you use many (200)?




What happens as the number of iterations of algorithm increases?




Do the same with at least <strong>two non-uniform distributions</strong> on the disk.  (For example, when the likelihood of picking a point in the data set is proportional to the size of x, but uniform to the size of y.)




You should report with snapshots of the space as the Kohonen map evolves as the number of iterations grows..




<ol start="2">

 <li>Now do the same experiments as above for fitting a circle of neurons on a “donut” shape i.e. {&lt;x.y&gt; | 1&lt;= x^2 +y^2 &lt;= 2}. The line of neurons has 30 neurons.</li>

</ol>

Be sure to report on the results of your different attempts. .(Give snapshot as the map evolves over iterations.)

Now reproduce the experiment on the “monkey hand” as described in class.  For this part you can use your own code or the Kohonen algorithm in a package (like the SOM package in Matlab).   Be sure to state what code you are using

In more detail:




<ol>

 <li>given diagram like the following; where the data is &lt;x,y&gt; is inside the “hand” which is located as a subset of {&lt;x,y&gt; |  0&lt;= x &lt;= 1,  0&lt;=y &lt;= 1} and the Kohonen space is 225 neurons arranged in a 15 x 15 mesh.   [That means data points are only within the “hand” .].  Show how the mesh is superimposed on the plane that contains the hand and how it changes over iterations.    (You can use any “hand like” figure  with 4 “fingers” you wish,)</li>

</ol>




<ol start="2">

 <li>Now “cut off a finger” (i.e. data points come only from the “hand with 3 fingers” and then continuing from the stopping point in the previous section. Show over snapshots how the mesh is rearranged.</li>

</ol>