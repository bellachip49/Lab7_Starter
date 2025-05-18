## Check your understanding:
1. Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.<br />
Within a Github action that runs whenever code is pushed <br />
Response: Github actions is one of the better choices here. Running automated tests via Github actions helps streamline the process of testing pushed code, and validates it before merging branches through pull requests. It also prevents buggy code from being merged if the code reviewer misses a critical bug. By having tests run on GitHub actions, it also allows for code to be run in the same environment instead of locally on someone's machine, which may yield different results depending on the environment.

2. Would you use an end to end test to check if a function is returning the correct output? (yes/no) <br />
Response: No, unit tests should be used instead.

3. What is the difference between navigation and snapshot mode?<br />
Response: Navigation mode is the default chosen mode. It also captures metrics like first contentful paint and time to interactive. This mode is mainly used for analyzing full page performance, user experience. Snapshot mode captures the current DOM state without a full page load and doesn't reload the page. It is mainly used for testing particular parts of a page, not in its entirety.

4. Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
    - One thing we can do is convert all png images to jpeg, as png images often have larger filesizes than jpg files. Over time, as more png images are added, it may slow down page load times.
    - Usage of colors could be better; yellow buttons against a white background doesn't have a lot of contrast, which can be an accessibility issue for people with colorblindness.
    - There needs to be some way to organize the items on the website, since certain kinds of items may be hard to look for by simply scrolling as more items are added to the website. One way would be sorting the items and putting them into sections based on the type of item.