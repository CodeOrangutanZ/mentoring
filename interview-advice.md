# Interview advice for new software developers
This is mostly advice for new university and bootcamp graduates, though there are a couple of tips in here useful to more experienced engineers too.

The basic principles are:
1. Do more than the average.
2. Learn how to learn.
3. Take responsibility for your own professional development.
4. Code as a hobby and have something to show off.
5. Do your homework on the company.
6. Become fluent in coding.
7. Treat finding a job as a sales problem. 
8. Prepare to solve problems on a whiteboard.

## How to stand out to an employer
### 1. Do more than the average
> "To get better than average results, put in better than average effort." - De Wet Blomerus, [What I learned from applying for 107 jobs](https://www.youtube.com/watch?v=ybLA79IdEdY)
* This advice is the cornerstone of what it takes to stand out to an employer.

### 2. Learn how to learn
* The only constant in software engineering is change, and that means you need to get really good at learning.
* I recommend the following course since it's based on the neuroscience of learning, and debunks a lot of learnin myths. It also shows you how to use brain states to solve difficult problems more effectively:
    * Course: [Learning How To Learn by Barbara Oakley and Terency Sejnowski](https://www.coursera.org/learn/learning-how-to-learn)
        * Coursera lets you "audit" a course for free for a limited amount of time, so sign up, audit the course, and download all the videos while you have access.
        * If you find the course useful, consider buying access and doing all the quizes and assignments - it will help you learn!
    * Book: [A Mind For Numbers by Barbara Oakley](https://www.goodreads.com/book/show/18693655-a-mind-for-numbers)
        * The companion book to the course, covers the same material.

### 3. Take responsibility for your own professional development
* If you are lucky, your employer 
    * Develops a learning plan for you
    * Invests in your professional development
    * Wants you to leave as a better engineer than when you arrived
* If you're not lucky, they just want you to be a code factory.
* Don't depend on luck, make your own luck. Take responsibility, and do it yourself.
* Employers appreciate people who work to improve themselves.
* **Make your own learning plan**
    * Have a plan for what you want to learn next, and why.
    * Once you understand basic programming, try learning some computer science. I compiled a list of [open computer science resources](https://github.com/CodeOrangutanZ/open-computer-science/blob/master/README.md), but there are plenty other resources out there.
* **Invest in your own professional development**
    * I recommend joining the [Association of Computing Machinery](http://acm.org) as a professional member as soon as you are able.
    * They have a great [code of ethics](https://www.acm.org/code-of-ethics), and a very nice [learning center](https://learning.acm.org/about).
        * The learning center provides full access to the O'Reilly platform, which has about 50k computing books, and about 5k video courses.
        * You only need a Basic Online Membership to gain these benefits.
    * The ACM also has [special rates for developing countries](https://www.acm.org/membership/special-member-rates-developing-countries).

### 4. Code as a hobby and have something to show off
* Employers will often ask what you do for fun, or in your spare time
* This is sometimes a filter question meant to determine if you **code as a hobby**
* Prepare for this question by having something to show off.
* It should be something that involves code.
* Make it interesting, cool or fun, even if it's silly.
* Have it ready to show off.

### 5. Do your homework on the company
* It is always impressive when a candidate has good questions to ask about the company they are interviewing at.
* Find good questions to ask.
    * Read articles about them.
    * Research their business model.
    * Reach out to people who work there who you have connections to.
    * Check Glassdoor. 

## How to interview

### 6. Become fluent in coding
* Practice red, green, refactor
    * Red - Write the smallest possible test that fails.
    * Green - Write just enough code to make the tests pass.
    * Refactor - Clean up the code, and check the tests still pass.
    * Repeat until done.
* Practice ping pong coding (for two people)
    * A makes it Red - writes a small test that fails.
    * B makes it Green - writes just enough code to make the tests pass.
    * B Refactors - cleans up and checks the tests still pass.
    * B makes it Red - writes a small test that fails.
    * A makes it Green - writes jus enough code to make the tests pass.
    * A Refactors - cleans up and checks the tests still pass.
    * Repeat until done.
* Practice on code challenge sites.
    * binarysearch.com
    * Exercism
    * LeetCode
    * HackerRank

### 7. Treat finding a job as a sales problem
* Sales works on a funnel principle.
    * Fill the funnel by making lots of companies aware of you.
    * Not all companies will be interested in interviewing you.
    * Fewer will want to make you an offer.
    * Only one offer can be accepted.
* The basic idea is that at every stage, some prospects will drop off.
* So to get good offers, you need to fill the top of the funnel with lots of applications.
* Don't take rejections personally, just keep applying.

### 8. Prepare to solve problems on a whiteboard
* **Bring your own whiteboard markers**. Their markers might be dry. - [fisken_ai](https://www.twitch.tv/fisken_ai/about)
* **Ask if you can use a laptop.** Many places allow you to use your own laptop, and it's a lot faster to type (and more readable) than to write. 
* **Ask if you can use a code editor.** It might be allowed, in which case you get nice formatting, autocomplete and can test your code.
* **Solve the problem manually first.** 
    * Write out the inputs.
    * Simulate the computer by solving the problem step by step, writing the outputs as you go.
    * Think through the algorithm, and do it out loud.
    * Then write code.
    * Check that you haven't missed any edge cases.
        * What if the input is empty?
        * Is there valid input that breaks your algorithm?
* **Discuss time and space complexity.** You should predict how good your algorithm is by analyzing time and memory usage with Big O. Learn what it is, and practice using it.
* **Start simple, then refine.**
    * Start with a simple, but obviously correct algorithm.
        * This may be a brute force algorithm, or may use language libraries.
    * Improve on your initial algorithm.
        * At the very least, think about whether you can improve the algorithm.
    * Discuss different approaches.
        * If you have multiple options, ask if you should optimize for time or space.
* **Be prepared for the interviewer to change the problem.**
    * Often this means falling back to a simpler algorithm, or changing to another algorithm that optimizes for something different.
* **Think about whether the algorithm can be distributed.**
    * If you had multiple computers, could you divide the problem into smaller parts, solve them in isolation, then recombine the results?
    * This is good to think about because it's a common modification made to questions.
