# Why Are We Here?

## Learning to Judge, Not Just to Write

I came to this course with almost no programming experience. My background is mainly in user experience and digital product design, where I usually work with user research, interfaces, prototypes, and visual systems. At first, I had a simple question: if AI can already generate working code from a sentence, why should a designer like me still spend time learning programming?

After the first two weeks, my answer is that I am not learning programming to compete with AI at writing code. I am learning it so that I can turn design intentions into specifications, read what a program is actually doing, and judge whether the result is correct. I may write less code by hand in the future, but I still need enough programming knowledge to understand and direct the material I am working with.

## When “Working” Is Not the Same as “Correct”

One exercise in Week 2 made this difference very clear. We were given several Python programs that ran successfully but produced the wrong result. One calculated an average using the wrong number of values. Another created a 3 × 5 grid, but changing one row unexpectedly changed all three rows. A third produced eleven opacity steps when the brief asked for ten. None of these programs crashed. The computer was perfectly happy with them.

Before this exercise, I tended to think that if code ran without an error, it was probably correct. I now see that these are completely different questions. A program can be syntactically valid and still fail the specification.

This is especially important when working with AI-generated code. AI can produce something that looks convincing very quickly, but appearance and execution are not enough. Someone still has to ask: Does this actually meet the brief? What assumptions does the code make? What happens when I change something?

For me, this is similar to design critique. A polished interface can still have a bad user flow. A visually attractive prototype can still fail to solve the user's problem. Programming adds another layer of judgement: I need to be able to inspect the rules underneath the output.

## From Describing to Specifying

The Schotter exercise gave me another way to understand this. The visual idea is simple: a grid of squares gradually falls apart from order into disorder. But the brief does not stop at describing that visual feeling. It gives rules: the top row remains untouched, the early part stays relatively calm, the damage becomes stronger in the lower half, and each square stays within part of its original position.

That difference between describing and specifying is important for my design practice. I can tell an AI tool, “make a generative visual that feels chaotic,” but that does not tell it what should remain stable, what should change, or how much change is acceptable. To get a result I actually want, I need to translate an aesthetic intention into constraints that can be tested.

This is where I see programming becoming useful beyond simply making a prototype. It gives me a way to make design rules explicit. Instead of only saying what something should look like, I can describe relationships, conditions, limits, and behaviours. That makes my design thinking more precise.

## Code as a Design Material

I also found Dylan Beattie's *The Art of Code* useful because it presents programming as an expressive medium rather than only a technical tool. His examples of generative art and live coding made me think about code in a similar way to other design materials (Beattie, 2020). A designer does not need to manufacture every physical material from scratch to understand what it can do, but they do need to understand its properties and limitations.

I do not think AI makes this understanding unnecessary. If anything, it makes it more important. When a system writes code for me, I am no longer only choosing what the code should produce; I am also choosing what to accept, change, test, or reject. Without some understanding of the material, I can easily mistake a plausible output for a good one.

## Why I Am Here

I therefore do not expect this course to turn me into a professional programmer. I want something more directly connected to my practice: enough programming literacy to work critically with computational tools.

AI may eventually write most of the code I would otherwise write myself. I am willing to accept that possibility. What I do not want is to become a designer who can describe an idea to a machine but cannot tell whether the machine understood it.

For me, learning programming is about keeping that judgement. It lets me move from prompting to specifying, from simply looking at an output to reading the rules behind it, and from accepting generated code to questioning it.

If machines increasingly write the code, I think the important skill is not disappearing. It is changing from writing every instruction to understanding, testing, and directing what those instructions mean. That is why I am here.

## References

Beattie, D. (2020, February 26). *The art of code* [Video]. NDC Conferences. YouTube.
