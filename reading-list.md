# Reading list

<!-- TOC -->

- [Retrospectives](#retrospectives)
- [TDD - Where did it all go wrong](#tdd---where-did-it-all-go-wrong)
- [Go hook adaptor app](#go-hook-adaptor-app)
- [Learning Go](#learning-go)
- [To Read](#to-read)
- [Linux](#linux)
- [Random](#random)
- [Random Archive](#random-archive)

<!-- /TOC -->

## Retrospectives

Thinking about re-invigorating retrospectives and ensuring the time is well spent

### To Read

- [Luis Goncalves: Agile retrospectives](https://luis-goncalves.com/agile-retrospectives/)
- [Agile Retrospective Resource Wiki](http://retrospectivewiki.org/index.php?title=Agile_Retrospective_Resource_Wiki)
- [Akash: 1 useful tool or empty ceremony](http://www.akashb.com/blog/2012/05/06/agile-retrospectives-part-1-useful-tool-or-empty-ceremony/)
- [Akash: 2 The Prime Directive](http://www.akashb.com/blog/2012/05/13/agile-retrospectives-the-prime-directive/)
- [Akash: 3 The Safety Check](http://www.akashb.com/blog/2012/05/28/agile-retrospectives-the-safety-check/)
- [Akash: 4 The Action Items](http://www.akashb.com/blog/2012/06/26/agile-retrospectives-action-items/)
- [Akash: 5 The Facilitator](http://www.akashb.com/blog/2012/08/06/agile-retrospectives-the-facilitator/)
- [Creating Safety](http://www.funretrospectives.com/creating-safety/)
- [What to do when safety is low in a retrospective](https://www.benlinders.com/2016/what-to-do-when-safety-is-low-in-a-retrospective/)

### Reference

- [Author: akash](http://www.akashb.com/blog/author/akash/)

## TDD - Where did it all go wrong

Starting From Ian Coopers talk _TDD where did it all go wrong?_

### What did I learn?

Articles all re-emphasise what I already held to be true.

- test behaviours, not implementation
- Enforcing one test class file per production class is wrong
- A test class is testing **one** scenario
- **Unit** in **Unit testing** means _a test_ that runs in isolation to other tests.
- Do **not** fear deleting tests that provide no value or hold you back
- From Dan North's original article, the focus is on behaviour. Unfortunately there appears to be a desire to make JBehave too clever, when the original intent seems to have been to remove any reference to the word test.

Now to find some thoughts on why this is wrong.

### To read

- [TDD avoid testing internals](http://codebetter.com/iancooper/2011/10/06/avoid-testing-implementation-details-test-behaviours/)
- [Ken Beck. Test driven development by example](https://www.safaribooksonline.com/library/view/test-driven-development/0321146530/pr02.html)

### References

- [Video: TDD where did it all go wrong?](https://vimeo.com/68375232)
- [Review of ian cooper tdd where did it all go wrong](https://robdmoore.id.au/blog/2015/01/26/review-of-ian-cooper-tdd-where-did-it-all-go-wrong/)
- [Dan North. Original introduction to BDD](https://dannorth.net/introducing-bdd/)
- [My Unit Testing Epiphany](https://www.stevefenton.co.uk/2013/05/My-Unit-Testing-Epiphany/)
- [My Unit Testing Epiphany Continued](https://www.stevefenton.co.uk/2013/05/My-Unit-Testing-Epiphany-Continued/)
- [TDD where did I go wrong](https://frankcode.net/2014/07/01/tdd-where-did-i-go-wrong/)
- [Steve Sanderson, writing great unit tests](http://blog.stevensanderson.com/2009/08/24/writing-great-unit-tests-best-and-worst-practises/)
- [The Philosophy of Testing](https://www.codesimplicity.com/post/the-philosophy-of-testing/)
- [Dan North: Thoughts behind go's testing.T approach](https://dannorth.net/2016/09/03/scratching-a-junit-itch/)

## Go hook adaptor app

### To Read

- [Some example custom functions](https://github.com/Masterminds/sprig)
- [Using templates](https://www.calhoun.io/using-functions-inside-go-templates/)
- [Mattermost hooks](https://docs.mattermost.com/developer/webhooks-incoming.html)

## Learning Go

## To Read

- [Go AWS Lambda](https://aws.amazon.com/blogs/compute/announcing-go-support-for-aws-lambda/)
- https://npf.io/2016/10/reusable-commands/
- https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1
- https://medium.com/wtf-dial/wtf-dial-domain-model-9655cd523182

### References

- [Training series by William Kennedy](https://www.safaribooksonline.com/library/view/ultimate-go-programming/9780134757476/)
  - Covers more than how to type in a program in go. Whilst I don't agree with everything Bill suggests, watching the whole course (at x1.25) was worth the effort and Bill made me aware of many new topics.

## Linux

- [Learn just enough Linux to got things done](https://alexpetralia.com/posts/2017/6/26/learning-linux-bash-to-get-things-done)

## Random

- [Occam's Razor: How it works](https://science.howstuffworks.com/innovation/scientific-experiments/occams-razor.htm)
- [Occam's Razor: What Occam really said](https://boingboing.net/2013/02/11/what-ockham-really-said.html)
- [What does code readability mean?](http://typicalprogrammer.com/what-does-code-readability-mean)
- [Netflix, What happens when you hit play](http://highscalability.com/blog/2017/12/11/netflix-what-happens-when-you-press-play.html)
- [Unconferences, how to prepare](http://unconference.net/unconferencing-how-to-prepare-to-attend-an-unconference/)
- [Introduction to logic programming with Prolog](https://www.matchilling.com/introduction-to-logic-programming-with-prolog/)
- [Getting started with go Matcha](https://gomatcha.io/guide/getting-started/)
- [Luna data processing tool](http://www.luna-lang.org/)

## Random Archive

- [Dave Cheney: If aligned memory writes are atomic why do we need the sync atomic package](https://dave.cheney.net/2018/01/06/if-aligned-memory-writes-are-atomic-why-do-we-need-the-sync-atomic-package)
  - tl;dr; Force reading and/or writing through the various caches to main memory.
- [Occam's Razor: The art of software design](https://michaellant.com/2010/08/10/occams-razor-and-the-art-of-software-design/)
  - tl;dr; Ask why? Justify all the things, how do they contribute to the simplest solution.
  
