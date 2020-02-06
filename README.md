<<<<<<< HEAD
# Key Metrics Flow

I was working with a client this week who was looking for an easy way to show some metrics about an account record right from the account layout. Number of open cases, total forecasted hours this month, total historical revenue, etc. Assuming that you have a master-detail relationship, some of these items can be calculated with rollup summary fields while others could be displayed with inline report charts. The customer, however, just wanted a simple "Key Metrics" section that they, as non developers, could easily maintain over time and would keep their layout simple.

The approach that we decided on was to build a flow. High level, the logic is to query all the needed information, process it and then display it on a flow screen. The end result is a simple, clean looking key metrics section that can be played on the account page.

## Flow diagram

![image](https://user-images.githubusercontent.com/1509672/73903011-b2fc5700-4865-11ea-9876-128eb117279b.png)

## Result

![image](https://user-images.githubusercontent.com/1509672/73903098-fce53d00-4865-11ea-9b7a-4e3fb70f9d45.png)
