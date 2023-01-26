# Language

_What is the name of the language? Link the name to its webpage
(if appropriate)._

[Lotus](https://github.com/lotus-ios/lotus)
# Domain

_Describe the language's domain in five words._

Animating entire layers in CoreAnimation

# Computational model

_We don't yet have a great definition of the term "computational model".
For now, try to come up with the clearest, most concise explanation of
what happens when a program in your DSL runs._

An animation begins playing in a viewport.

# DSL-ness

_Fowler writes about a spectrum of languages, from general-purpose languages to
"purely" domain-specific. Where does the DSL you chose fall on this spectrum,
and why?_

This language would fall close to purely domian specific because you can only use it for animating shapes in CoreAnimation.

# Internal or external?

_Is the language implemented as an internal or external DSL?
Justify your answer._

The language is implemented as an internal DSL because it only handles a specific domain, animating shapes, and adds on to the existing language for animating in CoreAnimation. 

# Host language

_What language(s) was (were) used to implement the DSL?_

Swift

# Benefits

_Identify one potential benefit of the DSL: how is a programmer's life made
easier by the existence of this language?_

The code is a lot easier to read and undertand compared to typing out everything in Swift. 

# Drawbacks

_Identify one potential drawback of the DSL: what does a programmer
lose by using this DSL instead of a general-purpose language?_

The documentation on this language is not fully complete, so it might be difficult to learn. The time to learn the new language might not be worth switching over to it. 
