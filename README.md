# Finalcial Analysis Tools   

  > Create a Financial Planner for Emergencies   
  Create a Financial Planner for Retirement   
---  

## Technologies  

  > Monte Carlo Simulation    
  Python pandas library   
  API, SDK with alpaca
---   

## Using process

  > use request library to get BTC information       
![pic01]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/01.jpg")    

  > use alpaca SDK get information of AGG and SPY    
![pic02]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/02.jpg")     

  > store the info in a list and make a dataFrame based on it for a pie chart    
![pic03]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/03.jpg")        
![pic04]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/04.jpg")   

  > use python if statements to check if members has enough money in the fund
```python
if total_portfolio > emergency_fund_value:
    print("Congratulations, members has enough money in this fund")
elif total_portfolio == emergency_fund_value:
    print("Congratulations, members reaches this important finacial goal")
else:
    print(f"You have ${total_portfolio - emergency_fund_value} missed.")
```

   > use Monte Carlo simulaters to predict    
![pic05]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/05.jpg")    
![pic06]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/06.jpg")    
![pic07]("https://github.com/liulujunjin-vivian/Module5/blob/main/Pics/07.jpg")    

---

## Conclusion
#### Question: Will weighting the portfolio more heavily to stocks allow the credit union members to retire after only 10 years?
  > Through the data of decreasing retire year from 30 to 10
  and with higher risk of weight stock more than bond
  We found that although the 95% ci upper remains the same, which is 6.86 of ten years vs 22.09 of thirty years
  however, the CI lower risk increases rapidly, which from 1.044 of 30 years to 0.64 of ten years
  Weighting the portfolio more heavily to stocks seems not allow the credit union members to retire after 10 years
  
  please note the simulator use random number, so the 95 ci lower and upper index may varies

 ---   

## Contributors
  > Vivian Liu    
    Liu Lujunjin   
---
## License

  > MIT License

Copyright (c) [2022] [Liu Lujunjin]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


	


