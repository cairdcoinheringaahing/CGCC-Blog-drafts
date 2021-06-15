## Welcome to the first CGCC Blog post!

After [7 years](https://codegolf.meta.stackexchange.com/questions/1446/code-golf-blog-phase-1-raise-the-idea-on-the-meta-site), and three attempts, we've finally started a site blog, for posts and topics that the community here on CGCC is likely to find interesting. If you'd like to suggest topics, or would like to write a post about something specific, feel free to head over to our [ideas thread](https://codegolf.meta.stackexchange.com/questions/22070/what-should-we-write-about-on-our-blog) and write up a suggestion!

Intially, the idea for a blog came about when Stack Exchange was promoting [BlogOverflow](https://stackoverflow.blog/2011/06/23/blog-overflow/) back in 2014. Unfortunately, the idea ["sort of just... stopped"](https://chat.stackexchange.com/transcript/message/15461516#15461516) and never came to fruition. 4 years ago, [BlogOverflow stopped](https://meta.stackexchange.com/questions/291741/we-will-no-longer-be-hosting-blog-overflow), right as there was [renewed interest](https://chat.stackexchange.com/transcript/240?m=32929735#32929735) in having one, so we moved [off-site](https://medium.com/code-golf) for a while, before stagnating again. Finally, we decided to give it another shot, which is why you're reading this now!

If you'd like to see all the blog posts, check out the [meta-tag:blog] tag - all the posts are collected there, and each post has that tag. If you'd like to check out our [drafting and discussion room](https://chat.stackexchange.com/rooms/123200/cgcc-blog-chat), feel free to drop by and ask any questions you have. For our very first post, we've decided to write about the basics of language design and development, a topic relevant to a lof of CGCC users who have decided to create their own programming languages. Additionally, read to the end to find the first of our recurring sections on underappreciated answers and rarely used but interesting esoteric languages.

Enjoy!

---

Banning golfing languages has been an idea since the [creation of the site], back when "golfing language" meant the clunky, outdated mess that is [Golfscript] and the general-purpose-but-short languages [J] and [APL]. The general idea behind the ban is that verbose languages such as [Java] are unable to compete with languages specially designed for golfing, so, in order to level the playing field, various different measures (handicaps, bans, language-specific competitions etc.) have been suggested.

So, are golfing languages good for the site?

## Yes!

In general, I disagree with these measures. [Code Golf.SE] has a principle of "Answers don't compete with all other answers, they compete with other answers *in the same language*". For example, a Java submission is only ever trying to beat the other Java submissions, rather than the [Jelly] answers. This is a good compromise of a policy, and I personally prefer it much more than sites that only allow specific languages. However, it can also feel a bit cheap or hand-wavy.

The thing I most enjoy about golfing languages is that they force you to think in completely different ways to regular languages. Their vast builtin libraries completely trivialise trivial problems - as they should. People complain that having a builtin to do something (for example, a builtin to calcualte the dot product of two arrays) trivialises that task. That it isn't "real coding" to just copy-paste the `ḋ` character instead of having to actually write your own method. However, I wholeheartedly believe that if a task can be trivialised in a golfing language, it's a trivial task in *any* language.

Golfing languages are interesting when the challenge is interesting. Generally speaking, the more interesting a challenge is, the more interesting the golfing language answer will be, because the approaches are going to be completely different. Using a golfing language allows you to abstract away a task until you can distil it into its core principles. And, often, this results in a trivial answer in a golfing language, because the core of the challenge is trivial, but this can only be realised through the level of abstraction available in golfing languages. For example, consider [this] Jelly answer to a challenge about the [Padovan sequence]. This sequence is similar to the Fibonacci sequence, and so most practical languages use this approach. However, this style of recursion is not always golfy in golfing languages, so it requires a fresh take and a new way to understand the task in order to create a competitive solution.

This is, in my opinion, the biggest argument for golfing languages. The obvious solution may not always be the shortest in every language, and by expanding the ways one can approach a problem (via expanding the builtins available), golfing languages are able to find more creative ways to answer. That's not to say that practical languages can't be interesting, but that the approaches in practical languages are limited by their builtin set.

---

[creation of the site]: https://codegolf.meta.stackexchange.com/q/286/66833
[Golfscript]: http://www.golfscript.com/golfscript/
[J]: https://www.jsoftware.com/#/
[APL]: https://aplwiki.com/wiki/
[Java]: https://www.java.com/en/
[Code Golf.SE]: https://codegolf.stackexchange.com/
[Jelly]: https://github.com/DennisMitchell/jelly
[this]: https://codegolf.stackexchange.com/a/182825/66833
[Padovan sequence]: https://en.wikipedia.org/wiki/Padovan_sequence

## No!

Javascript, Python, and Jelly are the top three languages on CGCC. If you pick a random challenge from the last few years, chances are you'll see all three of them. One of these languages stands out. It's far golfier, but also far more disliked.

Those who have been on the site for a while will know that answers (officially) compete only with other answers in the same language. That unfortunately isn't immediately obvious to new users. Posting a 200 byte Python answer when there's 10 bytes of strange unicode in first place is discouraging. Why bother, when you don't know any of the languages that are consistently at the top?

Golfing languages are also designed for one thing: golfing. In JS or Python, you'd have to balance the byte counts of potentially dozens of approaches to a part of a problem. You would need to take into account how changing the syntax in one place affects it in others. In Jelly or 05AB1E, many answers are just a few built-ins strung together.

Entire classes of challenges can be completely trivialized by golfing languages. Prime-related challenges, for example. While it costs you 30-40 bytes for a primality check in most practical languages, a golfing language can do that in a single byte. You could argue that these challenges are already trivial if they could be solved in a few bytes in a golfing language, but it could also be that golfing languages make a larger number of challenges count as trivial.

Overall, golfing languages can be discouraging to new users, and trivialize many problems.
