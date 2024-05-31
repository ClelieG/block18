# Test Specs 

Prompt 1 Unit Test : multiplication function that returns the product of the two input numbers 
    -Expect multiply(3,4)to be equal to 12
    -Expect multiply(3,4)to be a number
    -Expect multiply(a,4)to be an error

Prompt 2 Unit Test: concatOdds takes two arrays of integers as arguments. It should return a single array that only contains the odd numbers, in ascending orderm from both of the arrays. 
    - Expect concatOdds([8,9,10],[-3,4,-1,1,9,-9,11,-11,12]) to be [-11,-9,-3,-1,1,9]
    -Expect concatOdds([22,23,37],[0003,5,13,13,14,25]) to be [0003,5,13,23,25,37]  
    - Expect concatOdds([1,4,2,4,6,7,],[2,3,1,6,7,8]) to be [1,3,7]


Prompt 3 Functional Test: shopping cart checkout feature that allows a user to check out as a guest (without an account), or as a logged-in user. They should be allowed to do either, but should be asked if they want to create an account or log in if they check out as a guest. 
    - When a user clicks "add to cart", they will be prompted with a pop-up to login, or continue shopping as a guest 
    - When a user clicks "login" they will be prompted to enter in existing account information, or create a new account. 
    - When user clicks "continue as guest" rather than logging in, a pop-up should display asking for an email address to send updated shopping discounts/new arrivals/coupons, or allow them to skip email input and still continue as guest. 
    - When user clicks "check out" they should be taken to a check out page with an itemized list of their shopping cart, and allow them the option to still proceed as a guest or login. 
    - When checking out as a logged in user, all mailing info should already be filled out for the user at checkout besides billing. 