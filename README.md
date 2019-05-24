*******PLEASE CONSULT WITH A STOCK MARKET PROFESSIONAL**************
******** BEFORE MAKING ANY FINANCIAL DECISIONS*********************
**********NOT FOR FINANCIAL USE********************************


Summary:

We rarely find the exact data that we need prepackaged in a pretty box with a bow on it. Throughout my career as a financial analyst, I have found myself with ambiguous tasks for questions where data is often missing and/or incomplete. When this happens data professionals rarely go back to their bosses saying we can’t do this, as a matter of fact that is a great way to show incompetence and get fired. Instead, we improvise. We find workarounds to the data and we use what we call proxy data. Proxy data is data from secondary sources that we believe might provide a pattern of behavior that we expect our incomplete data to display. For example, when I was tasked with creating an annual budget for a company that I worked for which was only in existence for 6 months, we worked with data that was available for a similar company which had no longer existed. We used the data to map the annual expense cycle and averaged their revenue data to project ours. During this project, we made assumptions, recorded those assumptions and changed them when we felt like they would no longer apply to our situation. As a result, we were able to create an annual budget(which is a form of projection) of around $500M in revenue within a 5% margin of error using data that was spotty at best.

For this project, I will use machine learning techniques to create a model that will predict stock prices for an IPO company using proxy data for other companies that are similar to Lyft and try to predict stock prices for the company. I will draw upon my experience as a financial analyst, as well as my newly minted skills in Machine learning to 1) find suitable proxy companies 2) use that data to train the model to predict stock prices for recent IPO tech companies and 3) Feed that model what we know about Lyft’s stocks and predict the first six months of stock prices of Lyft.

Assumptions:

Assumptions are important when working with any sort of data modeling project. The practice of data analytics is the practice of trying to take obscure data and creating solid conclusions from that data. In order to do this we must make assumptions about how our model will mimic real world events. In order to determine the effectiveness of a model, these assumptions must be explicitly defined, developed and recorded. This is especially true when working with proxy data. The big important assumption is that the real world events will behave in predictable patterns defined by the proxy data. If things behave properly or improperly, we will need to know why and revise our model to reflect the validity of our assumptions.

My assumptions for this project are:

1) Lyft’s stock prices will behave in a similar manner to our proxy companies.

2) Our Machine learning algorithms will be able to account for seasonal variations in the business cycle and adjust the model accordingly.

3) We won’t see any major abrupt financial market disruption(ie: crash or war) over the next six months.


Conclusions:
1) Proxy data for stock prediction does not work.

2) SVR Models do not like me(yes I take it personally).

3) Some stocks are more predictable than others.

4) Predicting Stocks with Machine Learning is complex with many variables.



# Next Steps:

    1) Create a model to predict DJIA

    2) Push model to production environment with Flask app so that the model can update itself in realtime.

    3) These types of predictions will involve a lot more data.
