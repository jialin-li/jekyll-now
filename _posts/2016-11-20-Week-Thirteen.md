---
layout: post
title: Week Thirteen :13
---

**What did I do this past week?** 

My partner and I finshed Life this week! Thanks to Darwin, I felt a lot more comfortable designing the classes for Life with a no getters and setters approach. It felt easier compared to Darwin and we spent less time on it as well. One thing I learned from this project is that when writing unit tests, always delete/free resources before doing ASSERT(). We kept getting warnings on some of our unit tests, and then realized it was because there could be memory leaks if the assertion failed. So we had to modify our tests to store all the values and conditions we wanted to test in some variables, free the pointers and then do all the ASSERTs together. In class this week, we learned about static and dynamically bound methods, how are things different in Java and C++ and some interesting properties of inline methods. We also had two speakers from Spicework giving a talk on Wednesday. Overall this week has been going well. 

**What's in my way?**

Nothing really. I've gotten a lot of sleep this weekend, feels great now! 

**What will I do next week?**

I am going to work on a retreat recap video for my church, do my last algorithms homework, go home, eat a lot, and probably redo the filesys project! I've always wanted to improve my PintOS solution for vm and filesys, finally there's time! Excited to do a better version of filesys and help my students :)

**Tip of The Week**

I learned about [User-Mode Linux](http://user-mode-linux.sourceforge.net/) this week! It's basically a vm but only for Linux. You can run it as a native process on Linux and develop on it without worrying about crushing your actual kernel. An older version of the website stated that "UML compiles to native machine code that runs just like any other compiled application on the host. This makes it very much faster than portable virtualisation schemes that implement an entire hardware architecture in software. UML runs applications inside itself with normally at worst a 20% slowdown compared to the host system, which modern hardware and clever system design can render negligable in real terms." Hopefully I can work on a project similar to this over the summer :)

