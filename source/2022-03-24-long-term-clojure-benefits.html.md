---
title: Learning Clojure yields surprising long-term benefits. These companies are hiring and will train you.
date: 2022-03-24
---

# Learning Clojure yields surprising long-term benefits. These companies are hiring and will train you.

Learning any programming language requires a significant investment in time and resources. Of all the languages I&rsquo;ve gained proficiency in, Clojure has by far yielded the largest benefits for my life. Some of these benefits have been surprising and have only become evident with time. I want to share these less-obvious benefits because they&rsquo;ve had such a positive impact on me, and I want other devs to benefit, too.


<a id="orgf579f24"></a>

## Clojure&rsquo;s stability can improve your lifestyle

Clojure&rsquo;s core team is committed to the language&rsquo;s stability over time so that code you wrote years ago will almost always work with the latest version of Clojure.

By unfortunate contrast, some other languages introduce significant, breaking changes like a friend declaring that they&rsquo;re DONE with carbs and are going PALEO thank you very much. This imposes a cost every time you sit down to do some work. Say you want to spend some time on a side project that uses the language `blub v1.0` but you want to use a library built for `blub v1.1`. You are in for a night of pain and horror.

Let&rsquo;s play this scenario out over time. Say you only have 30 minutes to work on a side project. You run into a &ldquo;language overhead&rdquo; issue like the one above. Solving this kind of problem is chaotic, meaning it&rsquo;s hard to pick up where you left off between programming sessions. If you don&rsquo;t solve it the first time, you&rsquo;ll retread a lot of ground the next session. Heaven help you if Life Happens and you can&rsquo;t pick up your project for a couple weeks. It&rsquo;s hard to make actual progress.

What does this have to do with your lifestyle? I&rsquo;ll use this job board as an example. I recently re-built and re-launched this job board, and since then revenue has *quintupled* (!!!). This has provided more income, which obviously helps on the financial end. But what&rsquo;s interesting is that Clojure&rsquo;s stability has let me consistently make real progress on my passion projects without neglecting other parts of my life: making art, spending time with loved ones, etc. I can work less for better results because I&rsquo;m not bogged down by the overhead costs imposed by the language.

I get to build this business at a sustainable pace without sacrificing my personal life because Clojure lets me focus on actually *building* instead of traversing the seven circles of language hell. I built some parts of the site eight years ago. The fact that I can figure something out and it&rsquo;s still useful to me nearly a decade later is the definition of a good investment.

There&rsquo;s another way that Clojure&rsquo;s stability improves your lifestyle: it reduces your stress. The quality of your life is the quality of your day-to-day experience, and if a significant portion of that involves meaningless struggle with your programming language, well it&rsquo;s hard to not end up feeling kinda lousy. And in this economy??

I realize I&rsquo;m probably giving off strong &ldquo;wow this guy is straight up mainlining the kool-aid&rdquo; vibes here. Clojure, ultimately, is just a tool, right? Yes. And if we&rsquo;re going to talk about building a satisfying and rewarding life, we need to talk about tools, and Clojure is an exceedingly good one.


<a id="orgb658aba"></a>

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

More than other languages, Clojure lets you focus on what&rsquo;s essential about the domain or concept you&rsquo;re trying to learn.


<a id="org6494f24"></a>

## Your experience is portable across environments

