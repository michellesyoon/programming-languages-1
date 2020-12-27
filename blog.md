# Blog    

Deadline: tba.

## Introduction

This course can only scratch the surface of so many topics in programming languages, ranging from very practical (which programming language is best suited for what type of application) to purely mathematical (algorithmic complexity theory, algebra, logic, category theory, proof theory, ...). The blog is an opportunity to dig a bit deeper in what interests you most.

Learning a new programming language is always a challenge, in particular if it is the first functional programming language you are going to learn. You only know that you understand something if you can explain it to somebody else. So a good way to start the blog is to write a Haskell tutorial for beginners.

For more detailed ideas and suggestions see below.

## Setting up a blog

The minimal way to set up a blog is as follows:

- Create a public github repository.
- Add a `README.md`.
- Make `.md` files for each blog entry. Link them from the README.

To learn markdown, have a look at this  [Markdown Guide](https://www.markdownguide.org/basic-syntax) and one of the many [cheat sheets](https://www.markdownguide.org/cheat-sheet). Markdown is easy. And it is what I use for this course, so you can also look at my sources. Btw, you can use all of html in markdown. It makes the writing more cumbersome, but also gives you additional options. 

Here are some tips:

- Link your blog entries from the README.
- Never paste naked urls into md, use `[name](url)`.
- Did yo spellcheck your blogs?
- Typeset code as code, not text.
- Add a list of references at the end of each blog.

Personally, I am more interested in content than in form, but form is important as well. Just ask yourself whether the form supports the understanding of the content or whether it distracts from what you want to achieve. For example, spelling mistakes are always distracting. And long paragraphs are almost always bad form. 

You can take my github repo for this course as a guideline for your blog, but I don't want to discourage more sophisticated design of a webpage (or better use of the English language).

## Writing Tips

The blog is not an English assignment, but I do remmend to read this classic and entertaining [article by Orwell](https://www.orwell.ru/library/essays/politics/english/e_polit). 
- To avoid what Orwell calls "this mixture of vagueness and sheer incompetence" is particularly important in technical writing. 
- "A scrupulous writer, in every sentence that he writes, will ask himself at least four questions, thus: What am I trying to say? What words will express it? What image or idiom will make it clearer? Is this image fresh enough to have an effect? And he will probably ask himself two more: Could I put it more shortly? Have I said anything that is avoidably ugly?" Perhaps metaphors play a lesser role in our kind of technical writing, but if you replace "image" above by "example", Orwell's remarks are again exactly to the point.
- Orwell recommends to "think wordlessly, and then, [...] describe the thing you have been visualising"   and "to put off using words as long as possible and get one's meaning as clear as one can through pictures" first. 



## Organisation

My expectation is that you write the blog like a diary, as you go through the course. Write it with beginning Haskellers in mind. 

**Drop me an email when you made a new entry.**

Your blog should 
- approximately/on average has one entry/page per week (**10 in total** should suffice);
- be organised by time or topic;
- make sense to readers who do not take this course ... don't talk from student to professor but rather from professional to professional;
- you can draw on all kind of resources, but always make your own examples, observations, conclusions;
- interleave narrative with code (all code must be tested and run, make sure the reader knows how to run your code);
- finish each blog with list of references and recommendations for further reading;
- ...

***I don't want to limit your creativity, so let me know if you have your own ideas.***


## General remarks on content

Make the blog interesting to your readers including myself. Do not only repeat material that is already in the lecture notes.  Explore on your own. If you write about material we have covered in the lectures, make your own examples and add your own angle. **Do not post answers to homework and assignments.**

For example, if you write a Haskell tutorial, here are some things I would like to learn from you:
- How do newcomers learn functional programming?
- Which external sources (videos, blogs, tutorials, etc) do you find most useful?
- How does Haskell compare to your favourite programming language? Give examples of the same algorithm written in your favourite language and in Haskell. What are the respectives strengths and weaknesses of the two programming paradigms?
- What are, in your opinion, the major stumbling blocks in learning Haskell?
- Are there any projects you implemented in Haskell that go beyond what we do in class? What did you learn from them? Can you explain your project in a way that the reader wants to run and/or recreate it?

## Grading Guidelines

- **D:** Demonstrates basic familiarity with Haskell.  
- **C:** Demonstrates adequate familiarity with Haskell. Develops own examples along the lines of the homework.
- **B:** Demonstrates good understanding of Haskell. Makes interesting observations that do not merely repeat points made in the lectures.  Develops material that goes beyond what has been treated in class. Can be recommended to a beginning Haskeller as a first introduction. Makes connections between the practical and theoretical parts of the course. 
- **A:** Demonstrates a very good understanding of Haskell. Makes interesting observations and contains material that goes significantly beyond what has been treated in class. Will be of substantial interest to a beginning Haskeller. Makes interesting connections between the practical and theoretical parts of the course. Typically would discuss some of the advanced features of Haskell such as type classes or monads and/or develop their own project (but there are many possibilities here ... get in touch to discuss more.)

Some further considerations:

- Spelling, typesetting, layout, and structure will also be taken into account for grading. Does the form support the understanding of (or does it distract from) the content? 
- Every blog should have something interesting to say and be built around a central idea. If a blog reads just like a lists of items without a connecting narrative something is missing.
- Another way to say what an "A" blog is: You would be proud to add it to your resume.

Again, if you have your own ideas, let me know. I am happy to adapt these guidelines if they do not fit what you have in mind.

## Ideas for the blog

These are just suggestions, explore on your own. 

Some items require more work than others. Feel free to expand interesting topics into a series of blog posts.

#### Haskell

-  Write a Haskell tutorial. Make your own examples that you think would help a beginning Haskeller to understand Haskell better.
- Benchmark the same algorithms in Python and Haskell. You can use [gnomon](https://github.com/paypal/gnomon) to measure the time that programs take to run. Evaluate your findings.
- Explain how to use docker to setup Haskell and bnfc. Make a dockerfile that we could use to run Haskell, bnfc and the assignments.
-  I collected some ideas for [Haskell projects](haskell-projects.md) you might want to try.
- Haskell and $\lambda$-calculus: 
  - Write the same program in both languages and compare.
  - Study Church numerals. Make examples. Implement Church numberals and run them in Haskell.
-  If you know C and have experience in programming with pointers, you will be interested to learn that all of this is still in Haskell, but hidden in the compiler. Study how the Haskell compiler makes working with lists efficient. (This is a big topic and would be worth a whole series of blog posts.)
- Haskell is lazy, which is interesting for programming with infinite data structures such as streams.
- Do one (or more) of the [exercises](https://hackmd.io/@alexhkurz/BJ23jmpIw) labelled "Optional (but interesting)". (Essential exercises are not suitable for the blog.)
- ...

#### Theory

- Why is lambda-calculus Turing complete?
- What is the halting problem? Why is it undecidable? What are other undecidable problem?
- What is combinatory logic? Is combinatory logic Turing complete? 
- Beta-reduction is an important computational mechanism. Explore how to efficiently implement it using de Bruin indices.
- Can we prove confluence automatically? What is the Knuth-Bendix algorithm?
- Not all terminating programs can be proved terminating with a termination measure that takes values in natural numbers. How can we go beyond this?
- Some modern programming languages such as [Dafny](https://hackmd.io/@alexhkurz/SJyBbDQjv) implement verification of termination and Hoare triples. Explore.
- [Reversible computing](https://hackmd.io/@alexhkurz/H1PIwnSqw).
- Interactive theorem provers (Isabelle, Coq, Agda, Lean, ...) are functional programming languages in which one can prove mathematical theorems. Explore.
- ...

#### General Programming Languages Topics

- Multi-paradigm languages:
  - Haskell is close to what one calls "pure functional programming" but there are also multi-paradigm languages such as OCaml and, more recently, Scala and Julia. You can pick Julia or Scala and write one or more blogs about how they integrate FP and OO. What are the benefits (apart from just having both FP and OO)?
  - In case you have an interest in logic programming (eg PROLOG), there is some interesting literature on building multi-paradigm languages that combine functional and logic programming. 

- ...

#### Interpreters

Improve the `LambdaNat5` interpreter. See also my suggestions for [extra credit](extra-credit.md). Some of these may be more difficult than others, get in touch before you spend a huge amount of time on this.
  - Efficiency:
    - binary numbers instead of successor numbers
    - call by value instead of call by name
    - better substitution/beta-reduction
    - call stack
    - ...
  - Usability
    - Booleans
    - error messages
    - binary numbers
    - pattern matching
    - ...

#### Other Topics

See also the Discussion Topics in the [README](README.md) ... and let me know if you have your own ideas ... the blog is a space where you can be creative ...
