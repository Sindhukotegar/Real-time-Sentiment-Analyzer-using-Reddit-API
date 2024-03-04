# Real-time-Sentiment-Analyzer-using-Reddit-API



Introduction
Reddit is a social news site where users create and share content, with millions of active users daily. This network contains millions of rich data that can be used in sentiment analysis projects. Reddit is one of the biggest platforms where individuals ask questions and share ideas regarding topics ranging from Politics, Entertainment, Money, Tech, etc.

Prerequisites
To follow this article you will need the following installed and activated on your PC. Also, feel free to fork the GitHub Repo for the code and other necessary materials.
  Reddit Developer Account.
  Installation of PRAW Library.
  
Developer Application
In order to have full access to Reddit API, you will need to create a developer account. This can be done by clicking on this link Prefs and follow the instruction .

App Name: Firstly, you need to give your app a name.
Script: Check the Script button, this is used for personal use and projects
Redirect Uri: For this, we will be using our local host of our pc ”https://localhost:8888" or 8080.
Create app: The create app will help you generate an ID number and Secret key. (Copy both keys and keep them in a safe place).
Keys: Copy both keys as they will be needed in the code.

PRAW Installation
The PRAW library provides a means of communication with the Reddit server, it is also known as the Python Reddit API wrapper. It supports three types of applications; Web Applications, Installed Applications, and Script Applications.
Note before you can use the PRAW library, you first must register the appropriate application type on Reddit

Authentication
At this stage, this is where the “user_agent, keys, and client id” are needed.
