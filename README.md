# Things You Should Never Do, Part I

## The Article

[**Things You Should Never Do, Part I**](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/) by *Joel Spolsky* (Joel on Software, April 2000)

## Why I Find It Interesting

Spolsky argues that the worst strategic mistake a software company can make is to **throw away working code and rewrite it from scratch**. His main example is Netscape, which spent roughly three years rewriting its browser while competitors took over the market. What stuck with me is his point that old, "ugly" code isn't really ugly. Every strange-looking line is usually a bug fix for some real-world edge case that someone found the hard way. When you rewrite, you throw away all of that hard-earned knowledge and have to rediscover it.

The article is over two decades old, but it still feels relevant. Developers (myself included) tend to think *"it's harder to read code than to write it, so I'll just write it again."* Spolsky shows why that instinct is dangerous. Instead of starting over, he recommends **incremental refactoring**: improving the architecture, efficiency, or readability of an existing codebase piece by piece. This connects directly to agile practices like continuous refactoring and small, frequent changes, and to tools like git that make incremental change safe and reversible.

> "The idea that new code is better than old is patently absurd. Old code has been *used*. It has been *tested*."

## Comment by Estifanos-Wassie

Great choice of article! I actually picked the same one for my own README, which shows how well it has held up over time. I especially agree with your point that "ugly" old code usually contains hidden bug fixes for real-world problems. I also like how you connected Spolsky's advice to agile practices and to git: small, frequent commits are a practical way to follow his recommendation of improving code step by step instead of rewriting it from scratch.
## comment
Interesting
