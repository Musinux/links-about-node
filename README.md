# links-about-node
Just a bunch of links related to Node.js and nodejs internals

Also checkout videos on [links-about-web-programming](https://github.com/Musinux/links-about-web-programming#web-security)
## Preamble


> You should be unhappy with code you wrote a year ago. If you aren't, that means either A) you haven't learned anything in a year, B) your code can't be improved, or C) you never revisit old code. All of these are the kiss of death for software developers. 
>                   -- from [Coding Horror](https://blog.codinghorror.com/sucking-less-every-year)
[https://blog.codinghorror.com/why-im-the-best-programmer-in-the-world/](https://blog.codinghorror.com/why-im-the-best-programmer-in-the-world/)

## Learn Javascript basics
- [Javascript cheat sheet (pdf)](https://github.com/mbeaudru/modern-js-cheatsheet)
- [Another cheat sheet (github repo)](http://overapi.com/static/cs/jsquick.pdf)
- [Yet Another cheat sheet (web page)](https://www.codementor.io/johnnyb/javascript-cheatsheet-fb54lz08k)
- [ES6 cheat sheet (github repo)](https://github.com/DrkSephy/es6-cheatsheet)
- [StandardJS guidelines to write beautiful code (web page)](https://standardjs.com/index.html#the-rules)
- [Node Hero: Getting started with Node.js tutorial (blog article)](https://blog.risingstack.com/node-hero-tutorial-getting-started-with-node-js/) (Really good tutorial to begin with)
- [Quick learn of new Javascript features](http://es6-features.org)

## Node internals
Maybe, you should begin by reading [What Hackers Learn That the Rest of Us Don't](https://www.cs.dartmouth.edu/~sergey/hacker-methodology.pdf), specifically the section 2 if you "don't have time to read it all"


- [How JavaScript works: inside the V8 engine + 5 tips on how to write optimized code (blog article)](https://blog.sessionstack.com/how-javascript-works-inside-the-v8-engine-5-tips-on-how-to-write-optimized-code-ac089e62b12e)
- [A sneak peek into super optimized code in JS frameworks (yt conf)](https://www.youtube.com/watch?v=_VHNTC67NR8)
- [Just-in-time compilation explained (MDN)](https://hacks.mozilla.org/2017/02/a-crash-course-in-just-in-time-jit-compilers/)
- [Libuv: the underlying lib of Node.js (youtube conference)](https://www.youtube.com/watch?v=nGn60vDSxQ4&t=29s)
- [Deep dive into libuv (youtube conference)](https://www.youtube.com/watch?v=sGTRmPiXD4Y)
- [Everything you need to know about node.js event loop (youtube conference)](https://www.youtube.com/watch?v=PNa9OMajw9w)
- [More on the node.js event loop (youtube conference)](https://www.youtube.com/watch?v=P9csgxBgaZ8)
- [Node.js guide about the event loop (blog post)](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
- [What is shared between threads, and what's not (stack exchange question)](https://cs.stackexchange.com/questions/48345/what-threads-share-in-general)
- [Myths Programmers Believe about CPU Caches (blog post)](https://software.rajivprab.com/2018/04/29/myths-programmers-believe-about-cpu-caches/)
- [Node.js, TC-39, and Modules (blog post)](https://hackernoon.com/node-js-tc-39-and-modules-a1118aecf95e)
- [An Update on ES6 Modules in Node.js (blog post)](https://medium.com/the-node-js-collection/an-update-on-es6-modules-in-node-js-42c958b890c)
- [Transform all node.js utilities to promises, with the agreement of Node.js core team (blog post)](http://2ality.com/2017/05/util-promisify.html)
- [Type coertion in Javascript (blog post)](https://2ality.com/2019/10/type-coercion.html?utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+2ality+%282ality+%E2%80%93+JavaScript+and+more%29)


## Advanced uses
- [Why Learn Functional Programming in JavaScript? (blog post)](https://medium.com/javascript-scene/why-learn-functional-programming-in-javascript-composing-software-ea13afc7a257)
- [Templates literals | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals#Browser_compatibility)
- [Async functions (blog post)](https://blog.risingstack.com/mastering-async-await-in-nodejs/)
- [Express vs Hapi performance (2017) (blog post)](https://raygun.com/blog/node-js-performance-2017/)
- [Mistakes made with mongooseJS (blog post)](https://www.mongodb.com/blog/post/the-mean-stack-mistakes-youre-probably-making)
- [Programming Best Practices: Memory Efficiency with Closures (yt conf)](https://www.youtube.com/watch?v=u17ejrZlDLY)
- [this operator examples](https://gist.github.com/Musinux/6ad9132491f5a939416865e8b910c97b)

## Unit testing
- [A useful guide about testing](https://fr.scribd.com/document/69769/TheWayOfTestivus)
- [The short version of this useful guide](https://testing.googleblog.com/2010/07/code-coverage-goal-80-and-no-less.html)
- [Unit testing Guide for Mongoose](https://codeutopia.net/blog/2016/06/10/mongoose-models-and-unit-tests-the-definitive-guide/)

## Debugging
- [Node.js Tools for development debugging (blog post)](https://www.nearform.com/blog/node-js-develop-debugging-techniques/)
- [Debug Node.js with Google Chrome (blog post)](https://medium.com/the-node-js-collection/debugging-node-js-with-google-chrome-4965b5f910f4)
- [New DevTools features to debug Node.js (youtube conference)](https://www.youtube.com/watch?v=dbCcVzt9C1c)

## Hardcore Debugging
The type of debugging you don't do for fun
- [MDB to debug core dumps](https://www.joyent.com/node-js/production/debug/mdb)
- [MDB_v8 to debug Node.js core dumps](https://github.com/joyent/mdb_v8/tree/master)
- [Debugging Node.js applications using core dumps](https://www.reaktor.com/blog/debugging-node-js-applications-using-core-dumps/)
- [Debugging Node.js in production (youtube conference)](https://www.youtube.com/watch?v=CiqzuIUwHl8) advanced debugging techniques

## Security
- [A Roadmap for Node.js Security (google sec team)](https://nodesecroadmap.fyi/)
- [Analyzing your repo for known-vulnerable dependencies (website)](https://snyk.io/vuln)
- [Writing secure node.js code (youtube conference)](https://www.youtube.com/watch?v=QSMbk2nLTBk)
- [npm & dependencies security management (youtube conference)](https://www.youtube.com/watch?v=2_aclLr3o5s)
- [Somebody Tried to Hide a Backdoor in a Popular JavaScript npm Package](https://www.bleepingcomputer.com/news/security/somebody-tried-to-hide-a-backdoor-in-a-popular-javascript-npm-package/)
- [Cross-Site Request Forgery mitigations (github)](https://github.com/pillarjs/understanding-csrf)
- [Eval no more: a journey through NodeJS' VM module, VM2 and Expression Language (blog post)](https://odino.org/eval-no-more-understanding-vm-vm2-nodejs/)


## Use in production
- [Node.js Logging Best practices (blog post)](https://strongloop.com/strongblog/compare-node-js-logging-winston-bunyan/)
- [Node.js at scale (blog post)](https://blog.risingstack.com/nodejs-at-scale-npm-best-practices/) tutorial about using Node in production (dockerisation, scalability...)

## Talks from companies
- [Node.js at Uber (youtube conference)](https://youtu.be/ElI5QtUISWM?t=8m20s)
- [Designing (architecturally speaking) very large applications (Google) (text article + video)](https://medium.com/@cramforce/designing-very-large-javascript-applications-6e013a3291a3)

