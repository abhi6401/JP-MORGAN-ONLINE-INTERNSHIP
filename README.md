![Uploading image.png…]()

https://camo.githubusercontent.com/1a5e9dd0eed60696a2ae3aa91b2370e0af78787214e2d9f4fa76738ec16c331c/68747470733a2f2f696e736964657368657270612d6173736574732e73332d61702d736f757468656173742d322e616d617a6f6e6177732e636f6d2f69636f6e732f6a706d6f7267616e2f6769746875622b7265706f2b696d616765732f6a706d2b67697475622b2e706e67
Task Overview | Installation Instructions | Link to Module 1 | JP Morgan Chase & Co Software Engineering Virtual Experience

Introduction
Experience Technology at JP Morgan Chase & Co
Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.

Module 1 Task Overview
Interface with a stock price data feed and set up your system for analysis of the data

Aim: We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

Please clone this repository to start the task
Adjust the getRatio, getDataPoint and main functions
Bonus: Pass all unit tests and add more to cover edge cases
Upload a git patch file as the submission to this task
Set up / Installation
In order to get the server and client application code working on your machine, follow the setup here

Note:This is the Python 3 version of the JPM 1 exercise. The Python 2.7 version is in this other repo

How to Run
To start the server, run
python server3.py
this will create random market called 'test.csv' in your working directory if one does not already exist.

If you encounter an issue with datautil.parser, run this command:

pip install python-dateutil
If you don't have pip yet, you can install it from: https://pip.pypa.io/en/stable/installing/

To start the example client, run:

python client3.py
To unit test the example client, run: python client_test.py

How to request from the server using curl
Query:
$ curl 'http://localhost:8080/query?id=1'
{"id": "1", "top_ask": {"price": 129.18, "size": 70}, "timestamp": "2016-08-06 12:32:11.821574", "top_bid": {"price": 128.79, "size": 61}}
How to fix the code to meet objectives
To make the changes necessary to complete the objectives of this task, follow this guide.

To do the bonus task, read this.

How to submit your work
A patch file is what is required from you to submit. To create a patch file, follow this guide. Then submit the patch file in the JPM Module 1 Page.
