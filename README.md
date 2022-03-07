# E-commerce Linear Regression
A project aiming to help an e-commerce company decide whether to focus on development of their website or mobile app. By fitting a model and analysing coefficients, we can help an e-commerce company decide whether to focus on development of their website or mobile app.

## Description
The `linear-regression.ipynb` notebook contains:
* visualization of the data,
* model training, making predictions, and evaluation of the model performance with final insights.

## The Data
The dataset consists of the following features:
* `Email` (customer's email address),
* `Address` (customer's residential address),
* `Avatar` (the color of customer's avatar on their website profile),
* `Avg. Session Length` (average time of in-store style advice sessions, in minutes),
* `Time on App` (average time spent on the mobile app, in minutes),
* `Time on Website` (average time spent on the website, in minutes),
* `Length of Membership` (number of years the customer has been a member),
* `Yearly Amount Spent` (average amount spent on online clothing purchases in the store per year, in USD).

## Project Outcome & Conlusion
The biggest impact on the `Yearly Amount Spent` has the `Length of Membership`. This means that the, quite obvious, priority of the company is to keep their customers being members as long as possible (on average, a customer shops for almost $62 worth of apparel more each year they remain the store's member).

But to answer the first question "Is it better to invest in the development of the website or mobile application?", we have to compare the coefficients of `Time on App` and `Time on Website`. Our linear regression model shows that with each minute spent on the moblie app, a store gains an average $38.5 by selling their clothing. This is a far better result than that of a time spent on website - each minute on the website helps the company sell around $0.7 worth of merchandise.

We can draw two conclusions:
1. The mobile app performs a lot better than the website, so the company's sales will not be impacted much by reducing the development of the website.
2. Since the mobile app already shows good performance, the company might want to focus on the website development to boost sales thru the website, which might show the same or similar performance as the mobile app.
