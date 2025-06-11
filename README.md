# comp5630-assignment-1--decision-tree-solved
**TO GET THIS SOLUTION VISIT:** [COMP5630 Assignment #1- Decision Tree Solved](https://mantutor.com/product/machine-learning-comp-5630-comp-6630-comp-6630-d01-solved-2/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109771&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5630 Assignment #1- Decision Tree Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Assignment #1 Decision Tree

Submission Instructions

Tasks

1. Decision Tree Basics [50 pts]: The goal of this assignment is to test and reinforce your understanding of Decision Tree Classifiers.

(a) [5 pts] How many unique, perfect binary trees of depth 3 can be drawn if we have 5 attributes. By depth, we mean depth of the splits, not including the nodes that only contain a label. So a tree that checks just one attribute is a depth 1 tree. By perfect binary tree, we mean every node has either 0 or 2 children, and every leaf is at the same depth. Note also that a tree with the same attributes but organized at different depths

are considered “unique”. Do not include trees that test the same attribute along the same path in the tree.

[5 pts] In general, for a problem with A attributes, how many unique full D depth trees can be drawn? Assume A&gt;&gt;D

(b) [20 pts] Consider the following dataset for this problem. Given the five attributes on the left, we want to predict if the student got an A in the course. Create 2 decision trees for this dataset. For the first, only go to depth 1. For the second go to depth 2. For all trees, use the ID3 entropy algorithm from class. For each node of the tree, show the decision, the number of positive and negative examples and show the entropy at that node.

Early Finished HMK Senior Likes Coffee Liked The Last Jedi A

1 1 0 0 1 1

1 1 1 0 1 1

0 0 1 0 0 0

0 1 1 0 1 0

0 1 1 0 0 1

0 0 1 1 1 1

1 0 0 0 1 0

0 1 0 1 1 1

0 0 1 0 1 1

1 0 0 0 0 0

1 1 1 0 0 1

0 1 1 1 1 0

0 0 0 0 1 0

1 0 0 1 0 1

Table 1: Toy Data-set for Task 1: Decision Tree Basics.

(c) [10 pts] Make one more decision tree. Use the same procedure as in (b), but make it depth 3. Now, given these three trees, which would you prefer if you wanted to predict the grades of 10 new students who are not included in this data-set? Justify your choice.

(d) [10 pts] Recall the definition of the “realizable” case. “For some fixed concept class C, such as decision trees, a realizable case is one where the algorithm gets a sample consistent with some concept c∈C. In other words, for decision trees, a case is realizable if there is some tree that perfectly classifies the data-set.

If the number of attributes A is sufficiently large, under what condition would a dataset not be realizable for decision trees of no fixed depth? Prove that the dataset is unrealizable if and only if that condition is true.

2. Application on Real-Word Data-set [50 pts]: In this task, you will build a decision tree classifier using a real-word data-set called Census-Income Data Set available publicly for downloading at Dataset. This data set contains weighted census data extracted from the 1994 and 1995 Current Population Surveys conducted by the U.S. Census Bureau. The data contains 41 demographic and employment related variables.

One instance per line with comma delimited fields. There are 199,523 instances in the data file and 99,762 in the test file.

The data was split into train/test in approximately , proportions using MineSet’s MIndUtil mineset-to-mlc. Below are your tasks:

(b) [15 pts] Using the trained classifier with optimal cut-off depth k, classify the 99,762 instances from the test file and report the testing accuracy (portion of testing instances classified correctly).

(c) [15 pts] Do you see any over-fitting issues for this experiment? Report your observations.
