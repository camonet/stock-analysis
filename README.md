# stock-analysis (VBA Challenge)
## Overview of Project
The purpose of this project was to refactor existing stock analysis code to in order for it to run faster (i.e., more efficiently). 
## Results
Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
The following pictures show the stock performance 12 stocks in years 2017 and 2018. According to the table, 2017 saw significantly more positive stock growth than 2018. 

<img width="421" alt="Screen Shot 2022-04-30 at 6 59 56 PM" src="https://user-images.githubusercontent.com/99444856/166126559-1de527e2-4c8d-4f44-89da-098fff832319.png">

<img width="421" alt="Screen Shot 2022-04-30 at 7 00 11 PM" src="https://user-images.githubusercontent.com/99444856/166126564-c137fdf0-a1ae-4ea0-ab77-eec9181ccfd9.png">

With respect to refactoring, the edited code performed the same job much faster than the original code. In 2017 and 2018, the original code ran in 0.64 and 0.66 seconds, respectively. The refactored code ran in 0.10 and 0.09 seconds for 2017 and 2018, respectively. 

<img width="264" alt="Old code (2017)" src="https://user-images.githubusercontent.com/99444856/166126932-4c7a31fa-6b64-441e-a98e-fe4af8d8756f.png">

<img width="264" alt="Old code (2018)" src="https://user-images.githubusercontent.com/99444856/166126907-1936519a-ed36-4d89-b83e-b1fa4553e483.png">
                             


<img width="264" alt="VBA_Challenge_2017" src="https://user-images.githubusercontent.com/99444856/166126727-fead9f05-312c-4fb8-bd5d-8dd95c83434e.png">
<img width="264" alt="VBA_Challenge_2018" src="https://user-images.githubusercontent.com/99444856/166126728-771f1bdf-7d48-41fe-9b03-7732090d669d.png">

The reason for the increase in efficiently was due to the use of stragetic for loops and conditionals. 
The following is the old code: 
<img width="555" alt="Original Code " src="https://user-images.githubusercontent.com/99444856/166126666-9a1738b4-d7c8-46c6-a940-ad34300a270b.png">

And the new code: 
<img width="609" alt="Refactored Code (1)" src="https://user-images.githubusercontent.com/99444856/166126876-e87f6c39-4e14-4ea7-a472-a5801e8b26c4.png">
<img width="609" alt="Refactored Code (2)" src="https://user-images.githubusercontent.com/99444856/166126878-c90f4a11-a797-47d3-9d41-73246c6cce6f.png">


## Summary
### There is a detailed statement on the advantages and disadvantages of refactoring code in general (3 pt).
In general, the advantages of refactoring code make it more efficient for the comuputer to perform the desired task. Writing code that is inefficient may not make a huge difference for small data sets, but it can make a very large difference in performance when there are many data points to analyze. One marked disadvantage of refactoring code is that one can lose its readability when the code is made more efficient. 
### There is a detailed statement on the advantages and disadvantages of the original and refactored VBA script (3 pt).
The advantage of the original script is that it allowed for someone to easily understand the code at the expense of efficiency, whereas the refactored allowed for a faster analysis of the stocks at the expense of readability. However, if a coder is diligent at making comments about the code, then the disadvantages that come with refactoring code will be diminished. 

