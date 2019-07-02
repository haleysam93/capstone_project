## Title
Mining Data from the Web with Python

## Category
Data Analysis

## Duration
30 minute slot

## Description
When performing data analysis an important step in the data analysis process is collecting the data that will be analyzed to answer the question.
This talk focuses on that data collection step and discusses different strategies for collecting the data as efficiently and accurately as possible.

The talk covers 4 different strategies for data collection using python:
- Downloading a Dataset
- Python API Wrapper Libraries
- Using Web APIs from Python
- Web Scraping

For each strategy the basic concepts are introduced and when that strategy should be used is discussed.  
Additionally, for each strategy a working example that uses that strategy will be covered. 

## Audience
Python developers that perform data analysis.

## Python Level
Beginner to Intermediate

## Objectives
Attendees will learn different strategies for mining data from the web and when to use each.

## Detailed Abstract
When performing data analysis collecting the data that will be analyzed is an important step in the overall process.
One of the most common sources of data is the web.

#### Downloading a Dataset
This is the most simple methodology for collecting data, but it should not be forgotten about.
Downloading a dataset can save a lot of time collecting and cleaning the data and should be used when possible.  
The issue that commonly arises is that a prepared dataset does not exist to support the domain you are working in.

#### Python API Wrapper Libraries
There are many python libraries that wrap Web APIs and provide users with the ability to access data.
This is often preferable to using Web APIs because they are easier to use and offer capabilities that the Web API does not.
Similar to downloading a dataset this strategy is only usable in select scenarios, but should be considered.

#### Using Web APIs from Python
Web APIs are prevelent throughout the web they can be utilized to collect data.
The requests library can be utilized to access Web APIs from Python.  
Techniques for working with private undocumented APIs are also covered.
Not all data can be accessed throught web APIs, but using this strategy should be explored prior to attempting to scrape data.

#### Web Scraping
There are instances where the only way to access the data of interest is by parsing the html.  
The BeautifulSoup library can be used to parse html files and extract data from them.
Parsing HTML has it's issues and should be avoided if there is an easier strategy. 

## Outline
1. Introduction (2 mins)
- Who am I?
- Purpose of Talk
- Agenda

2. Data Collection (2 mins)
- Frame the content of the talk within the data analysis process
- Considerations when collecting data
- Collecting Data from the Web (Web Mining)

3. Downloading Datasets (3 mins)
- Why this strategy is preferred?
- Quick Example of pandas read_csv

4. Overview of Web APIs (3 mins)
- What is a Web API?
- Quick example of using a web browser to show data returned by the Github API.

5. Python API Wrapper Libraries (5 mins)
- Discuss python API wrapper libraries and list a few of the most common
- Quick example of using the python-twitter library to get all tweets from a specific user

6. Using Web APIs from Python (10 mins)
- Introduce requests
- Quick example of getting data from the Github API
- Discuss Private APIs
- Extended example of Mining ESPN Fantasy Football Data by using the private API

7. Web Scraping (5 mins)
- Define web scraping
- Extended example of mining beer description data
- Discuss limitations of web scraping

## Additional Notes

## Additional Requirements
