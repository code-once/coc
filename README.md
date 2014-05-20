COC = code once compiler
========================
Porgrammers world is getting complexer every day.
Yet we just want to code once and reuse what we know.

This project will just collect different ideas which could be implemented in a
code once compiler. It might turn into a new compiler soon, however writing a
compiler is a lot of work.

There are some contradicting principles such as:
* being object orientated
* being functional
* being strict
* being lazy

Depending on the use case you need some aspects or some others.
My goal is to think about a compiler which knows all flavours (but not
necessarily at the same time!) - but allowing to reuse code (like Scala/Java).

Also I want to target many different platforms using advanced AST rewriting
for instance to adopt to continuation passing style, signaling error in
different ways depending on what fits the target language.

Thus this compiler will be about describing behaviour rather than code
compiling down to JS/C/Java/... whatever I need.

Languages such as "haxe" come close, but they still fail in some ways making it
very hard to write cross platform code.

Yes - this is kind of research project.

SUPPORT
=======
If you want this to turn into reality you can support this project by
watching/following/starring or donating. Just [contact me by mail](mailto:marco-oweber@gmx.de)
