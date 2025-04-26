# csci360-lab-1-solved
**TO GET THIS SOLUTION VISIT:** [CSCI360 Lab 1 Solved](https://www.ankitcodinghub.com/product/csci360-lab-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;60234&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI360 Lab 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
<ol>
<li><strong>Problem Description</strong>: We have a stack of <em>n </em>textbooks that need to be sorted, such that the frontmatter of each textbook is facing up. For example, initially, we may have the following stack (n=7):</li>
</ol>
1&nbsp;&nbsp; 0

<ul>
<li>1</li>
<li>1</li>
</ul>
7&nbsp;&nbsp; 0

3&nbsp;&nbsp; 1

2&nbsp;&nbsp; 1

6&nbsp;&nbsp; 0

where the first number in each row shows the desired order of the textbook, and the second number shows whether the cover is frontmatter of the textbook is facing up (1) or facing down (0).

The goal is to sort the textbooks so that they form the following stack:

<ul>
<li>1</li>
<li>1</li>
<li>1</li>
<li>1</li>
<li>1</li>
<li>1</li>
<li>1</li>
</ul>
However, to sort the stack, we are only allowed to select one of the textbooks, lift that textbook and all textbooks on top of it,<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a> and flip them altogether. For example, assume that we select textbook 7 in the following stack:

1&nbsp;&nbsp; 0

<ul>
<li>1</li>
<li>1</li>
</ul>
2&nbsp;&nbsp; 1

<ul>
<li>0</li>
</ul>
Flipping that textbook and everything above it will give us the following stack of textbooks:

<ul>
<li>1</li>
</ul>
5&nbsp;&nbsp; 0

4&nbsp;&nbsp; 0

1&nbsp;&nbsp; 1

3&nbsp;&nbsp; 1

2&nbsp;&nbsp; 1

6&nbsp;&nbsp; 0

1

We wish to start from an arbitrary stack, and do a finite number of flips and sort the textbooks.

<ol start="2">
<li>The goal of this Lab is that you write a program that takes an initial stack of textbooks of size <em>n</em>, and sorts them using Depth-First Search and Breadth-First Search. We have provided a skeleton code with extensive comments in the README.md file that you should read. Please use the skeleton code and submit your code to the GitHub repository that will be provided to you.</li>
</ol>
Here is how your code will be graded:

<ul>
<li>General soundness of DFS and BFS code: 2 × 30 pts.</li>
<li>Passing multiple test cases: 2 × 20 pts.</li>
</ul>
<ol start="3">
<li>(20 pts <strong>Extra Credit</strong>) For <em>n </em>= 1<em>,</em>2<em>,</em>3<em>,</em>4<em>,</em>5, generate all 2<em><sup>n</sup></em>× <em>n</em>! possible initial book stacks and solve the problem starting from each of them using DFS and BFS. For each <em>n</em>, calculate the average number of flips needed and the average number of nodes traversed when using DFS and BFS, over all possible initial textbook stacks. For example, when <em>n </em>= 3, there are 2<sup>3</sup>× 3! = 48 possible initial textbook stacks. For each initial textbook stack, calculate how many flips are needed and how many nodes are traversed to sort the textbooks for each of the DFS and BFS algorithms, and calculate the average number of flips over all 48 possible initial configurations for each of DFS and BFS algorithms, and report the average for each <em>n </em>and for each algorithm in a table. Analyze and interpret the results.</li>
</ol>
<strong>Note 1</strong>: as there may be more than one solution for each initial textbook stack, consider only one solution (the first solution your algorithms encounter) for each initial configuration when calculating averages.

<strong>Note 2</strong>: You may need to submit the results of the extra credit part separately. Instructions for submission will be given later.

2

<a href="#_ftnref1" name="_ftn1">[1]</a> The top textbook has no textbook on top of it, so in case it is selected, it will be the only textbook that flips.