Clojure was designed from the beginning to be [platform-agnostic](https://clojure.org/about/rationale#_languages_and_platforms), and the result is that is that it&rsquo;s made its way beyond the JVM to browser programming via ClojureScript, and to shell scripting via [babashka](https://github.com/babashka/babashka). Being able to transfer your programming language experience from one environment to another like this means that you get to spend more time solving real problems.

It is hard to overstate how powerful this is. There are two complementary ways to think about this:

1.  You&rsquo;re not limiting yourself to building only certain kinds of applications
2.  You&rsquo;re gaining immense leverage

Generally, when you spend time gaining deep expertise in a programming language you&rsquo;re necessarily limiting yourself to only building certain kinds of applications. Most languages are intimately tied to the kind of environment they target; when you spend time learning Go, you&rsquo;re limiting yourself to server-side apps. When you learn Swift, you&rsquo;re limiting yourself to iOS applications. If you want to start building a different kind of application, you have to learn a new language, with its attendant build tools and architecture ecosystem and paradigm and quirks. On top of that, you have to learn about the environment itself: its resources, its interaction modes, etc.

When you invest the time to learn Clojure, you gain leverage instead of limitations. Learning any language involves more than just the basics of syntax and build tools. It includes deeper topics like how to structure an application for maintenance and evolution. Taking the time to develop Clojure expertise will pay dividends when you switch from backend to frontend development.

I expect this situation will only improve over time, especially thanks to the unstoppable force that is [Michiel Borkent, aka borkdude](https://github.com/sponsors/borkdude). I am very excited for what the future holds!


<a id="org99365d9"></a>

## These Clojure Companies Hire People Without Clojure Experience

Are you ready to invest in Clojure? Then these companies are ready to invest in you. These businesses are successfully leveraging Clojure&rsquo;s power, and they hire people without Clojure experience:

-   [Nubank](https://jobs.braveclojure.com/company/nubank), the largest financial services company in Latin America and one of the biggest IPOs of 2021, is the world&rsquo;s biggest user of Clojure and Datomic, with over 1000 Clojure developers.
-   [Reify Health](https://jobs.braveclojure.com/company/reify-health), a unicorn startup helping pharma companies and research sites enroll patients in clinical trials faster than ever before. Clinical research remains a significant bottleneck on drug development. Much of this is due to the slow and unpredictable nature of patient enrolment. Many potential therapies get scrapped because they failed to enroll enough patients in their trials.  Reify Health is tackling this problem with a platform built on Clojure.
-   [Pitch](https://jobs.braveclojure.com/company/pitch), the modern presentation software we always wished we had. Built for teams that care about where their time and energy goes. They&rsquo;re around 80 Clojure engineers now, and are having a great time learning how to scale a Clojure codebase and team. They&rsquo;ve got a good track record of hiring non-Clojurists and making them fluent in parens.
-   [Metabase](https://jobs.braveclojure.com/company/metabase), the easiest way for people to get insights from their data, from tiny startups who get up and running quickly to major corporations with tens of thousands of users. Their codebase is open-source, and it&rsquo;s one of the largest open-source Clojure codebases on the planet!
-   [Logseq](https://jobs.braveclojure.com/company/logseq), a startup that exists to increase the knowledge output of humanity. They&rsquo;re starting with building a personal knowledge assistant.
-   [Mobot](https://jobs.braveclojure.com/company/mobot), a startup building developer tooling to help automate the manual side of mobile app QA (all the onerous work that remains after you&rsquo;ve put in the time to leverage emulators and simulators). They&rsquo;re using robots we fabricate to execute tests on a corpus of test devices. Their web apps and internal mobile app use ClojureScript.
-   [Crossbeam](https://jobs.braveclojure.com/company/crossbeam), an escrow service for data with more than 5000 companies and more than $100M of venture capital. Their platform allows companies to find overlapping customers and prospects with their partners while keeping the rest of their data private and secure.
-   [JUXT](https://jobs.braveclojure.com/company/juxt-ltd), a consultancy using Clojure to build systems and keep complexity under control. They&rsquo;re hiring experienced Clojure practitioners as well as those that are keen to learn. JUXT also created XTDB and many well-known Clojure libraries.
-   [BroadPeak Partners](https://jobs.braveclojure.com/company/broadpeak-partners), a company that helps less technical users manage data streams and integrations without having to rely on developers. They&rsquo;re focused on enterprises with increasing amounts of data to manage, the need to move fast, and deliver sustainable solutions.
-   [Riverford Organic Farmers](https://jobs.braveclojure.com/company/riverford-organic-farmers), an employee-owned company that delivers organic food to around 90,000 homes and businesses across the UK!
-   [Shortcut.com](https://jobs.braveclojure.com/company/clubhouse-io), an intuitive and enjoyable project management platform, has been using Clojure for its backend since day one.
-   [Dewise](https://jobs.braveclojure.com/company/dewise-aps), a Cloud-first, polyglot, product and solutions development company, using Clojure for tricky data manipulation, tricky logic programming and dynamic business logic backends.
