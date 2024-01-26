---
layout: essay
type: essay
title: "How Do I Ask?: An overview of smart questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-25
published: true
labels:
  - Smart questions
  - Online forums
  - Stack Overflow
---

<img width="300px" class="rounded float-start pe-4" src="../img/how-do-i-ask.jpg">

# The Problem of Questions

An experience that is far too common in classrooms today is that of the vacuum-like silence that immediately fills the space after the teacher says "Any questions?" I have been on both ends of this, and it is not fun, especially when you can very clearly the confusion and uncertainty painted on the students' faces. There are so many questions that are waiting to be asked! Yet, students hold off on asking, usually because most of those questions are nascent, barely conceptualized feelings of confusion, but also because students may perceive their questions to be too "stupid." Now, in a classroom environment, I hold the belief that these "stupid" questions should be asked. After all, in person, such questions can be really funny! Subsequently, even if the answer is quite obvious or plain, it can encite further discussion and encourage those with "smart" questions to formalize their question's wording and actually ask.

This does not carry over to online forums for software engineering. Online, questions are often viewed in a vacuum and do not inspire a continuing discussion like they would in a classroom environment. Furthermore, the marketplace of questions is teeming with dumb questions that can either be solved with a good search on Google or are so incoherent or vague that it would take a miracle for an online stranger to be able to find out what is being asked. In effect, a question must be sold and packaged as a "smart" question in order to attract the interest of "consumers," or online experts, so that they can give you help. So how do we phrase our questions to be "smart?" What qualifies as a "stupid" question?

# The Dumb

The following example of a stupid question comes from [this Stack Overflow question](https://stackoverflow.com/questions/77882598/error-the-name-gridview1-does-not-exist-in-the-current-context). The question regards an issue the user is experiencing with C# and how he can use C# Web Forms to extract data from a mySQL database. It goes as follows:

```
I am learning how to retrieve data from mysql database using c# webforms

this is default.aspx.cs

* A lot of code *

and default.aspx file:

* Also a lot of code *

How to solve the error 'The name 'GridView1' does not exist in the current context'?

unfortunately after providing full detail I still cant post the question due to 'It looks like your post is mostly code; please add some more details.' so excuse me for including this paragraph
```

This question, even though I barely know anything about C# webforms and mySQL, was frustrating to look at. The user did not seem to conduct research on how to solve his question. They simply included the entirety of two of their source code files with no comments or anything to really guide the reader, and an error message. Their goal is stated, although may be perceived as too vague and general. In addition, their last paragraph is, by their admission, only there to fill space, and gives the reader no additional details on the problem. It seems to be a question asked in haste, and thus, is a "stupid" question.

# The Smart

The following example of a smart question comes from [this Stack Overflow question](https://stackoverflow.com/questions/77879103/blockingcollectiont-throws-unexpected-invalidoperationexception) regarding a user's inquiry about implementing a queue using a specific C# class. It goes as follows:

```

I was trying out BlockingCollection<T> (as a Queue) in .NET8 and sometimes I end up with the exception:

"System.InvalidOperationException: The collection argument is empty and has been marked as complete with regards to additions."

Code example:

    * lots of code *

IsCompleted states "Whether this collection has been marked as complete for adding and is empty."

So as long as CompleteAdding() has not been called Take() should be blocking and when CompleteAdding() has been called and the queue is empty, " !queue.IsCompleted " should return false.

What am I missing?

Any help would be very much appreciated.

Running in VS2022 17.8.5 on Windows 11.

```

This question is very neatly formatted, with no spelling errors and decent grammar. The user gives us details about their environment in case it contributed to the error, which given it is an occasional error, might be a factor. The code, which has been omitted here for brevity, is tidy and, while it could use more comments, is readable. They state their goal and intentions with this code, as well as some examples of intended behavior. Finally, they offer some courtesy at the end. While there is not too much evidence of previous searching up, the fact the question is so cleanly formatted makes me lean towards this being a "smart" question.

# Conclusion

Learning something is often a difficult journey with many bumps along the way. Questions are a key part of this journey, and if answered properly, will clear the way for progress. However, if a question is "stupid" and not worded properly, the answers given can be at best non-existent (as the people who know will not answer) and at worst derail one's journey. Thus, we should aspire to create smart questions, questions that we can sell to the knowledgable so that they can pay us and those in the future with knowledge. Yet, we should not hinder our curiosity and hold back a question even if it might be a little stupid. If we all got stuck on the question of "How should I ask this?," we would never ask any questions. And that silence would truly be deafening.
