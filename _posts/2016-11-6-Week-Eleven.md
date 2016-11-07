---
layout: post
title: Week Eleven :11
---

**What did I do this past week?** 

I turned in Darwin. :) My partner and I redesigned our Darwin project the night before it was due. It took us 2 hours to implement our new design, which was much shorter than expected! Thankfully everything worked out, but lessons learned, I will definitely confirm my design multiple times before diving into implementation next time. For our best creature, we first tried to make our best creature identical to rover's instructions, this gave us 24 best after 1000 turns. We then tried to manipulate with the random number by adding an extra if_random in our instruction set, and that alone made our best creature outnumbered all other creatures after 1000 turns. 48 to 2 :p Aside from the project, I learned about move and the scope of different type of variables this week. The swapping tricks for move are so clever! I hope to use them in my own code sometime. 

**What's in my way?**

Grading design doc... It's taking a lot longer than I've expected :( Hopefully I will be faster at it once I grade a few more. I also have a few more interviews to do this week. I am normally excited for interviews because they are fun, but now I am just exhausted. 

**What will I do next week?**

I will start on the game of life project with my partner, go to Dr. Downing's office hour and try to do my best on my interviews. I will also finish grading design docs and answer as many OS questions as I can on piazza :p 

**Tip of The Week**

Warning: The VM project is due this Friday, the lab will be pretty crowded throughout the week.
Tips on the vm project: 1. When changing load_segment to demand paging, don't forget to store the offset of the current file page. 2. When doing stack growth through system call, make sure to use the esp from the interrupt frame from syscall.c not from exception.c. 3. Don't forget synchronization for frame table and supplemental page table. Although supplemental page table is per process, when you implement eviction, you will need to update someone else's supplemental page table.
