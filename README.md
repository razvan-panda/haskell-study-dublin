# Haskell Study Group Dublin

## Guidelines

We will mainly work through [_Haskell Programming from First Principles_](https://gum.co/haskellbook/dublinmeetup) (aka the "Haskell Book from first principles") by Christopher Allen and Julie Moronuki but feel free to study through other alternatives like the free ones mentioned bellow. The only prerequisites for participating are a computer and your person. An open mind is also recommended. No prior experience with Haskell, functional programming, or coding in general is required.

To prepare for your first visit, please do the following:

- **Join the [FPChat](http://fpchat-invite.herokuapp.com/) Slack community.**
All announcements pertaining to this study group will be sent out via Meetup and Slack. On the FPChat Slack, look for the `#haskell-dublin-meetup` channel.

- ** Either [Purchase](https://gum.co/haskellbook/dublinmeetup) your own copy of the book Haskell Programming from first principles OR use one of the free alternatives mentioned bellow OR choose your own material to study**
Please read the guidelines about using the book in the GitHub repository before using the discount code coupon.
You will need your own copy on your own machine so you can work with the PDF and your terminal open side-by-side. This book was independently researched, written, and published by two Haskell developers working in their spare time to support education in functional programming. As a member of our strong and supportive community, we know you are too committed to the spirit of pure actions to "borrow" someone else's copy - so either purchase one or use a free alternative.

  Alternative free haskell books:
    - [Real World Haskell by Bryan O'Sullivan, Don Stewart, and John Goerzen](http://book.realworldhaskell.org/read/)
    - [Learn You a Haskell for Great Good! by Miran Lipovača](http://learnyouahaskell.com/chapters)

- **Install [Stack](https://docs.haskellstack.org/en/stable/README/), the Haskell project development tool.**
If you are familiar with package managers like npm, pip, and apt, Stack is similar. You needn't show up already an expert, but do at least [learn the basics](resources/haskell-stack-notes.md). If you want to know everything, though, you could watch [this video](https://www.youtube.com/watch?v=sRonIB8ZStw). The most important thing: whatever you do, _do not install the Haskell Platform_.

- **Set up a project environment for your practice code, and familiarize yourself with GHC and GHCi.**
You don't need to do much more than create a directory for your code and make sure you know how to run the GHC compiler on your source files and GHCi when you need a REPL. I like to keep separate subdirectories for the individual chapters, but you can do whatever you find most convenient. Do not expect WiFi to be available at meeting locations, though every effort will be made to ensure its availability.

### Expectations

Participants in the study group will be expected to model and reinforce a culture of accountability. This entails everyone abiding by the norms of a supportive and rigorous classroom environment. Each week, you should attempt to complete the following tasks:

- Do all the reading.
- Type in all the code.
- Attempt all the exercises.
- Meet with a study partner to discuss your work.
- Attend the group meeting.

These expectations are not meant to make your life miserable but to provide a framework for your success. If you actually want to learn Haskell, consistency is the key — as with anything else. Since we'll be learning Haskell together in this group, it is essential that you work through each chapter on your own first so that you come to each group meeting prepared, knowing what you need help with and what you understand well enough to teach others. If you get stuck on a problem, keep moving, but do not just skip the exercises entirely.

#### For the sake of emphasis: _do not skip the exercises!_

If you are a complete beginner to programming or for whatever reason have trouble installing Haskell on your computer, don't worry about it! Come to the study group, and we'll help you figure it out or just ask in Slack for help. Fortunately, you don't even need a computer to work through Chapter 1 — just pen, paper, and patience. So make sure you at least do that much, even if you require tech support.

### Conduct of code

By participating in this study group, you implicitly agree to conduct your coding as follows:

If you can not afford to purchase the Haskell Programming from first principles then use an alternative information source for the study at your own pace and ask for any help required during the meetups.

Each week, prior to the group meeting, you will complete the assigned reading and attempt to complete the coding exercises to the best of your ability. If you find yourself struggling with the exercises, you should seek help at the meetings, from your study partner, or online.

You will make every effort to attend the weekly group meetings. Space is limited, so if you cannot commit to attending regularly, do not sign up. If you cannot make it to a meeting, withdraw your RSVP as soon as possible.

In addition to the above, all study group participants are expected to make their best effort at being decent human beings. Participants whose behavior strays too far or too often beyond the reasonable boundaries of respect, kindness, and collegiality may be removed from the group at the discretion of the organizer.

### Format

We will work through chapters 1–18 of the Haskell Book over the course of 12 weeks, meeting for about 2 hours each week. We may extend the meeting schedule to cover subsequent chapters if there is enthusiasm for doing so.

You will have the opportunity to review your work and to discuss concepts and exercises that gave you difficulty when working through the book on your own.

You are encouraged to hew as closely to this regular, weekly schedule as you are able so as to maintain your momentum. That said, if life gets in the way, so be it: but do your best to catch up, and avoid skipping any material as each chapter builds on the last. We can always discuss exercises on Slack, but please refrain from posting your solutions publicly (including on GitHub).

### Signing up

All meetings will be announced on Meetup and Slack. If you cannot attend a meeting because it is full, please continue to work on your own, and come to a future meeting.

### Slides and other resources

See the [resources](resources) sub-directory in this repository for presentation slides, bonus exercises, and other materials used during study session meetings. If you have something good to add, please submit a pull request.

### Schedule

**Week 1. Introduction. Lambda calculus.**
- Haskell Book, Chapter 1

**Week 2. Getting started with Haskell.**
- Chapters 2 and 3

**Week 3. Basic datatypes.**
- Review chapters 2 and 3
- Chapters 4 and 5

**Week 4. Types and Typeclasses.**
- Review chapters 4 and 5
- Chapter 6

**Week 5. Functional patterns. Working with recursion.**
- Review chapter 6
- Chapters 7 and 8

**Week 6. Lists and folding lists.**
- Review chapters 7 and 8
- Chapters 9 and 10

**Week 7. Algebraic datatypes.**
- Review chapters 9 and 10
- Chapters 11 and 12

**Week 8. Midpoint review. Testing with QuickCheck.**
- Review chapters 2-12
- Read and complete Chapter 13 on your own
- Chapter 14

**Week 9. Monoid and Semigroup.**
- Chapter 15

**Week 10. Functor.**
- Review Chapter 15
- Chapter 16

**Week 11. Applicative.**
- Review chapter 16
- Chapter 17

**Week 12. Monad. How to apply structure to your code. Conclusion.**
- Review chapter 17
- Chapter 18
- Read Chapter 19 on your own
- General review and look ahead

Meeting days, times, and locations may vary from week to week depending on the availability of space.

If you can help with hosting future meetings, please contact me at razvan.panda@gmail.com

Past hosts:
* Workday
* Nitro
* Zalando
* Pivotal
* WhatClinic

For details of specific meetings, see the Meetup page.

This repository was adapted from [Haskell Study Startup](https://github.com/sjsyrek/haskell-study-startup). Thank you @sjsyrek!
