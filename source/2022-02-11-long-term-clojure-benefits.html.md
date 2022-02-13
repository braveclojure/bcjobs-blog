NOTE: this is a draft of a blog post for https://jobs-blog.braveclojure.com/. If you have suggestions for edits or would like your company included, please email me, [daniel@braveclojure.com](mailto:daniel@braveclojure.com).

# Learning Clojure yields surprising long-term benefits. These companies are hiring and will train you.

Learning any programming language requires a significant investment in time and resources. Of all the languages I&rsquo;ve gained proficiency in, Clojure has by far yielded the largest benefits for my life. Some of these benefits have been surprising and have only become evident with time. I want to share these less-obvious benefits because they&rsquo;ve had such a positive impact on me, and I want other devs to benefit, too.


## Clojure&rsquo;s stability can improve your lifestyle

Clojure&rsquo;s core team is committed to the language&rsquo;s stability over time so that code you wrote years ago will almost always work with the latest version of Clojure. Most other languages, by unfortunate contrast, don&rsquo;t have this dedication to stability. Instead, they&rsquo;re fairly laissez-faire about introducing breaking changes across versions, and they&rsquo;ll introduce new syntax with gusto.

This kind of churn in the core language imposes an overhead cost every time you sit down to do some programming. Say you want to spend some time hacking on a side project that uses the language `blub-1.0` but you want to use a library built for `blub-1.1`. You are in for a night of pain and horror. Your stomach is probably turning just thinking of it.

Now let&rsquo;s play this scenario out over time. Let&rsquo;s say that you generally have 30 minutes a night, two nights a week, to work on a side project. You run into a &ldquo;language overhead&rdquo; issue like the one above. Solving this kind of problem is a little chaotic, meaning it&rsquo;s hard to pick up where you left off between programming sessions. If you don&rsquo;t solve it the first night, you&rsquo;ll be retreading a lot of the same ground the next night. Heaven help you if Life Happens and you can&rsquo;t pick up your project for a couple weeks. It&rsquo;s hard to make actual progress.

What does this have to do with your lifestyle? I&rsquo;ll use this job board as an example. I recently re-built and re-launched this job board, and since then revenue has *quadrupled* (!!!). This has provided more income, which obviously helps on the financial end. But what&rsquo;s surprising and interesting is that Clojure&rsquo;s stability has allowed me to consistently make meaningful progress on my passion projects while *also* having time time for everything else I care about: making art, spending time with loved ones, and being involved in my local community. I don&rsquo;t have to work as much to get good results, because I&rsquo;m not fighting with the overhead costs imposed by the language.

Building this business at a sustainable pace, without sacrificing other parts of my life, has been huge for me, and it&rsquo;s possible in large part because I get to focus on actually *building* and not on traversing the seven circles of dependency hell or figuring out what some new glyph like `...` is supposed to mean.

The job board&rsquo;s core stack is one I&rsquo;ve been able to slowly grow over more than five years as I&rsquo;ve worked on various side projects. The fact that I can figure something out and it&rsquo;s still useful to me more than half a decade later is the definition of a good investment.

There&rsquo;s another, even less obvious way that Clojure&rsquo;s stability can improve your lifestyle: it reduces stress in your life. The quality of your life is the quality of your day-to-day experience, and if a significant portion of that involves meaningless struggle with your programming language, well it&rsquo;s hard to not end up feeling kinda lousy. And in this economy??

I realize I&rsquo;m probably giving off strong &ldquo;wow this guy is straight up mainlining the kool-aid&rdquo; vibes here. Clojure, ultimately, is just a tool, right? Yes. And if we&rsquo;re going to talk about building a satisfying and rewarding life, we need to talk about tools, and Clojure is an exceedingly good one.


<a id="org52ef52d"></a>

## Clojure is a great portal to other programming domains

Clojure has provided a gateway for me to learn more programming techniques and concepts, including:

-   [Parsing](https://github.com/Engelberg/instaparse)
-   Dataflow programming
-   [Concurrent, parallel](https://www.braveclojure.com/concurrency/), and distributed programming
-   [Logic programming](https://github.com/clojure/core.logic)
-   [Functional-reactive programming](https://github.com/day8/re-frame)
-   [Discrete event simulation](https://github.com/helins/dsim.cljc)
-   [System specification (like TLA+)](https://github.com/pfeodrippe/recife)
-   [Property-based testing](https://github.com/clojure/test.check)

There are other domains I want to explore, and great Clojure libraries for them:

-   [Rules engines](https://github.com/oakes/odoyle-rules)
-   [Generative art](https://github.com/quil/quil)

You might look at this list and object that plenty of other languages offer libraries that let you explore other programming domains. In fact, some of the Clojure libraries I linked above are wrappers for Java libraries. So what makes Clojure special here?

Clojure has three properties that make it a superior language for learning programming concepts:

1.  Its REPL provides a tighter feedback looper than other languages, making it easier to perform mini experiments and learn from them. This is a form of self-testing, which studies show is one of the most effective tools for learning. You ask yourself a question, answer it, and compare it to the real answer, confirming (or not) your mental model of a system. The REPL allows you to do this almost at the speed of thought.
2.  Its focus on a small core set of data types and abstractions reduces the amount of non-essential learning you have to work through. In other languages, libraries introduce their own bespoke types with their own bespoke APIs, and the result is that you continually have to revisit the questions of &ldquo;How do I represent data?&rdquo; and &ldquo;How do I transform it?&rdquo;
    
    By contrast, 90% of the time the Clojure libraries you use represent compound data with vectors (which are like arrays), maps (like dictionaries), and sets. Even when they don&rsquo;t, the data types they introduce likely participate in [Clojure&rsquo;s core abstractions](https://www.braveclojure.com/core-functions-in-depth/), allowing you to use Clojure&rsquo;s core functions. You don&rsquo;t have to learn a new API for dealing with something like a LogicProgrammingSet or DiscreteEventMap.
3.  Its minimal syntax and lack of boilerplate. Less boilerplate means less ways to mess up, and less time writing boilerplate means more time experimenting and learning.


<a id="org0139a62"></a>

## Your experience is portable across environments

Clojure was designed from the beginning to be [platform-agnostic](https://clojure.org/about/rationale#_languages_and_platforms), and the result is that is that it&rsquo;s made its way beyond the JVM to frontend programming via ClojureScript, and to shell scripting via [babashka](https://github.com/babashka/babashka). Being able to transfer your programming language experience from one environment to another like this means that you get to spend more time solving real problems. I expect this situation will only improve over time, especially thanks to the unstoppable force that is [Michiel Borkent, aka borkdude](https://github.com/sponsors/borkdude).


<a id="org0982c5a"></a>

## These Companies are Hiring and Will Train You

Are you ready to invest in Clojure? Then these companies are ready to invest in you. These businesses are successfully leveraging all the power that Clojure provides, and they&rsquo;re hiring:

-   JUXT
-   Reify Health
-   Metabase
-   Logseq
