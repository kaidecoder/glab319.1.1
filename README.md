# GLAB 319.1.1: MongoDB Setup

## Introduction
MongoDB is one of the most popular NoSQL database solutions. This lab will guide you through the steps necessary to setup MongoDB for use throughout this module and beyond.

## Objectives
- Create a MongoDB account.
- Create a MongoDB database cluster.
- Add user authentication to the database.
- Configure the database connection.
- Load sample data into the database.
- Acquire the database connection string.
- Install MongoDB Compass.
- Connect to the database through MongoDB Compass.

## Equipment
A Windows-based computer.

## Submission
Submit your completed lab using the Start Assignment button on the assignment page in Canvas.
Your submission should include:
A connection string for your database.

## Instructions
We will begin by creating a MongoDB account, and then work through setting up a database for use throughout the next lesson. This lab is not intended to teach you how to use these tools; that will be covered in future lessons. This lab focuses only on setting up the tools.
These same steps can be repeated to set up database clusters for existing or future projects.
### Part 1: Creating a MongoDB Account
Go to account.mongodb.com/account/register to create your MongoDB account.
You may choose to sign up in one of three ways:
A Google Account
A GitHub Account
With Email and Password
We recommend linking your GitHub account for convenience, but you may choose whichever method you prefer.

### Part 2: Creating a Database
Once your account has been created, you should be greeted by the following database deployment screen. If you are not, navigate to the Database Deployments page and click "Build a Database."
Within the "Deploy your database" page, select M0, the FREE tier.
You may leave the Provider and Region sections on their default values, or select a specific provider and/or region as specified by your instructor, if necessary for this course.
Change the Name of the cluster to MongoPractice.
Click "Create."

### Part 3: User Authentication and Connections
Next, you will be brought to the Security Quickstart page in order to set up access to your database.
On this page, choose a username that you would like to use to access the database, and a secure password. Once finished, click "Create User."
The next step identifies from where you would like to connect to the database. This option is important because only registered environments will be able to make direct calls to the database.
"My Local Environment" should be selected by default. If it is not, select it. Ensure that your IP address is added to the Access List on screen.
Once you have verified the information is correct, click "Finish and Close."

### Part 4: Loading Sample Data
You should be brought to the Database Deployments page, where you can see your newly created MongoPractice cluster. There should also be an option to Load a sample dataset. Click it.
It may take a significant amount of time to load the sample datasets. Continue with the remainder of this lab while the data loads.
We will use this sample data during future lessons to explore the features and functionality of MongoDB. As you continue learning more about MongoDB, you will be able to create your own collections of data from scratch, and manipulate data within your applications.

### Part 5: Acquiring a Connection String
The MongoDB connection string is a Uniform Resource Identifier (URI) string that contains all of the information that an application needs to connect to the MongoDB database it is associated with, including username and password information in many cases. For this reason, it should be kept securely.
To acquire your database's connection string for later use, click the "Connect" button on the Database Deployments page. You may do this while the sample dataset is still loading.
Take a moment to internalize the options found on this connection screen, as some of them may be useful for you in the future. For now, we are going to select "Compass."
The next screen will prompt you to download and install MongoDB Compass. Follow the instructions on this screen to download and install MongoDB Compass.
Once Compass has been installed, open it and insert your connection string. Name the connection, favorite it, and click "Save & Connect."
You should be greeted by the following screen:
For now, you are finished! Congratulations on having a live database running!
Save this document as a reference for future use, and keep your MongoDB Compass and browser tabs open so you can follow along during the next lesson.

### Part 6: Completion
Submit your database's connection string, excluding the actual password, according to the submission instructions at the beginning of this document. We do not want access to your database; we just want to verify you finished setting it up!