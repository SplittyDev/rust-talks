# rust-talks
Talks about Rust.

Talks are sorted in inverse-chronological order, so the newest talks are always at the top.   
The speakers are in no particular order.

Contributions are more than welcome!    
So if you can find other talks, please open an issue or submit a pull request.

## Talks at RustConf 2016
- [Aaron Turon, Niko Matsakis - Opening Keynote][rustconf16_7]

- [Raph Levien - A Modern Editor Built in Rust][rustconf16_8]

- [Alex Crichton - Back to the Futures][rustconf16_0]   
This talk will explore the implementation of a cross-platform futures library in Rust backed by the full power of mio and leveraging many aspects of Rust to make futures programming even easier.

- [Geoffroy Couprie - Integrating Some Rust in VLC Media Player][rustconf16_1]   
VLC media player has a nice goal for users: handle almost any file or protocol you throw at it. Unfortunately, this results in a lot of parser vulnerabilities, because most of the parsing code is handwritten in C. By leveraging Rust and the nom parser combinators library, could we replace some security critical parts of VLC?

- [Liz Baillie - The Illustrated Adventure Survival Guide for New Rustaceans][rustconf16_2]   
Programming is an adventure, often more harrowing than it has to be. If you're more used to higher-level languages like Ruby or JavaScript, learning Rust can feel like an impossible journey that leaves you wishing for a well-written and heavily illustrated field guide. Good news! I have already gone down this road and am now prepared to share my adventure with you. Luckily, I was able to capture much of the flora and fauna of Rustlandia with my primitive pictorial devices (paper and pen).

- [Josh Triplet - RFC: In Order to Form a More Perfect `union`][rustconf16_4]   
This talk will present unions as a case study of the Rust RFC process, show the kinds of iterative refinements that take place, review corner cases and interactions that arise when attempting to extend Rust, and discuss the next steps forward for union implementation.

