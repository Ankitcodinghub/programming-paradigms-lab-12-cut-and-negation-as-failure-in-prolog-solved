# programming-paradigms-lab-12-cut-and-negation-as-failure-in-prolog-solved
**TO GET THIS SOLUTION VISIT:** [Programming Paradigms Lab 12-Cut and negation as failure in Prolog Solved](https://www.ankitcodinghub.com/product/programming-paradigms-lab-12-cut-and-negation-as-failure-in-prolog-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100221&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Programming Paradigms Lab 12-Cut and negation as failure in Prolog Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Programming Paradigms

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Lab 12. Cut and negation as failure in Prolog

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
Non-unifiable

Exercise 11.1

Implement predicate nonunifiable/2 that succeeds whenever its arguments cannot be unified. Provide three implementations:

<ol>
<li>First, using = and \+</li>
<li>Second, using = without \+</li>
<li>Third, using cut-fail combination, without = or \+</li>
</ol>
?- nonunifiable(test, test). false

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Partitioning a list

Exercise 11.2(a)

Implement predicate partition/4 that takes a pivot and a list and produces two lists: one with elements less than the pivot and another one with elements greater than or equal to the pivot.

?- partition(3, [1, 5, 2, 6, 3, 0], L, G). L = [1, 2, 0]

G = [5, 6, 3]

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
Partitioning a list efficiently

Exercise 11.2(b)

Improve predicate partition/4, making it more efficient without changing its meaning with green cuts.

?- partition(3, [1, 5, 2, 6, 3, 0], L, G). L = [1, 2, 0]

G = [5, 6, 3]

</div>
</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="section">
<div class="layoutArea">
<div class="column">
Siblings

Exercise 11.3

Implement predicate sibling/2 that succeeds whenever two people are siblings (they share a common parent). Make sure that a person cannot be its own sibling.

?- sibling(jack, jack). false

</div>
</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="section">
<div class="layoutArea">
<div class="column">
DFS proper

Exercise 11.4

Implement predicate path/3 that searches for a path between two nodes in an undirected graph.

?- path(1, 3, Path). Path = [1, 4, 3]

</div>
<div class="column">
<pre>connected(1,2).
connected(3,4).
connected(5,6).
connected(7,8).
connected(9,10).
connected(12,13).
connected(13,14).
connected(15,16).
connected(17,18).
connected(19,20).
connected(4,1).
connected(6,3).
connected(4,7).
connected(6,11).
connected(14,9).
connected(11,15).
connected(16,12).
connected(14,17).
connected(16,19).
</pre>
</div>
</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="section">
<div class="layoutArea">
<div class="column">
Filtering unifiable terms

Exercise 11.5

Implement predicate filterUnifiable/3 that takes two lists and a term. The second list is the output argument and should contain terms from the first list that unify with the given term. The variables in the first list should not be instantiated as a result of this predicate:

?- filterUnifiable([X, b, t(Y)], t(a), List). List = [X, t(Y)]

Hint: consider using checks of the form \+ term1 = term2.

</div>
</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
Eight queens problem

Exercise 11.6

Solve the eight queens problem.

Use green cuts to make the implementation efficient.

</div>
</div>
</div>
</div>
