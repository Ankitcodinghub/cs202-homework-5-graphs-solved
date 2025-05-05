# cs202-homework-5-graphs-solved
**TO GET THIS SOLUTION VISIT:** [CS202 Homework 5-Graphs Solved](https://www.ankitcodinghub.com/product/cs202-homework-5-graphs-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100263&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS202 Homework 5-Graphs Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
Please do not start the assignment before reading these notes.

<ol>
<li>Before 23:55, June 1, upload your solutions in a single ZIP archive using Moodle submission form. Name the file as studentID_secNo_hw5.zip.</li>
<li>Your ZIP archive should contain the following files:
<ul>
<li>– &nbsp;C++ source codes (files FriendNet.h and FriendNet.cpp as well as the files containing any extra class you will use). But this time, do not include the file that contains the main function. We will write our own main function to test your programs.</li>
<li>– &nbsp;Do not put any unnecessary files such as the auxiliary files generated from your favorite IDE. Be careful to avoid using any OS dependent utilities.</li>
</ul>
</li>
<li>You MUST use the adjacency list representation for the graph implementation. If you use the adjacency matrix representation, you will get no points from this assignment.</li>
<li>Your implementation should not have any memory leak.</li>
<li>Although you may use any platform or any operating system to implement your algorithms, your code should work on the dijkstra server (dijkstra.ug.bcc.bilkent.edu.tr). We will compile and test your programs on that server. Please make sure that you are aware of the homework grading policy that is explained in the rubric for homework assignments. Please check the following website https://docs.google.com/document/d/1jyGik6lsghu7KdSk75wwAcjTwo__4nbtIXrWK4_L75w/edit.</li>
<li>This homework will be graded by your TA, Can Taylan Sarı. However, you can contact both TAs for any homework related questions.</li>
</ol>
Attention: For this assignment, you may use the codes given in your textbook and the slides. However, you ARE NOT ALLOWED to use any codes from other sources (including the codes given in other textbooks, found on the internet, and belonging to your classmates). Furthermore, you ARE NOT ALLOWED to use any data structure or function from the C++ standard template library (STL).

Do not forget that plagiarism and cheating will be heavily punished. Please do the homework yourself.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Implement a simple friendship network. Represent this friendship network by a graph and answer the queries, each of which corresponds to calling a member function, on this graph.

Below is the required public part of the FriendNet class that you will implement. The name of the class must be FriendNet, and must include these public member functions. We will use these functions to test your code. The interface must be written in a file called FriendNet.h and the implementation must be written in a file called FriendNet.cpp. You may define additional private data members and member functions for the FriendNet class, if necessary. You may also define additional classes.

You have to use the adjacency list representation to represent edges in this class.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>#include &lt;string&gt;
using namespace std;
</pre>
<pre>class FriendNet{
</pre>
<pre>public:
     FriendNet(const string fileName);
     FriendNet(const FriendNet&amp; aNet);
     ~FriendNet();
</pre>
</div>
<div class="column">
<pre>// constructor
// copy constructor
// destructor
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
void listFriends(const string personName, const int hopNo);

<pre>     void displayAverageDegrees();
     void displayDiameters();
</pre>
<pre>private:
     // ...
</pre>
// define your data members here

// define private class functions here, if you have any // YOU HAVE TO USE THE ADJACENCY LIST REPRESENTATION

};

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The details of the member functions are as follows:

 FriendNet(const string fileName);

The default constructor loads a friendship network from an input file called fileName. The first row of this file indicates the number of people in the network and each subsequent row includes information of a particular person. This information contains &lt;id&gt; &lt;name&gt; &lt;degree&gt; &lt;friend_id&gt; tokens separated by white space. For a particular person P,

<ul>
<li>– &nbsp;&lt;id&gt; and &lt;name&gt; are the id and the name of person P, respectively.</li>
<li>– &nbsp;&lt;degree&gt; is the number of friends of person P.</li>
<li>– &nbsp;&lt;friend_id&gt; is the id of a friend of person P. Note that a person may have zero or more friends
and there will be exactly &lt;degree&gt; friend ids after the degree token.

In this assignment, you may assume that the contents of the input file are always valid. You may also assume that the ids and the names are unique and the ids are in the range of 0 and N – 1, where N is the number of people in the network. You may also assume that all names are case sensitive and do not contain any spaces, e.g., John Doe is written as JohnDoe in the file.
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Note that, if the input file fileName does not exist, then the default constructor creates an empty friendship network.

As an example, the table shown on the left is an input file for the network illustrated on the right. This file contains 17 people, as indicated in its first line. For example, the fifth line of this file indicates that the person with an id of 3 has the name of Dogan and has four friends, with the ids of 14, 0, 1, and 2.

 void listFriends(const string personName, const int hopNo);

It lists the names of all people that are accessible from a given person, whose name is personName, within the given number hopNo of hops (i.e., using at most hopNo edges). If this given person does not take place in the friendship network, give a warning message. If the given number of hops is non- positive, do not list any people. See the output example below for the format. You may assume that the names are unique within the friendship network.

 void displayAverageDegrees();

It calculates and displays the average degree of each connected component within the friendship network. The degree of a vertex is defined as the number of its neighbors. The average degree of a connected component is the mean of the degrees computed for every vertex in this connected component. See the output example below for the format.

 void displayDiameters();

It calculates and displays the diameter of each connected component within the friendship network. The diameter of a connected component is the longest of the shortest paths between any pair of vertices within this connected component. See the output example below for the format.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
17

<ol start="0">
<li>0 &nbsp;Ali</li>
<li>1 &nbsp;Beril</li>
<li>2 &nbsp;Cigdem</li>
<li>3 &nbsp;Dogan</li>
</ol>
4Ebru

<ol start="5">
<li>5 &nbsp;Funda</li>
<li>6 &nbsp;Gamze</li>
<li>7 &nbsp;Hande</li>
<li>8 &nbsp;Ibrahim</li>
<li>9 &nbsp;Jale</li>
<li>10 &nbsp;Kenan</li>
<li>11 &nbsp;Leman</li>
<li>12 &nbsp;Mahmut</li>
<li>13 &nbsp;Nalan</li>
<li>14 &nbsp;Okan</li>
<li>15 &nbsp;Pinar</li>
<li>16 &nbsp;Rana</li>
</ol>
</div>
<div class="column">
411432 203 4101403 414012 2167

0

111

2164

2 10 13 412111310 52131289 31596

3 10 9 15 39108 3203 21211

247

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Below is an example test program that uses this class and the corresponding output. This test program uses the friendship network illustrated above. Assume that the name of the input file is “friends.txt”. Of course, use other programs to test your implementation.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>#include &lt;iostream&gt;
using namespace std;
#include "FriendNet.h"
</pre>
<pre>int main(){
   FriendNet F("friends.txt");
</pre>
F.listFriends(“Selim”, 2); F.listFriends(“Funda”, 1); F.listFriends(“Cigdem”, -1); cout &lt;&lt; endl;

F.listFriends(“Ibrahim”, 2); F.listFriends(“Ibrahim”, 3); cout &lt;&lt; endl;

F.displayAverageDegrees(); cout &lt;&lt; endl; F.displayDiameters();

cout &lt;&lt; endl;

return 0; }

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
The output of this program will be as follows.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Selim does not exist in the network.

People accessible from Funda within 1 hops: NOBODY People accessible from Cigdem within -1 hops: NOBODY

People accessible from Ibrahim within 2 hops: Cigdem, Jale, Kenan, Mahmut, Nalan People accessible from Ibrahim within 3 hops: Ali, Cigdem, Dogan, Jale, Kenan,

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Leman, Mahmut, Nalan,
</pre>
<pre>There are 3 connected
For component 0: 3.08
For component 1: 2.00
For component 2: 0.00
</pre>
<pre>There are 3 connected
For component 0: 6
For component 1: 1
For component 2: 0
</pre>
</div>
<div class="column">
Okan, Pinar

components. The average degrees are:

components. The diameters are:

</div>
</div>
</div>
</div>
