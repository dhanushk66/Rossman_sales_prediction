# Rossman_sales_prediction
Business Problem
Rossmann operates over 3,000 drug stores in 7 European countries. Currently, Rossmann
store managers are tasked with predicting their daily sales for up to six weeks in advance.
Store sales are influenced by many factors, including promotions, competition, school and
state holidays, seasonality, and locality. With thousands of individual managers predicting
sales based on their unique circumstances, the accuracy of results can be quite varied.
Data Description
We have been provided data with the following data fields.
1. Id - an Id that represents a (Store, Date) duple within the test set
2. Store - a unique Id for each store
3. Sales - the turnover for any given day (this is what you are predicting)
4. Customers - the number of customers on a given day
5. Open - an indicator for whether the store was open: 0 = closed, 1 = open
6. StateHoliday - indicates a state holiday. Normally all stores, with few exceptions, are
closed on state holidays. Note that all schools are closed on public holidays and
weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
7. SchoolHoliday - indicates if the (Store, Date) was affected by the closure of public
schools
8. StoreType - differentiates between 4 different store models: a, b, c, d
9. Assortment - describes an assortment level: a = basic, b = extra, c = extended
10. CompetitionDistance - distance in meters to the nearest competitor store
11. CompetitionOpenSince[Month/Year] - gives the approximate year and month of the
time the nearest competitor was opened
12. Promo - indicates whether a store is running a promo on that day
13. Promo2 - Promo2 is a continuing and consecutive promotion for some stores: 0 =
store is not participating, 1 = store is participating
14. Promo2Since[Year/Week] - describes the year and calendar week when the store
started participating in Promo2
15. PromoInterval - describes the consecutive intervals Promo2 is started, naming the
months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round
starts in February, May, August, November of any given year for that store.


Aim
We are provided with historical sales data for 1,115 Rossmann stores. The task is to
forecast the "Sales" column.
