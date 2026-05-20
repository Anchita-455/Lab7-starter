1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.


Using GitHub Actions to run tests whenever code is pushed is a good choice because tests run automatically and developers do not have to remember to run them locally, as they may forget. Testing only after all development is finished is not ideal because a lot of code may have changed, making bugs harder to find and fix. Running tests regularly during development helps catch problems earlier and makes debugging easier.

2) Would you use an end to end test to check if a function is returning the correct output? 

No, because an end-to-end test checks how the entire application works together, not just whether one function returns the correct output. Since the function may interact with other parts of the application, it would be harder to determine whether a failure was caused by that specific function.

