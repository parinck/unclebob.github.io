---
layout: post
title: Flipping the Bit
tags: ["Testing", "Craftsmanship"]
old_tags: ["TDD", "Professionalism", "Craftsmanship"]
---


There's a bit you need to flip in your head. It's just one bit. In this blog we'll call it "THE BIT". Some of you have already flipped THE BIT. The rest of you need to flip THE BIT as soon as possible.

Once you flip THE BIT your life will be easier, your code will be cleaner, you'll get done with software faster, your software will work better, and fuzzy bunnies will happily hop over hillsides overarched by double rainbows all the way!

Before I tell you what THE BIT is, let me show you an example of an article produced without the benefit of THE BIT being flipped. The article is [here](http://www.simple-talk.com/dotnet/.net-framework/unit-testing-myths-and-practices/), and was written by someone named Tom Fischer. As I write this blog, Fischer's article has been read eleven thousand times. That's eleven thousand people who've been influenced by the wrong polarity of THE BIT.

Fischer's article makes the point that unit testing isn't always necessary. He uses graphs and charts with clever little colorings to support his arguments. Those arguments are two-fold.

1.  Unit testing takes time and can delay projects causing them to lose money due to lost opportunity[1].
2.  Unit tests don't find all bugs because many bugs are *integration* bugs, not bugs in the unit-tested components.

Fischer goes on to say that unit tests are great and can solve lots of problems, etc, etc, blah, blah. But then he erases all those positive and friendly words by concluding with this:

> We can no longer rely on a general acceptance of the myth that unit testing is a universal panacea, but need to focus unit testing on aspects of development where it is most effective, and be prepared to actively justify its use.

Oh my goodness! We have to be prepared to *actively justify unit testing?* Be warned! The *Unit Test Compliance Squads* will be making the rounds soon. Anyone who cannot actively justify their unit tests will be duly punished! &lt;*samuri scowl*&gt;

Who's going to write unit tests if we have to *actively justify* their use? Who'd be fool enough to take that risk? So we can summarize Mr. Fischer's article with the following sentence: "Don't you dare write unit tests unless you KNOW, and can *actively justify*, that you have enough time."

So the question is: *Who's got enough time?* Who, out there, has schedules that are so forgiving that you can *actively justify* the risk of writing unit tests? Who out there is working in an environment where opportunity costs and time-to-market aren't an issue? Who out there has a cushy-dreamy-stress-free-unicorn-riding project in which you can safely absorb the terrible cost of unit tests? Answer: Unicorns and fuzzy bunnies. But no humans that I am aware of.

Therefore, the only real conclusion of Mr. Fischer's article is that nobody should ever write unit tests no matter how beneficial they might sometimes be, because the risk and cost is so great that you must *actively justify* their use. (Note, that there seems to be no need to actively justify their lack...)

Mr Fischer has not flipped THE BIT in his brain. He still thinks that unit tests take time. Apparently he thinks they take a *lot* of time. He still thinks that there are situations in which unit tests aren't helpful. He hasn't flipped THE BIT. What planet is he living on?

THE BIT
-------

What is THE BIT? THE BIT is the boolean variable within your subconscious that represents your belief that unit tests take time. I want you to flip that bit so that your belief changes. I want you to believe that *Test Driven Development saves time in every case and every situation without exception amen*.

Notice that I did not say: "Unit tests save time". I said: "TDD saves time". I think that's an important distinction. I don't want you believing that unit tests written after the fact are anywhere near as beneficial as the *discipline* of TDD.

Here's the test for THE BIT. You can have a friend ask you these questions. If you answer them as shown below, you'll know that THE BIT has been flipped:

1.  Given a task, will you finish faster using TDD?: *YES.*
2.  Are there any tasks that you can finish faster without using TDD?: *NO.*
3.  I understand that TDD might help in the long term, but what if the job is really short term? Would you still use TDD?: *Yes, because TDD is faster even in the shortest term.*
4.  What if the schedule is really tight and the boss is breathing down your neck, would you still use TDD?: *YES.*
5.  In every case?: *YES.*
6.  Is there any case where you would not use TDD: *NO.*
7.  What if you were on the Starship Enterprise and the warp coil was seconds away from an anti-matter explosion and all you needed to do was invert one IF statement to save the ship. Would you use TDD for *that*?: *Yes.*
8.  Why?: *Because I'd get done faster.*
9.  Even for just one IF statement?: *Yes, even for just one IF statement.*
10. Do you mean to tell me that there is no case, no case at all, in which you would not use TDD?: *Well, I might not use TDD if I needed the task to take a really long time to finish, and have lots of bugs. But other than that? No, no case at all.*
11. What about GUIs?: *Ah, GUIs![2]*

That's THE BIT. When you have flipped THE BIT in your head, then when your boss tells you to stop writing tests because you don't have time, you'll refuse and tell him that without TDD it will take you longer to get done -- and you'll believe it! The more the pressure is on, the more you'll rely on the TDD discipline.

How do you flip THE BIT? I can tell you how I flipped *my* BIT. I used TDD for a month or so; and my BIT flipped. That's all it took for me -- just doing it. Maybe that'll be enough for you.

[1] It seems to me that you can lose a lot of money by shipping code that doesn't work too, but -- oh well.

[2] We'll talk about GUIs in more detail later. The short answer is: *Yes*. The medium answer is: *Yes, for all the dynamics.*
