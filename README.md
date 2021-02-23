[![Build status](https://travis-ci.org/fpinscala/fpinscala.svg?branch=master)](https://travis-ci.org/fpinscala/fpinscala) [![Join the chat at https://gitter.im/fpinscala/fpinscala](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/fpinscala/fpinscala?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) 

This repository contains exercises, hints, and answers for the book
[Functional Programming in Scala](http://manning.com/bjarnason/). Along
with the book itself, it's the closest you'll get to having your own
private functional programming tutor without actually having one.

Here's how to use this repository:

Each chapter in the book develops a fully working library of functions
and data types, built up through a series of exercises and example code
given in the book text. The shell of this working library and exercise
stubs live in
`exercises/src/main/scala/fpinscala/<chapter-description>`, where
`<chapter-description>` is a package name that corresponds to the
chapter title (see below). When you begin working on a chapter, we
recommend you open the exercise file(s) for that chapter, and when you
encounter exercises, implement them in the exercises file and make sure
they work.

If you get stuck on an exercise, let's say exercise 4 in the chapter,
you can find hints in `answerkey/<chapter-description>/04.hint.txt` (if
no hints are available for a problem, the file will just have a single
'-' as its contents) and the answer along with an explanation of the
answer and any variations in
`answerkey/<chapter-description>/04.answer.scala` or
`04.answer.markdown`. The finished Scala modules, with all answers for
each chapter live in
`answers/src/main/scala/fpinscala/<chapter-description>`. Please feel
free to submit pull requests for alternate answers, improved hints, and
so on, so we can make this repo the very best resource for people
working through the book.

Chapter descriptions:

* Chapter 2: **gettingstarted**
* Chapter 3: ~~datastructures~~
* Chapter 4: ~~errorhandling~~
* Chapter 5: ~~laziness~~
* Chapter 6: ~~state~~
* Chapter 7: ~~parallelism~~
* Chapter 8: ~~testing~~
* Chapter 9: ~~parsing~~
* Chapter 10: ~~monoids~~
* Chapter 11: ~~monads~~
* Chapter 12: ~~applicative~~
* Chapter 13: ~~iomonad~~
* Chapter 14: ~~localeffects~~
* Chapter 15: ~~streamingio~~

# Setup

This repository can be built using IDEA Ultimate with Scala plugin 
configured to use the *Update Channel: Nightly Builds*. The snippets
can then be run from the IDE.

# Scala 3 Compatibility

All `*.scala` files have been moved to `*.scala2` as some of them don't
compile using Scala 3. We will adjust the broken files as we go. See
chapter description above to see the current state of Scala 3 support.

All code in this repository is
[MIT-licensed](http://opensource.org/licenses/mit-license.php). See the
LICENSE file for details.

Have fun, and good luck! Also be sure to check out [the community
wiki](https://github.com/fpinscala/fpinscala/wiki) for the **chapter
notes**, links to more reading, and more.

_Paul and Rúnar_

