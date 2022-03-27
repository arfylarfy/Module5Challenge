# Module 5 Challenge

## Financial Analysis Tools
This application consists of 2 parts:

A financial planner for emergencies: The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.

A financial planner for retirement: This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

This is a python command-line interface application that uses the information from the Monte Carlo simulation to answer questions about the portfolio.


## Technologies
This project is written in python. The required libraries in order to use the application are os, requets, json, dotenv, alpaca_trade_api, MCforecastTools, pandas, and %matplotlib inline.

![Import libraries](https://github.com/arfylarfy/Module5Challenge/blob/main/Starter_Code/Images/Screen%20Shot%202022-03-27%20at%203.05.11%20PM.png)

## Examples

![graph](https://github.com/arfylarfy/Module5Challenge/blob/main/Starter_Code/Images/Screen%20Shot%202022-03-27%20at%203.06.48%20PM.png)

![simulations](https://github.com/arfylarfy/Module5Challenge/blob/main/Starter_Code/Images/Screen%20Shot%202022-03-27%20at%203.07.07%20PM.png)

![FinCumulReturn](https://github.com/arfylarfy/Module5Challenge/blob/main/Starter_Code/Images/Screen%20Shot%202022-03-27%20at%203.07.16%20PM.png)

![FinalCumulTraj](https://github.com/arfylarfy/Module5Challenge/blob/main/Starter_Code/Images/Screen%20Shot%202022-03-27%20at%203.14.32%20PM.png)

## Contributors

Aranda Furth, arandafurth@gmail.com

---

## License

Copyright 2022 Aranda Furth

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

