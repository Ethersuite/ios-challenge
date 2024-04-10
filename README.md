# Introduction
Welcome to EtherMail's code challenge project. This repository contains an iOS application with some basic functionality
to support the development of the code test required during the hiring process for an iOS developer in EtherMail.

# The challenge
A candidate has to implement the following:

- The app should contain two scenes:

  1) List of currencies: the app should fetch a list of crypto currencies (see CoincapService and AssetsApiData).
     - This list should provide for each crypto its name, symbol, change from usd and the exchange rate in the last 24h.
     - If the user taps in any of the crypto we should display a form for purchasing (virtually) a certain amount of this crypto and save this transaction on an array or a database.

  2) List of transactions: We will display a list of all the transactions made by the user 
     - Each row of the list will display the date when they were made and the price value, p.e: 10000 USD => 0.015 BTC.
     - At the top of the transactions list the app will display the final price in USD of all the transactions (remember to store the exchange rate at the moment of the transaction).

# Guideline
The candidate is free to implement the solution in any way that they consider appropriate, but please consider that we love well designed, clear and simple code. 
SOLID principles and Clean Architecture are fundamental concepts in our development philosophy.

Below are some key points that we use to evaluate your solution:
- The functionality needs to be testable, add different types of tests as deemed appropriate.
- The App has to be implemented with SwiftUI.
- The App has to be implemented with MVVM or VIPER.
- You are allowed to use third party packages, like Alamofire or Realm.
- Injectable content will be valued very positively.
- The webserver API used in this exercise can frequently return errors when many requests (sometimes just a few) are performed from the same IP address. Take this into account as part of the exercise and treat errors properly.
- Consider your commits, we want to see how you work and how you think.

# How to submit the code challenge
- **Important:** please DO NOT Fork this project from github
- The candidate can checkout the project locally and either push it to a newly created repo with public permissions so we can access it. Alternatively...
- Please attach sample images or video of your result, show us what parts make you feel proud about the demo!
- you can clone the project and send us the completed project in a zip file.

# Reference links
- Coincap API: https://docs.coincap.io/
