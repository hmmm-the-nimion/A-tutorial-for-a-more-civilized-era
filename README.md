# A-tutorial-for-a-more-civilized-era
Nim tutorial written in diruptesque



# Nim Tutorial (Part I)

This document is a tutorial for the programming language Nim. Nim is fairly elegant, expressive and **very** fast, much like your sports car, if you had one. Not much is required in the way of parsing this document, the usual *klišé* of programming concepts: variables, types, statements, the modern atoms of machine expression. The rest is kept very basic as it is generally known that it's the gentle hand that stirs the dim candle.

Apparently, as a rule, this kind of document cannot qualify without an hello world example. A practical custom, from a forgotten era:

```nim
# This is not a comment
echo "Martha! Look what the cat dragged in..What is your name, boy? "
var name: string = readLine(stdin)
echo "...I'm.., ", name, "..."
```
Don't be fooled by the first line, that one is an actual comment in Nim. Programmers use comments, pieces of not executed lines of code, to clarify and document code. In alternative you can notify fellow peers about the deplorable state of your code.
Comments can be multiline, such as:
```nim
#[
I bet Martha was dead for years and the boy is actually his son
  #[
     Nah, it would be too basic..hey is this a nested comment inside your own comment?
  ]#
  Apparently so my man
]#
```
Echo from line two is the modern Nim rendition of the vestigial printline. It's function is to print strings to the standard output. Useful to check that your program is staying the intended course, a primitive debugger of sorts, but an efficient one. 
