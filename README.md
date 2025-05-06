# ie684-lab-05-solved
**TO GET THIS SOLUTION VISIT:** [IE684 Lab 05 Solved](https://www.ankitcodinghub.com/product/ie684-lab-05-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97614&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE684 Lab 05 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
&nbsp;

Exercise 1: BFGS Method

k ← 0;

Start with a suitable point xk ∈ Rn; while not converged do

pk ← −(Bk)∇f(xk);

αk ← argminα≥0f(xk + αpk);

xk+1 ←xk +αkpk;

sk = xk+1 − xk ;

yk =∇f(xk+1)−∇f(xk);

Implement the update rule to update Bk+1. ; k ← k + 1;

end

Algorithm 1: BFGS Method

1. [R] What is a suitable initial choice of B (denoted by B0)? Justify with proper reasons.

</div>
<div class="column">
09-February-2022

</div>
</div>
<div class="layoutArea">
<div class="column">
2. ImplementthemodulesofBFGSmethodtosolvetheproblemminx∈Rn f(x)wherewehavef(x)=f(x1,x2,…,xn) =􏰈n−1 􏰆4(x2 − x )2 + (x − 1)2 )􏰇. Use backtracking line search with α0 = 0.9, ρ = 0.5, γ = 0.5 in the imple-

</div>
</div>
<div class="layoutArea">
<div class="column">
i=1 i i+1 i

mentation of BFGS method. Take the starting point to be x0 = (0, 0, . . . , 0).

<ol start="3">
<li>[R] Take n ∈ {1000, 2500, 5000, 7500, 10000}, find minimizer of the objective function in each case and compute the time taken by the BFGS method with backtracking line search. Tabulate the time taken by BFGS method for each n.</li>
<li>Use Newton’s method to solve the problem minx∈Rn f(x) . In Newton’s method implementation, use back- tracking line search with α0 = 0.9,ρ = 0.5,γ = 0.5. Take the starting point to be x0 = (0,0,…,0) in the implementation of Newton’s Method.</li>
<li>[R] Take n ∈ {1000, 2500, 5000, 7500, 10000}, find minimizer of the objective function in each case and compute the time taken by the Newton’s method with backtracking line search. Tabulate the time taken by Newton’s method for each n.</li>
<li>[R] Compare the time taken by BFGS method with backtracking line search against the time taken by Newton’s method with backtracking line search for each value of n. Plot the time taken by both methods vs n using different colors. Comment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE684, IEOR Lab Lab 05

Exercise 2:

In this exercise we shall consider the following problem:

min n q(x1,x2,…,xn)=􏰂􏰄(xi −1)2 +(x1 −x2i)2􏰅.

x=(x1 ,x2 ,…,xn )∈R

</div>
<div class="column">
09-February-2022

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Implement the required modules to compute the objective function value, gradient and Hessian for q(x).</li>
<li>Use BFGS method to solve the problem minx∈Rn q(x). Use backtracking line search with α0 = 0.9, ρ = 0.5, γ =
0.5 in the implementation of BFGS method. Take the starting point to be x0 = (0, 0, . . . , 0).
</li>
<li>[R] Take n ∈ {1000, 2500, 5000, 7500, 10000}, find minimizer of the objective function in each case and compute the time taken by the BFGS method with backtracking line search. Tabulate the time taken by BFGS method for each n.</li>
<li>Use Newton’s method to solve the problem minx∈Rn q(x). In Newton’s method implementation, use back- tracking line search with α0 = 0.9,ρ = 0.5,γ = 0.5. Take the starting point to be x0 = (0,0,…,0) in the implementation of Newton’s Method.</li>
<li>[R] Take n ∈ {1000, 2500, 5000, 7500, 10000}, find minimizer of the objective function in each case and compute the time taken by the Newton’s method with backtracking line search. Tabulate the time taken by Newton’s method for each n.</li>
<li>[R] Compare the time taken by BFGS method with backtracking line search against the time taken by Newton’s method with backtracking line search for each value of n. Plot the time taken by both methods vs n using different colors. Comment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
n i=1

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
