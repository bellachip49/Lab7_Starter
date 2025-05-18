## Check your understanding:
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.<br />
Within a Github action that runs whenever code is pushed <br />
Response: Github actions is one of the better choices here. Running automated tests via Github actions helps streamline the process of testing pushed code, and validates it before merging branches through pull requests. It also prevents buggy code from being merged if the code reviewer misses a critical bug. By having tests run on GitHub actions, it also allows for code to be run in the same environment instead of locally on someone's machine, which may yield different results depending on the environment.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no) <br />
Response: No, unit tests should be used instead.
