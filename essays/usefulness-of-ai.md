---
layout: essay
type: essay
title: "cAn I help you? On The Usefulness of Modern AI"
# All dates must be YYYY-MM-DD format!
date: 2024-04-30
published: true
labels:
  - Artificial Intelligence
  - Software Engineering
  - ChatGPT
---

<img width="300px" class="rounded float-start pe-4" src="../img/usefulness-of-ai.jpg">

### I. Introduction
In the past half-decade, AI has gone through a massive revolution in both capability and perception by the public. This is thanks to both the culmination of years of research in the field and the increasing proliferation of powerful AI processors via Nvidia's gaming GPUs. Subsequently, it's seen significant use in education, where students are using it for many writing-related tasks, sometimes allowed and many times not. For us software engineering students, it is particularly pertinent because of AI's promise in coding, and how quickly and accurately it can identify many of the constructs in nearly every programming language. For my part, that's the aspect of AI I've explored the most, along with image generation (mostly for fun). So, for software engineering in UH Manoa's ICS 314 class, how much did I use it?

### II. Personal Experience with AI:
I have used AI in class this semester in the following areas:

1. Experience WODs e.g. E18

I did not use ChatGPT for any experience WOD. For a majority of them, it felt like it was unnecessary to use ChatGPT as the material given was enough to figure out how to do each WOD. Even in situations where I might need to reference something else, I used Google first rather than consult ChatGPT.

2. In-class Practice WODs

I did not use ChatGPT for the majority of the in-class practice WODs. It just did not occur to me to use it; I was focused on comprehending the problem and the associated material and connecting the two. That sort of confusion when trying to do so is, I think, quite important.

3. In-class WODs

I never used ChatGPT for in-class WODs. The issue with ChatGPT is that, while it can provide useful insight as to how certain functions work, in WODs, you should not be trying to understand the content; you have to focus on implementation. That is a particular weakpoint of ChatGPT that is incredibly frustrating, and thus I would rather not use it for time-restricted activities.

4. Essays

Despite the convenience ChatGPT offers in generating essays, I prefer the challenge of crafting my own thoughts and arguments. Relying on this AI feels like bypassing the opportunity for personal growth and critical thinking. While it may save time, I value the process of wrestling with ideas and refining my writing skills independently.

In fact, that entire last paragraph was done using ChatGPT! I tend to write in a way that is similar to ChatGPT due to my use of more formal language, so if I were to use it, I could likely make it work. However, I find that relying on ChatGPT for writing to be both irritating, as you'd have to modify the output ChatGPT gives you to be more personal, and could degrade my writing skills. Given I sometimes write as a hobby, I would rather not do that.

5. Final project

The difficulty of creating the final project has necessitated me using ChatGPT at times; it has acted as essentially a more efficient search engine for specific functions and implementations of those functions. For example, I asked ChatGPT about how to require an attribute in a collection's schema to be an array of an object I defined. It was quite helpful in understanding small things like that. However, when I asked it for an implementation of a feature, it led me down a rabbit hole of errors and the program just stopping at points. After taking a break, it was easy to see the issue, but it took a while for me to figure it out. From that, I learned that ChatGPT is most useful when you have a fairly decent knowledge of what you want to do, but you had a brain fart or simply forgot something.

6. Learning a concept / tutorial

Inside of class, much like the experience WODs, I found that the material given was sufficient for learning each concept, so I did not use ChatGPT much.

7. Answering a question in class or in Discord

I did not use ChatGPT for answering in-class and Discord questions. I did not use the smart-questions channel in the ICS 314 discord that often, and when I try to answer questions in class, I usually enjoy discussing the answer, whether I do know or not, without referring to the material or ChatGPT.

8. Asking or answering a smart-question

Again, I did not use the smart-questions channel all that often other than to see what other people had issues with. Thus, I did not use ChatGPT for this particular use-case.

9. Coding example e.g. “give an example of using Underscore .pluck”

Using ChatGPT for this purpose has given me 50/50 results. The majority of the code ChatGPT spits out will be mostly sound, save for a few errors or needed adjustments if you want to implement in your program. However, there will be situations where the code it outputs is inherently wrong. One example is when I asked ChatGPT how to increment the count of a property in an object if it existed and add it to the array when it did not. The code ChatGPT gave me would do both no matter what, which the compiler immediately took issue with. Cases like this make me distrust ChatGPT for anything larger than a few lines.

10. Explaining code

This use-case never occurred to me, although I can see how this can be useful. My main issue with it, however, is that ChatGPT is prone to hallucinating things in math and thus code. Thus, I'd only sort of trust broad-stroke explanations of code from ChatGPT.

11. Writing code

As stated previously in sections 5 and 9, ChatGPT is very iffy on producing fundamentally sound code. Thus, I abstained completely from using ChatGPT to actually write things in my code. Whether Copilot or some other AI program would be more useful in this situation, I am not sure; I did not use them at all over the course of ICS 314.

12. Documenting code

To me, this use-case makes no sense. Code documentation should be done by the person who wrote the code, not by anyone else. While documentation does not contribute to the function of one's code, it's still important if someone else wants to review your code. Thus, letting a hallucination-prone AI do it for you might make someone else's life much worse.

13. Quality assurance

I personally did not use ChatGPT for this use-case. I found that ESLint and the other tools in the IDEs we used to be sufficient for catching errors. However, I have heard of people who utilized ChatGPT for pointing out errant semicolons and syntax at certain points. I can also think of situations where issues bigger than syntactic ones could be picked up ChatGPT or some other AI program.

