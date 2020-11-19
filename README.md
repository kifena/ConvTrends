# ConvoTrends
ConvoTrends is an application that analyzes text messages. With its help, users draw valuable insights from their online conversations and can see the trends and patters in them.

## Introduction
This document details the purpose, methodology, and application of data science within the ConvoTrends system. Section 2 outlines the business objective addressed by the data science work, and defines the scope of the effort. Section 3 describes the data collected and utilized during analysis. Sections 4, 5, and 6 detail the methodologies employed, why they were selected, and how they are used and tuned (Section 4), trained (Section 5), and tested (Section 6).

## Business Case
ConvoTrends is an application for analyzing online conversations and drawing insights from text messages. This project will bring interesting facts to the process of messaging: users will be able to see trends of their conversations with their close ones, as well as learn new things about their communication styles with different people in different circumstances. The users of our API will benefit from it by better understanding the most important part of their lives and online presence: their relationships with people. Success of our project can be defined by the following: establishment of a wide audience with a steady growth and trust from both the users and the companies. On the technical side, the project will be successful when it ensures total privacy for the users, is ethical and has a high accuracy (in terms of its “predictions” being close to those of human experts).
### Key User Stories
User 1: “I’ve been friends with person N for many years. Recently, we started to treat each other differently and I want to see what has happened. It would be great to see a graph of “friendliness” in our messages: when we were really close, and when we were distant. I would also want a professional to analyse all that info and give me personal recommendations on how to improve the situation.”
User 2: “I’m a curious person and I simply want to see what words I use most often, when I’ve most socially active, when I usually text people and so on”
User 3: “My speech doesn’t satisfy me and I want to improve my texting language and style. It’d be helpful to have my texting behaviors tracked and analysed: do I sound too formal? Do people have certain reactions to my messages that can be seen from their replies? Is there a bad word that I often use and should stop? Things like that. Personal recommendations from linguists or philologists or ethicists on how to improve my manners would be great.”
## Data
| Property | Description |
| ------ | ------ |
| Name | Dataset of SMS messages |
| Description | The dataset is comprised of 5171 unique SMS messages |
| Data Source | Kaggle, Leo Arruda |
| Point(s) of Contact | Leo Arruda, https://github.com/LeoArruda |
| Format | CSV file |
| Structure | 2 columns: message id, and the text of the SMS message; 5171 rows |
| Schema | SMS_id: Id, SMS: string; |
| Sample Data | Kaggle |
| Volume | 503.31 KB |

## Analytic Methodologies
This section details the methodologies proposed to be implemented during development. This section can either be organized by type of methodology or the user story that they address. 
### Sentiment analysis
#### Model Selection
Sentiment analysis would allow our application to determine reactions that the person who’s the user was chatting with, had to the user’s messages..

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
