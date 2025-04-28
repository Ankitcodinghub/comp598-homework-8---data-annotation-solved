# comp598-homework-8---data-annotation-solved
**TO GET THIS SOLUTION VISIT:** [COMP598 Homework 8 – Data Annotation Solved](https://www.ankitcodinghub.com/product/comp-598-homework-8-data-annotation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;118618&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP598 Homework 8 – Data Annotation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Non-standard (i.e., built-in) python libraries you can use:

– pandas

– requests

Task 1: Prep for coding (15 pts)

Write a script extract_to_tsv.py that accepts one of the files you collected from Reddit and outputs a random selection of posts from that file to a tsv (tab separated value) file. It should function like this:

extract_to_tsv.py -o &lt;out_file&gt; &lt;json_file&gt; &lt;num_posts_to_output&gt;

If there aren’t num_posts_to_output posts in the file, then the script should just output all those it finds. If there are more than num_posts_to_output (which is likely the case), then it should randomly select num_posts_to_output of them and just output those.

The output format (written to out_file) is:

Name &lt;tab&gt; title &lt;tab&gt; coding

&lt;name of first post chosen&gt; &lt;tab&gt; &lt;title of first post chosen&gt; &lt;tab&gt;

&lt;name of second post chosen&gt; &lt;tab&gt; &lt;title of the second post chosen&gt; &lt;tab&gt;

…

&lt;name of the n’th post chosen&gt; &lt;tab&gt; &lt;title of the nth post chosen&gt; &lt;tab&gt;

Note that:

– we’re including the “name” field because it uniquely identifies the post, in case you ever need to go back and check something in the original data

– whitespace between column value and the tab is optional

– the third column “coding” is intentionally blank. We’ll be completing that in the next task.

Run your script on your three files you created (one for each day) to extract 75 posts for each day. You should have one file for each day.

Task 2: Code posts (15 pts)

Our typology in this assignment has two categories:

– non-vote count (n): the post title doesn’t directly refer to vote counting – the process or the tallies themselves.

o Biden looks poised to win the election. o The situation is looking grim for democrats in Pennsylvania. o Trump claims voter fraud in multiple states.

Code all the posts that were extracted from your files by putting a “v” or “n” in the coding column next to each post. To do this, you can use a text file or, another option, would be to use a spreadsheet application – just make sure you export your results in tsv format.

Submission Instructions

Your MyCourses submission must be a single zip file entiled HW7_&lt;studentid&gt;.zip. It should contain the following items:

– scripts/ o extract_to_tsv.py – script for Task 1

– data/ o &lt;date1&gt;_posts.tsv o &lt;date2&gt;_posts.tsv o &lt;date3&gt;_posts.tsv

Notes on Grading

Your assignment will be graded

1. By the functionality of your script (in task 1)

2. Every sampled post was coded (in task 2)
