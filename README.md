# Blockchain Events Proposals
## About
If you are going to hold or know an **ONLINE** meet-up, conference, hackathon, or another event in the **BLOCKCHAIN** industry that can be helpful to developers, then you are welcome to create a **Proposal**. 

## General rules on how to write a Proposal: 
* It should be a markdown file;
* After creating it, you need to make a git pull request to the **master** branch;
* Then, it will take time to consider the application;
* Each proposal will have a status. It was made to create a convenient way for users to get know what happens with their proposal. The status is updated by pull requests. 

### Status types:
* **Proposed:** means that the application was just submitted;
* **Reviewed:** means that the application is reviewed by the developers;
* **Accepted**: the application is submitted and will be added on the site soon;
* **Rejected:** the application was rejected by developers (the rejection reason will be defined in the commit message);
* **InfoLack:** the developers need more information;
* **InforAdded:** the requested information is added by the proposer;
* **Published:** the event was added on the site. You can view it on http://88.218.28.126:4001/.

## Step-by-step example:
1. You create a git pull request and add the status **Proposed**;
1. Once the developers take it into consideration, they change the status from **Proposed** to **Reviewed**;
1. It may happen that some information is missed and the reason is not specified. In such cases, the developers change the status from **Reviewed** to **InfoLack**;
1. The person who created a proposal need to specify these points and change the status from **InfoLack** to **InfoAdded**;
1. The developers take it into consideration and change the status from **InfoAdded** to **Reviewed**;
1. If all is ok, the status will be changed to **Accepted**, and then to **Published**. The **Rejected** status can’t be changed again.

## The BEP template


| id  | status    | author | event_name                                  | event_type | start_date | end_date   | blockchain | topics                                                                                                                                                                                                                                                                                                          | dev_type | organizers                    | prize | price |
| --- | --------- | ------ | ------------------------------------------- | ---------- | ---------- | ---------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------------------------- | ----- | ----- |
|  <will be assigned by developers>    | Proposed | <github_username>  | <event name>  | <type of online event> | <date of event start> | <date of event end> | <blockchain name(s)>      | <list of topics> | <developer type>      | <who organize the event>| <does it has prizes> | <specify the price range> |

After you fill the table, provide us more details about the event.
#### Summary
Describe the event in several sentences.
#### Rounds and dates
Provide here a detailed description of the rounds, requirements, and dates the event has. 
#### Prizes Description
Describe the prizes in detail.
#### Prices
Write the ticket prices. Write Free if it is a free event.
#### URLs
Leave the link to the official site and social network pages.
#### Image URL
Link to the image that can be used as a cover image. Dimensions: 500 x 250 px

**Table Notes:**
1. Author: Github account
1. If the event has different rounds and starts dates, specify the first one in the table.
1. Events can be of different types: hackathons, conferences, meet-ups, round tables, discussions, etc. 
1. In topics, list all the topics that will be risen up during the event. 
1. In a dev_type row specify the level of developers the event is oriented to junior, experienced, middle, all. 
1. In prices and paid rows, write only true or false. 

**If the blockchain type and technologies stack do not play a big role, write Any. It also refers to a for_whom option.**
