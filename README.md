# Prosper Loan Exploratory Analysis

## Author

- [David Abiose](https://www.github.com/Abiose)


##  Dataset

The prosper loan data set includes **113,937** loans with **81** different characteristics for each loan, such as the `loan amount`, the `interest rate` paid by the borrower, the `loan status`, the `borrower's income`, and many more.
The dataset can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv)
With variable description [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0)

## Summary of Findings

It was found that Prosper frequently gives its customers a loan period of **36 months or more**, and the majority of the loans were really utilized for **debt consolidation**. A significant portion of the loans are still ongoing, and there are those that have already been closed. Due to the decreased risk involved, Prosper prefers to lend to a variety of **middle- to upper-income** individuals. One of the major takeaways from this analysis is that ratings have a larger impact on loan approvals than actual loan risks..

Another finding from the data is that loans made to borrowers with **intermediate incomes** ($25,000– 49,999,  $50,000– 74,999) also appear to be more risky (high, medium-high, medium). The borrower obtained loans worth on average less between **2007 and 2009**. Because prosper reopened on July 1st, 2009, following SEC registration, it closed in 2009 to complete the SEC filing procedure. **2009** saw the loan original amount trend's low point. [Prosper 2009](https://onlinemoneyfordads.com/is-prosper-a-scam-get-the-answers-in-my-review/#:~:text=Prosper%20had%20shut%20down%20in%202009%20to%20go,scale%3B%20so%20Prosper%E2%80%99s%20rank%20is%20an%20excellent%20rating).

A further intriguing finding is that **larger loan amounts** are associated with **longer** `loan durations`, with a **60-months** loan typically costing between  **$10,000 𝑎𝑛𝑑 $15,000**. With a shorter period, this amount is greater than the typical loan amount. A loan with a **shorter term** gives a `lower average annual percentage rate` than loans with **longer periods**. For loans with shorter durations, the `APR` should ideally be lower.

## Key Insights for Presentation

I concentrated my presentation on the impact of the major factors that determine how loans are granted. I began by outlining the borrower's `monthly income` distribution, the `debt-to-income ratio`, the `annual percentage rate`, and the `interest rate`. Following that, I described the loan conditions and the percentages of `loan status` categories in the dataset before showing the relative frequency of the borrower's `job status` and the `listing categories` they chose when listing was created.

The correlation matrix was also utilized to demonstrate the connections between all significant numerical variables. I continued to demonstrate the pattern of loans provided over time before demonstrating which component, among `risk level` and `loan ratings`, had the most influence on `loan amoun`t.