- [Suchin Gururangan, Colin O'Brien - The /r/playrust Classifier: Real World Rust Data Science][rustconf16_5]   
Modern machine learning systems require scalable, real-time processing to analyze massive datasets. Rust is an attractive tool to help drive low-cost, high performance data science. But what's it like to use Rust to solve machine learning problems in practice? To evaluate Rust as a foundation for machine learning services, we built a classification system, entirely in Rust, that detects /r/playrust posts mistakenly published on the Rust subreddit. We'll present Rust's strengths and weaknesses at each step of the process, inspiring discussion on its role in the future of data science pipelines. This is a two-speaker talk, also delivered by Colin O'Brien.

- [Without Boats - Using Generics Effectively][rustconf16_6]   
Traits and type parameters are the core mechanism for abstraction in Rust. Other languages also have features like these, but few leverage them nearly as much as Rust does. This talk will describe the many powerful uses for Rust's generics system, how generics can be used as a replacement for tools like inheritance and duck typing, and how to leverage this system to write good, clean code.

- [Julia Evans - Closing Keynote][rustconf16_3]   
Do you ever think “Ok, I'm definitely not a beginner at programming anymore, but how do I get WAY BETTER?” I have. It turns out that there are a lot of amazing things you can learn about programming by learning a little bit of Rust and systems programming, and I'm going to talk about some of my favorites.

## Talks by Steve Klabnik <[@steveklabnik][steve_klabnik]>
- [Rust in Production - Philly ETE 2016][aug_16_2016]   
In this talk, Steve will give an overview of Rust’s value proposition, focusing on examples and anecdotes from companies using Rust in production today.

- [The History of Rust - ACM][jun_21_2016]   
In this talk, Steve will show off some of Rust's history, with all of the decisions and changes that were made along the way.

- [Using Rust with Ruby - Ancient City Ruby 2016][apr_22_2016]   
In this talk, Steve will show off the Rust programming language and how to integrate it with Ruby.

- [Steve Klabnik on intermezzOS - UPenn CIS 198][apr_13_2016]   
Steve visited our CIS 198 Rust Programming course for a guest lecture on [intermezzOS][other_intermezzos].

- [Rust for Rubyists - Rocky Mountain Ruby 2015][oct_05_2015]   
In this talk, Steve will show off Rust, a new programming language from Mozilla, and why it's better for Rubyists than C.

- [How I manage to be efficient - Web2Day 2015][jun_10_2015]   
In this talk, Steve will give an overview of Rust and why you might want to choose it for your next project.

## Talks by Alex Crichton <[@alexcrichton][alex_crichton]>
- [State of Rust 2016 - Rust Meetup Cologne 2016][jun_06_2016_0]

- [The Rust Programming Language - GoogleTechTalks 2015][jun_06_2015]   
Alex Crichton will present an introduction to the Rust programming language, explain how it can be used to build performant, reliable systems, and answer your questions.

- [Intro to the Rust programming language - Code & Supply 2014][dec_11_2014]   
Alex Crichton presents an introduction to the Rust programming language.

## Talks by Aaron Turon <[@aturon][aaron_turon]>
- [Rust: Unlocking Systems Programming - QCon 2016][feb_07_2016]   
Aaron Turon explains Rust's core notion of “ownership” and shows how Rust uses it to guarantee thread safety, amongst other things. He also talks about how Rust goes beyond addressing the pitfalls of C++ to do something even more exciting: unlock a new generation of systems programmers by providing a safe, high-level experience -- while never compromising on performance.

## Talks by Jan-Erik Rediger <[@badboy][jan_erik_rediger]>
- [Compiling Rust to asm.js - Rust Meetup Cologne 2016][sep_05_2016]

## Talks by Kai Michaelis <[@fluffly][kai_michaelis]>
- [Why port 10k LOC to Rust - Rust Meetup Cologne 2016][jun_06_2016_1]


[steve_klabnik]: https://github.com/steveklabnik
[alex_crichton]: https://github.com/alexcrichton
[aaron_turon]: https://github.com/aturon
[jan_erik_rediger]: https://github.com/badboy
[kai_michaelis]: https://github.com/flanfly

[rustconf16_0]: https://youtu.be/bcrzfivXpc4
[rustconf16_1]: https://youtu.be/YTy_JOxGOd4
[rustconf16_2]: https://youtu.be/Ce6ppwgF4SA
[rustconf16_3]: https://youtu.be/ftQfpAeyxPo
[rustconf16_4]: https://youtu.be/U8Gl3RTXf88
[rustconf16_5]: https://youtu.be/lY10kTcM8ek
[rustconf16_6]: https://youtu.be/erJdCIti_O8
[rustconf16_7]: https://youtu.be/pTQxHIzGqFI
[rustconf16_8]: https://youtu.be/SKtQgFBRUvQ

[sep_05_2016]: https://www.youtube.com/watch?v=bvJCMhJ3RnQ
[aug_16_2016]: https://www.youtube.com/watch?v=0emIUsU1_0E
[jun_21_2016]: https://www.youtube.com/watch?v=79PSagCD_AY
[jun_06_2016_0]: https://www.youtube.com/watch?v=mRGb4hoGuPs
[jun_06_2016_1]: https://www.youtube.com/watch?v=xJZn87oqjrY
[apr_22_2016]: https://www.youtube.com/watch?v=Ms3EifxZopg
[apr_13_2016]: https://www.youtube.com/watch?v=iTSx-8qK4Hw
[feb_07_2016]: https://www.infoq.com/presentations/rust-thread-safety
[oct_05_2015]: https://www.youtube.com/watch?v=NaIXIKVxg3M
[jun_10_2015]: https://www.youtube.com/watch?v=CSYilkhDHzw
[jun_06_2015]: https://www.youtube.com/watch?v=d1uraoHM8Gg
[dec_11_2014]: https://www.youtube.com/watch?v=agzf6ftEsLU

[other_intermezzos]: https://intermezzos.github.io/

**Important:** If you do not want your talks to be listed here, please open an issue and I'll remove them immediately.   
