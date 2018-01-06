# Reading list

<!-- TOC -->

- [TDD - Where did it all go wrong](#tdd---where-did-it-all-go-wrong)
- [Ultimate Go](#ultimate-go)
- [Go hook adaptor app](#go-hook-adaptor-app)
- [Go application structure](#go-application-structure)
- [Linux](#linux)
- [Random](#random)
- [Random Archive](#random-archive)

<!-- /TOC -->

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

## Ultimate Go

Video training series by William Kennedy

## Go hook adaptor app

### To Read

- [Some example custom functions](https://github.com/Masterminds/sprig)
- [Using templates](https://www.calhoun.io/using-functions-inside-go-templates/)
- [Mattermost hooks](https://docs.mattermost.com/developer/webhooks-incoming.html)

## Go application structure

### To Read

- https://npf.io/2016/10/reusable-commands/
- https://medium.com/@benbjohnson/standard-package-layout-7cdbc8391fc1
- https://medium.com/wtf-dial/wtf-dial-domain-model-9655cd523182

### Finished Reading

none

## Linux

- [Learn just enough Linux to got things done](https://alexpetralia.com/posts/2017/6/26/learning-linux-bash-to-get-things-done)

## Random

- [Netflix, What happens when you hit play](http://highscalability.com/blog/2017/12/11/netflix-what-happens-when-you-press-play.html)
- [Unconferences, how to prepare](http://unconference.net/unconferencing-how-to-prepare-to-attend-an-unconference/)
- [Introduction to logic programming with Prolog](https://www.matchilling.com/introduction-to-logic-programming-with-prolog/)
- [Getting started with go Matcha](https://gomatcha.io/guide/getting-started/)

## Random Archive

- [if aligned memory writes are atomic why do we need the sync atomic package](https://dave.cheney.net/2018/01/06/if-aligned-memory-writes-are-atomic-why-do-we-need-the-sync-atomic-package)
  - Interesting reminder about how and why we need read/write barriers.