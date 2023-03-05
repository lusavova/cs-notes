# Testing

Everything I learned about testing from Martin Fowler

Testing is an **essential part of software development** that helps ensure that the code being produced is reliable, performs well, and meets the needs of users.
However it is often overlooked or undervalued. Many developers view testing as a time-consuming and unnecessary chore, preferring to focus their efforts on writing new code or implementing new features. However, this approach can lead to significant problems down the line, such as various bugs, performance issues, or security vulnerabilities. In contrast, a robust testing strategy can help ensure that the software being produced is reliable, efficient, and secure, and can help prevent these types of issues from arising.

## Self-testing code

> Every object should be able to test itself - Dave Thomas

Self-testing code is a powerful and effective technique for improving code quality and reliability. It is a key part of Continuous Integration.
**By writing small, focused tests that isolate individual units of code and larger tests that test the interactions between different units, we can create code that is easier to debug, faster to change, and more reliable overall.**

We can think of self-testing code as **building a bug detector that can locate faults within the system.**
Writing self-testing code not only helps avoid bugs, but it also gives us the confidence to make changes to the system. When we work with old codebases that have not been properly tested, even a small change or bug fix can lead to more problems, slowing down the process of adding new features. 

![image](https://user-images.githubusercontent.com/33388710/222955683-3659dfa4-b40b-4155-a592-26811d0c7876.png)
This can make us afraid to make further changes, leading to a build-up of technical debt and making it harder to improve the system over time.
Running the test suite frequently can help detect defects soon after they are introduced, making them easier to pinpoint and resolve. So we should strive to write tests that are fast and repeatable, so that they can be run frequently without slowing down the development process.

> You have self-testing code when you can run a series of automated tests against the code base and be confident that, should the tests pass, your code is free of any substantial defects. - Martin Folwer

However, it's important to note that self-testing code is not a substitute for integration or user acceptance testing. While self-testing code catches issues early in the development process, integration testing ensures that the individual components of a system work together correctly, and user acceptance testing verifies that the system meets the needs of its intended users. Therefore, self-testing code should be complemented by these other types of testing to ensure that the system as a whole works as intended.

Finally the heart of self-testing code is building a where developers are naturally thinking about writing code and tests together!!!