14. Other uses in ICS 314 not listed above

I've explored using image generation tools to generate assets for the final website. Unfortunately, the free ones I have access to produce mediocre results and thus, without paying, I cannot make something that is passable for good art.


### III. Impact on Learning and Understanding:

I used AI minimally during my time in ICS 314, but I see much promise in its usage and it has already made some impact on my comprehension. Using ChatGPT provides a different view on various concepts, and feels more responsive/alive than the documentation of the particular tool I am using. Subsequently, it fulfills the role of having another person to discuss problems with. In its best moments, AI eases the learning journey a lot.

At its worst, however, using ChatGPT becomes a puzzle of its own, a "Where's Waldo" kind of game where Waldo is logical error. It can be frustrating, and such searches leave me questioning my own competency. I suppose such errors does challenge my brain and flexes my critical thinking skills, but nonetheless, it is painful to deal with. I still have to give credit to AI, however, as its removed some hours from my workload and solidified my knowledge.

### IV. Practical Applications:

One of the most interesting usages of language-focused AI models like ChatGPT is its application in procedural storytelling. "Suck Up!" is an early access game released late last year that leverages LLMs to create responsive character AI. The player acts as a vampire attempting to get into people's homes for their blood. Players speak into their mic, which is interpreted by the game, then entered as a prompt into the game's system. Each character has their own personality defined by the developer, but all of their interactions are generated. It is very funny, albeit still kind of suspect at times with how permissive some characters can be.

It's use-cases like that where I think AI is most interesting. Rather than simply replacing the workload of people, it can enable new experiences that would not be possible otherwise via the hands of a human. Via LLMs, we could make characters actually respond to us and grow with us in a way not determined by anyone other than you. In the future, I foresee LLMs becoming the core of a new genre of role-playing games, one with the limitless freedom afforded by traditional tabletop RPGs like D&D or Cyberpunk, but without the need for other people and which looks like a typical triple A title.

### V. Challenges and Opportunities:

Perhaps the biggest challenge associated with AI currently is its tendency to hallucinate things, and how stubborn it can be with pushing it as correct. This is one thing that ChatGPT has unfortunately inherited from humanity, and holds it back from being a do-it-all tool. Too often, it just makes up things and justifies its decisions with more made up things. Two other issues are more future-sighted, but still impact us today. Namely, the databases which the AIs are based on are only updated so often. This can leave them behind the curve occasionally, which in most cases is fine, but for some, it may leave ChatGPT unable to answer basic questions. Related to this, AI's other problem is the poisoning of its database. As AI becomes more prevalent, more of the internet becomes AI, and if we were to feed this content back into the AI, we could create a loop of infinite garbage output. It would be disastrous for AI.

At the same time, it is hard not to see AI's promise, particularly in education. Given proper tuning and utilization, AI could be used to customize the learning experience of a student according to how they best learn. In terms of software engineering, this could mean the difference between the AI providing a student more practice problems or practical project ideas or providing a student more lecture-type materials and documentation. Of course, it would also provide a helping hand at times and would have correct explanations and answers at the ready. Perhaps in the future, it could also break down the structure of a student's code into a visual diagram and make recommendations to make it more efficient via that diagram. Such an application might just be mostly sugar rather than meat, but it would still be quite nice.

### VI. Comparative Analysis:

In a traditional instruction format, before AI, students are reliant on their professor and TAs for actual learning. Although students are able to continue their learning on their own via books and internet resources, if they want their code or software checked, they would have to get someone else to check it. This would typically be the professor and TAs, but could also be someone online. However, analyzing someone else's code and project takes time, time which is not really spent on teaching/learning. With AI, this sort of interaction is reduced and students can more or less ask "someone" on their own time and they can get a response with seconds of asking the question. Thus, students can remain engaged and can spend more time learning and doing rather than asking questions and waiting for responses.

Knowledge retention and skill development, however, are at risk of degradation due to AI. In a traditional setting, students have to do all the work on their own. They will have to struggle and slam their head against their wall trying to solve a problem. I argue, however, that that part of the process is critical to learning. Without error, after all, do you really know everything about how to do something? If one becomes too reliant on AI, their skills in straight coding could be degraded, and they would forget concepts and syntax more easily. After all, they are not the ones using it; it is the AI who writes it for them.

### VII. Future Considerations:

If AI models avoid the issues related to data poisoning and are able to continue on the trajectory of growth they are on, they will become an important part of software engineering moving forward. Perhaps instead of writing code, students will instead learn how to model their software and how to shape in such a way that makes for more efficient, fool-proof software. This would require AI models much less prone to hallucinations, and it'd also need improvements in what exactly you can input into the model and how receptive it will be to the user's modified input. Given these and many more improvements, AI could become the code monkeys to students who are trained more as architects and designers rather than programmers, and possibly have some design skills as well.

### VIII. Conclusion:

The rise of AI has simultaneously intrigued and terrified me. But like with all things, such strong feelings are tempered by time and experience. My limited usage of AI has been defined by its limitations, its imagined solutions and its blinding naivety. Yet, in some moments, the light shines through the clouds and it becomes clear where the promise in AI is. It can light the way much quicker than any human can, and it can do in a manner more specific to the one who is asking. In the future, I believe that software engineering courses must include a section about AI, its flaws and its strengths, its whims and its developer-defined bounds. Then, students should be challenged to take the AI as far as they can, if they wish. See how far it takes them in creating software, see where they got blocked. In doing so, I hope future students will be able to see more than I can right now, and can perhaps make better suggestions. 