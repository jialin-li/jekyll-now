---
layout: post
title: Week Two :3
---

**What did you do this past week?** 

This past week was the first full week of school and I've just been really busy with school work, TA work and interview prep. I set up the environment for OOP and started working on collatz. Setting up docker took much less time than I had expected, probably because I did it on OSX. However, learning how all the pieces fit together was not as smooth. I was pretty overwhelmed with all the tools that we need to use for this project, and didn't realize we need to do issue tracking on GitHub until I was almost done with the project. This project's workflow is very similar to the workflow at my past internship, especially Contiguous Integeration, pull request and test coverage. Dr. Downing spent two classes explaining how to approach the project, which helped a lot. The lazy cache was pretty easy to implement. Generating automated acceptance tests was also fun. I also looked into the makefile, changed some things and got a better understanding of how makefile works. A very "shocking" thing I learned this week is that you don't need to explicitly pass in the address of an int to another function; instead you can just make the function parameter expect an int address and pass in the actual int. When you call it, it all works out. Wow.

**What's in your way?**

Umm the reading takes me a long time, and sometimes I don't understand what the quiz is asking. In one of the quizzes last week, I forgot what max_cycle_length() does and got the question wrong due to misunderstanding. Also there are so many files to keep track of for the project, and I am a little worried about not turning in everything properly. The clang-format still is not working for me even after updating the makefile. Make format still gives an error message.

**What will you do next week?**

I am going to finish up with collatz, run my code against all the acceptance tests in the public test repo and create my pull request. I also need to polish up my code and add more comments if needed. My goal for this week is to contribute more on piazza and be more involved in the class. Also I would like to get out of my comfort zone and talk to new people in this class.

**Tip of The Week**

One thing I find very useful is scp. It is used for transferring files between different hosts. Ever since 439 I start working a lot more on the lab and have a lot of files stored in lab machine. And sometimes I would like to have a copy of my files on my laptop or transfer my resume to cs machines so it shows up on my cs webpage. The command 
```
scp -r user@your.server.example.com:/path/to/file/home/user/Desktop/
```
allows you to transfer files from remote server to local server. The -r means recursively copy the entire directory. And 
```
scp file.txt your_username@remotehost.edu:/some/remote/directory
``` 
allows you to transfer local files to remote server. You can also specify the port number by using`-P` flag with portnumber or transfer multiple files at the same time by replacing the file name with `\{file1, file2, file3\}`.
