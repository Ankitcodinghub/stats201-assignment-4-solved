# stats201-assignment-4-solved
**TO GET THIS SOLUTION VISIT:** [STATS201 Assignment 4 Solved](https://www.ankitcodinghub.com/product/stats201-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91866&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STATS201 Assignment 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Question 1

</div>
</div>
<div class="layoutArea">
<div class="column">
A marine scientist was interested in modelling the population of geoducks from the west coast of the North Island taking into account their age and an extreme storm event 10 years before. A random sample of geoducks (a big clam, the name is actually pronounced “gooey-duck”) was taken off the west coast of a North Island surf beach in 2013. Each geoduck was aged by counting rings in the shell, and the count of geoduck at each age was recorded. The population theory of geoducks suggests using the following model for the expected count at each age:

log(E[Counti]) = β0 + β1 × Agei

Here, we’ll be using a modified version of this model since there was as extreme storm event that all geoduck of age 10 or older experienced. The initial model to be fitted includes the storm effect and its interaction with age in the following way:

log(E[Counti]) = β0 + β1 × Agei + β2 × Stormi + β3 × Agei × Stormi

where Counti is the geoduck count at age i and Stormi is an indicator variable that takes the value

0 if age is less than 10, or 1 if age is at least 10.

The data is stored is Geoduck.txt which contains the following variables:

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>Count
Age
Storm
</pre>
</div>
<div class="column">
Number of geoducks counted at given value of age Years of age of geoduck

Indicator variable (0 if age&lt;10, or 1 if age ≥ 10)

</div>
</div>
<div class="layoutArea">
<div class="column">
The questions we want answered are: how does the population of geoducks change with age, did the storm event have any impact on the population, and did the relationship between age and the population count change after the storm?

<ul>
<li>Comment on the plot of the data.</li>
<li>Fit an appropriate Poisson GLM to model the number of geoducks. Determine whether the model can be simplified and determine an appropriate final model. Generate confidence interval output for this model.</li>
<li>Write a Method and Assumption Checks section.</li>
<li>Write an Executive Summary.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Question 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Now for some gruesome research from the 1950s (a very different time from today – we hope). A group of researchers investigated the utility of Streptomycin as a means of treating radiated mice. A total of 522 mice were irradiated by a burst of fast neutrons (each randomly assigned to get either a high or low dose of radiation). The mice were then randomly assigned to a treatment group, either Control or Streptomycin. The outcome of the experiment was then whether a mouse survived for 10 days or not.

The data is stored is mice.csv which contains the following variables:

n The number of mice in the group

Survived The number of mice in the group that survived for 10 days

Died The number of mice in the group that died within 10 days

Propn The proportion of mice in the group that survived for 10 days

Treatment The treatment the group received (Strept or Control)

Dose The dose level of radiation the group was given (high or low)

We wish to determine whether or not Streptomycin was effective as a radiation treatment and

whether or not the effectiveness depended on the level of radiation dose.

<ul>
<li>Comment on the plots of the data.</li>
<li>Fit an appropriate logistic regression model to investigate the effect of the predictors on the proportion of mice that survived. Carry out model checks and amend the model as needed. Determine whether the model can be simplified and determine an appropriate final model. Generate confidence interval output for this model.</li>
<li>Write a Method and Assumption Checks section.</li>
<li>Write an Executive Summary.</li>
</ul>
</div>
</div>
</div>
