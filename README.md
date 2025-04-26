# cs7646-ml4t-project-5-p0-solved
**TO GET THIS SOLUTION VISIT:** [CS7646-ML4T Project 5 P0 Solved](https://www.ankitcodinghub.com/product/cs7646-ml4t-p0-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;124409&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS7646-ML4T Project 5  P0 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
PROJECT 5: MARKETSIM

h

Table of Contents

Overview

About the Project

Assignment Project Exam HelpYour Implementation

Contents of Reporthttps://tutorcs.com

Testing Recommendations

Submission Requirements

Grading Information

Development Guidelines

REVISIONS

1 OVERVIEW

In this project, you will create a market simulator that accepts trading orders and keeps track of a portfolio’s value over time. It also then assesses the performance of that portfolio. You will submit the code for the project to Gradescope SUBMISSION. There is no report associated with this project.

1.1 Learning Objectives

The speci c learning objectives for this assignment are focused on the following areas:

Market Simulation: Develop a market simulator. Variations of this market simulator will play a role in future projects.

Transaction Costs: Develop an understanding of market costs and how they a ect the value of a portfolio.

2 ABOUT THE PROAssignmentJ PrECToject Exam Help

In this project, you will leverage some of the work completed in project 2 to build a market simulator, as described below.https://tutorcs.com

3 YOUR IMPLEMENTATION

Your submission must implement this API speci cation.

TESTING. Once you are satis ed with the results in testing, submit the code to Gradescope SUBMISSION. Only code submitted to Gradescope SUBMISSION will be graded. If you submit your code to Gradescope TESTING and have not also submitted your code to Gradescope SUBMISSION, you will receive a zero (0).

3.1 Getting Started

You will be given a starter framework to make it easier to get started on the project and focus on the concepts involved. This framework assumes you have already set up the local environment and ML4T Software. The framework for Project 5 can be obtained from: Marketsim_2023Fall.zip.

Extract its contents into the base directory (e.g., ML4T_2023Fall). This will add a new folder called “marketsim” to the course directory structure.

Assignment Project Exam Help

Within the marketsim folder are one directory and two les:https://tutorcs.com

grade_marketsim.py

The local grading / pre-validation script. This is the same script that will be executed in the Gradescope TESTING EnvironmentWeChat: cstutorcs

marketsim.py

Student implementations will replace your compute_portvals() function within this le, modifying or replacing the existing stub code provided in the le. orders directory

A directory containing several order les can be used with this project.

3.2 Part 1: Implement the Basic Simulator (90 Points)

Your job is to implement your market simulator as a function, compute_portvals() that returns a DataFrame with one column. You should implement it within the le marketsim.py. It should adhere to the following API:

Assignment Project Exam Help

1 def compute_portvals(orders_file = “./orders/orders.csv”, start_val = 10000

2 # TODO: Your code here

3 return portvalshttps://tutorcs.com marketsim_api.py hosted with ❤ by GitHub view raw

orders_ le is the name of a le from which to read orders, and start_val is the starting value of the portfolio (initial cash available) commission is the xed amount in dollars charged for each transaction (both entry and exit) impact is the amount the price moves against the trader compared to the historical data at each transaction. Impact of 0.01 in the API corresponds to an impact of 1%.

Return the result (portvals) as a single-column pandas.DataFrame (column name does not matter), containing the value of the portfolio for each trading day in the rst column from start_date to end_date, inclusive.

The les containing orders are CSV les with the following columns:

Symbol (e.g. AAPL, GOOG)

Order (BUY or SELL)

Shares (no. of shares to trade)

For example:

Your simulator should calculate the total value of the portfolio for each day using

adjusted closing pricesAssignment Project Exam Help. The value for each day is cash plus the current value of equities.

The resulting data frame should contain values like this:

<blockquote class="wp-embedded-content" data-secret="jKw21bzYGo"><a href="https://tutorcs.com/">Home</a>
</blockquote>
<iframe class="wp-embedded-content lazyload" sandbox="allow-scripts" security="restricted" style="position: absolute; visibility: hidden;" title="“Home” — Tutor CS 代写" data-src="https://tutorcs.com/embed/#?secret=mbvuQEoOYQ#?secret=jKw21bzYGo" data-secret="jKw21bzYGo" width="600" height="338" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-load-mode="1"></iframe>

3.2.1 How it Should Work

Your code should keep account of how many shares of each stock are in the portfolio on each day and how much cash is available on each day. Note that negative shares and negative cash are possible. Negative shares mean that the portfolio is in a short position for that stock. Negative cash means that you’ve borrowed money from the broker.

When a BUY order occurs, you should add the appropriate number of shares to the count for that stock and subtract the appropriate cost of the shares from the cash account. The cost should be determined using the adjusted close price for that stock on that day.

When a SELL order occurs, it works in reverse: You should subtract the number of shares from the count and add to the cash account.

3.2.2 Evaluation

We will evaluate your code by calling compute_portvals() with multiple test cases. No other function in your code will be called by us, so do not depend on “main” code being called. Do not depend on global variables.

For debugging purposes, you should write your own additional helper function to call compute_portvals() with your own test cases. We suggest that you analyze and con rm the following factors:

Plot the price history over the trading period.

Sharpe ratio (Always assume you have 252 trading days in a year. And risk-free rate = 0) of the total portfolio

Cumulative return of the total portfolio

Standard deviation of daily returns of the total portfolio

Average daily return of the total portfolio Ending value of the portfolio

Assignment Project Exam Help

3.3 Part 2: Transaction Costs (10 points)

Note: We strongly encourage you to get the basic simulator working before you implementhttps://tutorcs.com the transaction cost and market impact components of this project.

High transaction costs encourage less frequent trading, and accordingly a search for strategies that payout over longer periods of time rather than just intraday or over several days. For this project, we will consider two components of transaction cost:

Commissions and market impact.

Commissions: For each trade that you execute, charge a commission according to the parameter sent. Treat that as a deduction from your cash balance.

Market impact: For each trade that you execute, assume that the stock price moves against you according to the impact parameter. So, if you are buying, assume the price goes up (e.g., rises 50 bps) before your purchase. Similarly, if selling, assume the price drops (e.g., falls 50 bps) before the sale. For simplicity treat the market impact penalty as a deduction from your cash balance.

Commissions and Market Impact should be applied for EACH transaction, for instance, depending on the parameter settings, a complete entry and exit will cost 2 * $9.95, plus 0.5% of the entry price and 0.5% of the exit price.

3.4 Part 3: Implement author() function (deduction if not implemented)

And here’s an example of how it could be called from a testing program:

1 import marketsim as ms

2

3 print(ms.author())

markeAssignment Project Exam Helptsim_author_call.py hosted with ❤ by GitHub view raw Implementing this method correctly does not provide any points, but there will be ahttps://tutorcs.com penalty for not implementing it.

3.5 Technical RequirementsWeChat: cstutorcs

The following technical requirements apply to this assignment

1. When utilizing any of the example order les, the code must run in less than 10 seconds per test case.

3. You should use pandas’ read_csv function to read the orders les.

5. The Sharpe ratio uses the sample standard deviation.

3.6 Hints &amp; Suggestions

Here is a video outlining an approach to solving this problem [YouTube video].

Hint, use code like this to read in the orders le:

In terms of execution prices, you should assume you get the adjusted close price for the day of the trade.

4 CONTENTS OF REPORT

There is no report associated with this assignment.

Assignment Project Exam Help

5 TESTING RECOMMENDATIONS

To test your code, you can modify the provided test_code() function in the marketsim.py le. You are encouraged to perform any unit tests necessary to install con dence that the code will run properly when submitted for grading and will produce the required results.

Additionally, we have provided the grade_marketsim.py le that can be used for your tests. This le is the same script that will be run when the code is submitted to Gradescope TESTING. This le is not a complete test suite and does not match the more stringent private grader that is used in Gradescope SUBMISSION. To run and test that the le will run from within the marketsim directory, use the command:

In addition to testing on your local machine, you are encouraged to submit your les toAssignment Project Exam Help

Gradescope TESTING, where some basic pre-validation tests will be performed against the code. No credit will be given for coding assignments that do not pass this prevalidation. Gradescope TESTING does not grade your assignment.https://tutorcs.com The Gradescope

TESTING script is not a complete test suite and does not match the more stringent private grader that is used in Gradescope SUBMISSION. Thus, the maximum

Gradescope TESTING score of 87, while instructional, does not represent the minimumWeChat: cstutorcs score one can expect when the assignment is graded using the private grading script. You are encouraged to develop additional tests to ensure that all project requirements are met.

You are allowed unlimited resubmissions to Gradescope TESTING. Please refer to the Gradescope Instructions for more information.

5.1 Additional Example Tests/Checks (Orders File Code

Check Examples)

Example orders les are available in the orders subdirectory. You can use these for additional testing.

Here are some additional test cases: testcases_mc2p1.zip additional_orders.zip

5.2 Short Code Check Example

Here is a very, very short example that you can use to check your code. Starting conditions:

For the orders le orders-short.csv, the orders are:

The daily value of the portfolio (spaces added to help things line up):

Assignment Project Exam Help

1 2011-01-05 997495.775 2 2011-01-06 997090.775 3 2011-01-07https://tutorcs.com 1000660.775 4 2011-01-10 1010125.775 5 2011-01-11 1008910.775

6 2011-01-12WeChat: cstutorcs 1013065.775

7 2011-01-13 1014940.775 8 2011-01-14 1019125.775 9 2011-01-18 1007425.775 10 2011-01-19 1004725.775 11 2011-01-20 993036.375

short_exmaple_3 hosted with ❤ by GitHub view raw

For reference, here are the adjusted close values for AAPL on the relevant days:

The full results:

1 Data Range: 2011-01-05 00:00:00 to 2011-01-20 00:00:00 2 Sharpe Ratio of Fund: -1.00015025363 3 Sharpe Ratio of $SPX: 0.882168679776 4 Cumulative Return of Fund: -0.00447059537671 5 Cumulative Return of $SPX: 0.00289841448894 6 Standard Deviation of Fund: 0.00678073274458 7 Standard Deviation of $SPX: 0.00544933521991 8 Average Daily Return of Fund: -0.000427210193308 9 Average Daily Return of $SPX: 0.000302827205547 10 Final Portfolio Value: 993036.375 Assignment Project Exam Help

short_example_5 hosted with ❤ by GitHub view raw https://tutorcs.com

We provide an example, orders.csv that you can use to test your code, and compare with others. All runs assume a starting portfolio of 1000000 ($1M).

orders2.csv

The other sample le is orders2.csv that you can use to test your code and compare with others.

Assignment Project Exam Help

6 SUBMISSION REQUIREMENTS

6.1 Report Submission

There is no report submission associated with this assignment.

6.2 Code SubmissionAssignment Project Exam Help

This class uses Gradescope, a server-side auto-grader, to evaluate your code submission. No credit will be given for code that does not run in this environment and students are encouraged to leverage Gradescope TESTING prior to submitting anhttps://tutorcs.com

assignment for grading. Only code submitted to Gradescope SUBMISSION will be

graded. If you submit your code to Gradescope TESTING and have not alsoWeChat: cstutorcs submitted your code to Gradescope SUBMISSION, you will receive a zero (0).

Please submit the following le to Gradescope SUBMISSION:

marketsim.py

Do not submit any other les.

Important: You are allowed a MAXIMUM of ve (5) code submissions to Gradescope SUBMISSION.

7 GRADING INFORMATION

7.1 Grading RubricAssignment Project Exam Help

7.1.1 Report [0 points]

<blockquote class="wp-embedded-content" data-secret="jKw21bzYGo"><a href="https://tutorcs.com/">Home</a>
</blockquote>
<iframe class="wp-embedded-content lazyload" sandbox="allow-scripts" security="restricted" style="position: absolute; visibility: hidden;" title="“Home” — Tutor CS 代写" data-src="https://tutorcs.com/embed/#?secret=mbvuQEoOYQ#?secret=jKw21bzYGo" data-secret="jKw21bzYGo" width="600" height="338" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" data-load-mode="1"></iframe>

There is no report associated with this project.

There is no separate code section associated with this project.

7.1.3 Auto-Grader (Private Grading Script) [100 points]

We will test your code against the following cases:

Basic simulator: (90 points) 10 test cases: We will test your code against 10 cases (9 points per case) without transaction costs. Points per case are allocated as follows:

5.0: Correct portfolio value on the last day +-0.1%

1.0: Correct Sharpe Ratio +-0.1%

1.0: Correct average daily return +-0.1%

Transaction costs: (10 points) 5 test cases: We will test your code against 5 cases as follows:

2.0: Two test cases that evaluate commissions only (impact = 0)

2.0: Two test cases that evaluate impact only (commission = 0)

1.0: One test case with non-zero commission and impact.

8 DEVELOPMENT GUIDELINES (ALLOWED &amp; PROHIBITED)

See the Course Development Recommendations, Guidelines, and Rules for the complete list of requirements applicable to all course assignments. The Project Technical

Requirements are grouped into three sections: Always Allowed, Prohibited with Some Exceptions, and Always Prohibited.

The following exemptions to the Course Development Recommendations, Guidelines, and Rules apply to this project:
