# Dmoney_API_Automation_Newman

Dmoney is a demo financial project that supports fake transaction of money. In this project I have automated the Dmoney API using postman and newman. I have generated report using Newman and attached here.

## Positive and Negative case are Created for Follwing Scenraio
  * Admin does login to system
  * Admin creates an agent and random 2 customers
  * Deposit some money from SYSTEM account to the agent
  * Agent deposit to any of 1 customer
  * The customer checks balance
  * Then withdraw money from the agent
  * And send money to the other customer
  * Then the other customer will check statement
  * Do payment to merchant
  * Then he checks balance and statement
  * The merchant also checks balance

## How to run this project
Clone this project. Then run the follwing commands
  * npm i
  * npm run report.js

## Tools Used
  * Postman
  * Newman

## Postman documentation:
  https://documenter.getpostman.com/view/27529982/2s9YC7Rqth

## Newman Report:
![postman](https://github.com/siratulmustakim/Dmoney_API_Automation_Newman/assets/46200508/29e69164-b8bd-4cb0-a1c9-56f8674d26f7)

