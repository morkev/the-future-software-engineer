# The Future Software Engineer

Talk by Prof. Björn Regnell at Foo Café 12th anniversary, 2024 August 27 

**What every junior software developer must know to stay relevant in the AI-boosted era**

### About me
I do teaching and research in software engineering. Since 2015 I have been responsible for the first programming course for Master students in Computer Science at the Faculty of Engineering, LTH at Lund University. 

## Intro

The "Death of Programming", was recently predicted by Jensen Huang, the top boss at NVidia that make AI chips that heat up the plannet.

Is he right that AI will take the jobs of human coders? Should we stop teach coding to Software Engineers and instead teach Prompt Engineering and how to make a large language model write all the code for us, using Github Copilot, ChatGPT and similar tools that are already integrated in our development tools such as Microsoft VS Code and Jetbrains IntelliJ?

I don't think so!

We have heard the story before. Already in 1957 the ancient programming language Fortran was introduced in an academic paper entiteled "The FORTRAN Automatic Coding System". And the assembler programmers were complaining. Some cried that the compiler will take their work. Others claimed that it was better that humans write the machine code as the compiler is not smart enough to do the trickiest optimizations and the machine code will be of higher quality if humans write it.

What happened? Thanks to the compiler, software engineers could start coding at a higher abstraction level and get more done. Did assembler programmers loose their jobs? No, but the needed to learn new things. And they had really good use of their deep knowledge in machine coding when writing source code. We still today teach about machine programming as all well-educated software engineers need to understand what is actually happening at different abstraction levels.

The programming languages of the 60'ies provided abstraction mechisms that enabled the construction of much more complex software at a much higher productivity rate. And the story repeats itself on and on in the history of software engineering: powerful abstractions enable us to create more complex software, and when it gets too complex we need to create more powerful abstractions.   

What is bad with AI?

AI-code can have bugs anywhere, even if the code looks ok. The result from a large langugage model has an inherent stochastic element, due to the way it is constructed: the training process needs randomness to be effective at gradually adjusting the parameters of the underlying neural network. 

And we can't really **explain** exactly why the AI halucinated and gave us buggy code. 

What is good with AI?

Thanks to AI-boosted coding we can get relived of the nitty-gritty boilerplate coding and focus on the hard stuff in Software Engineering, and we can raise the level of abstraction. Finally the experienced coders can get more time for things like requirements engineering and architecture. 

Many coders today spend much of their time on nitty-gritty coding and non-interesting boilerplate. Compare to machine engineering building a factory producing things: do the machine engineers work all day by the conveyor belt doing repetivie tasks? No. But the sure need to understand what is going on in detail on the factory floor in order to be good at optimizing the flow of goods in the production. Many software engieers are stuck with low level coding of writing nitty-gritty bolierplate and crafting while loops. AI can help us here, and the more standard and bolierplaty the code is, the more reliable is AI-generated solutions.

## What junior software developers need to stay relevant?

* A deep and thurough education in computer science and engineering

* Knowledge about AI: both trained AI and symbolic AI.
* Understand the limitations of trained AI: bias, over-training, hallucination, ... 
* Use symbolic AI and "normal" code to check and balance trained AI code both statically and at runtime.
* Always set aside resources for human inspectio of AI-generated code.

Software Engineering topics that are even more important in th AI-boosted era:
* Software Inspection
* Requirements Engineering
* Software Architecture
* High-level, safe programming languages with powerful abstractions and advanced type system that enables strong static checks

In 2016 we started to use Scala as the first programming language at LTH for our CS programs, due to its simple syntax and powerful type system that help you find bugs already at compile time.  

## Outro
