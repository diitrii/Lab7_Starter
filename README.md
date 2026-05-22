1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
    I would put them in a GitHub action that runs whenever code is pushed. Everytime I push to GitHub, I'm saving the data to my main project, meaning that I am going to test to see if it works properly. If you have the automation set to run whenever code is pushed, then you will be able to test your code at every save point. 
2. Would you use an end to end test to check if a function is returning the correct output?
    No, you can just test the function by itself, as E2E is a very resource-intensive test that would not be required for a single function.
3. What is the difference between navigation and snapshot mode?
    Difference between navigation and snapshot mode is that navigation mode analyzes a page right after it loads, while snapshot mode analyzes a page in its current state.
4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
   Three things to improve the CSE 110 shop site:
    1. Using efficient cache lifetimes to speed up repeat visits to the page.
    2. Avoiding chaining critical requests
    3. Defer or inline render-blocking requests






