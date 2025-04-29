# cs2204-homework-5--fraudulent-transactions-solved
**TO GET THIS SOLUTION VISIT:** [CS2204 Homework 5- Fraudulent Transactions Solved](https://www.ankitcodinghub.com/product/cs2204-homework-fraudulent-transactions-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116688&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2204 Homework 5- Fraudulent Transactions Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Objectives

Learn to read text files with custom formatting

Learn how to sort tuples with selected field(s)

Learn to use the Python standard library documentation

Implement simple statistical and filtering algorithms

Background

In this assignment, you are going to implement and combine simple algorithms for finding potentially fraudulent credit card activities. You are given a text database of financial transactions

( transactions.txt ), where each line contains a single transaction. An example line from the file:

You are going to read this database and implement several filtering functions to find irregular activities. Finally, you will combine these methods to find potentially fraudulent transactions.

Tasks

You need to finish the fraud.py source file. Note: you can use the simple tests provided at the end of the file (by uncommenting those lines). Feel free to change/add/delete any testing code. The outputs of this testing code are not going to be graded. The validator program will use your code directly.

You are already given a new data type, called Transaction , with the following fields:

2. amount : should be a float value, for the USD amount

3. company : should be a string value, the name of the merchant

4. phone : should be a string value, the phone number of the merchant with a _+countrycode prefix.

1. Implement the load_transactions function. Instead of storing the results in a global variable, return a list of Transaction instances created by parsing the database. Make sure you do the proper type conversion of the field(s) where needed. (15 pts)

2. Implement the foreign_transactions function. As a simplification, foreign transactions are those where the merchant’s phone number does not start with the +1 country code. Check the documentation string (and the example testing code) for the expected behavior. (10 pts)

3. Implement the late_night_transactions function. Check the documentation string (and the example testing code) for the expected behavior. Also, you can find some additional hints below. (15 pts)

4. Implement the highest_transactions function. You need to return the top 𝑛 transaction objects, based on the USD amounts. Check the documentation string (and the example testing code) for the expected behavior. (15 pts)

5. Implement the median_expense function. You need to return a single float, which is the median value (https://en.wikipedia.org/wiki/Median) of the USD amounts in the provided transactions list. (15 pts).

6. Implement the significant_transactions function. You need to return those transactions where the

USD amount is greater than or equal to five times of the median spending for a trailing number of (previous) transactions. The number of trailing transactions is provided as a parameter. Obviously, you cannot detect a significant transaction for the first trailing number of transactions (not enough data to calculate the median) (15 pts).

7. Implement the fraudulent_transactions function to combine the results of the previous algorithms.

Check the documentation string (and the example testing code) for the expected behavior. (15 pts)

Hints

As always, you can use any approach and/or Python libraries installed with the standard Anaconda distribution.

specifically, the similarly named datetime

(https://docs.python.org/3/library/datetime.html#datetime.datetime) datatype inside this module and its strptime() (https://docs.python.org/3/library/datetime.html#datetime.datetime.strptime) method can be helpful. This is a good opportunity to learn to read Python documentation (as a practicing Python programmer, you will do this a lot!).

Grading

Penalties

Points will be deducted if you fail to set __author__ variable (-10 pts) and for each PEP 8 style errors (-1 pt for each) in your program.

Submission

Please, upload the final version of the following file(s) (and only those files) to Brightspace:

fraud.py
