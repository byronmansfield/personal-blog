+++
author = "Byron Mansfield"
date = "2016-11-25T20:16:01-08:00"
title = "Why I love Golang"
slug = "2016/11/25/why-i-love-go"
share = true
image = "/static/images/gophers-working.jpg"
tags = [
  "golang",
  "gopher",
  "technologies",
  "favorites",
]
menu = ""
draft = false
comments = true

+++

![Golang](/static/images/gopher.png "Golang")

If you know me at all, you probably know that I am a Golang advocate. Like most my other posts, this is only my opinion and you may not agree. But for those that might be reading this and curious about it, this post will aim at highlighting what I view as it's areas where it shines, and why those appeal to me. Let's get started.

##### Out of the way

What do I mean by this. One of Go's primary goals is to be a language that just get's out of your way and lets you just code. Whew! Finally! I don't know about you, but dealing with many other languages that all come with their caveats and special needs, this is a huge relief. So let me apply some more real world context around this.

If you are a developer working on a project with a Linux user and a Windows user. Go doesn't care. It' handles all this for you. As long as you set up a few very simple requirements described in the setup instructions (and I mean very minimal and super easy) then Go will handle the rest. Just pull the latest changes, make your own, and push them. End of story.

Dependencies. Yes on a small scale this is more realistic. And larger projects like Docker may need some more support. But in hindsight, the package management is trivial compared to some other languages. One less thing to worry about.

Cross platform compilation. Go lets you compile for all platforms. You can distribute your binary to anyone.

##### Support

Well aside that it's backed by one of the internet giants (which doesn't always fair well, but in this case seems to) The community has been very positive in supporting and contributing to the project comparatively to many other open source languages. Iterations are not too fast, but fast enough that major issues do not go long before **proper** fixes are in place. Speaking of which, the thoroughness of their releases is immaculate. When they release an iteration, it is put through the ringers first.

##### Simplicity

I guess I could label this maybe ease of writing the code. It feels very much like a language such as python in the since that it's just easy to pick up, and easy to hammer a proof of concept out. This is super powerful for iterating quickly. Another thing I consider powerful in it's simplicity is it's built in libraries. You will find that you will not need many third-party libraries comparatively to other languages. Which also means much more stable support. Not that you wont, it's just significantly less.

##### Favorite Features in a language

Now this may be just my opinion, but these are things that I favor and I think important to know if you are considering using or learning Go.

It is a functional language. It has no classes. In this since you can think of it more like C or JavaScript (ES5).

Super fast compile time.

True multi-threading.

It got language of the year in 2010.

Tiny footprint. What I mean by this, is that the language itself is small, the complied binary of your project is super tiny, it uses very little host resources. It's simply beautiful.

The success stories. The common one everyone loves to gloat about is Docker. And yes, it is simply amazing what the project built on pretty much 100% Go can do. But so many other projects built in mostly Golang are starting to spawn left and right, all displaying how fast they can iterate with simplicity, minimal code, flexibility, next to nothing footprints, and much more. Look at Rancher, kubernetes ,etcd, logstash-forwarder, grafana, prometheus, heck, even the Golang compiler is mostly Go. Then you look at projects like go-workers that are over 1000 times faster than sidekiq and resque. Stories like Iron.io going from 30 servers to 2 (2 simply for redundancy) all made from newcomers to the language. I mean come on, how you can you deny it's power.

##### Closing

Is it the answer to all my problems. Absolutely not. I still firmly believe in (the right tool for the job). But it fits into that category more times than none. Or at least as a valid option. Am I a full time Golang programmer that knows all the Golang woes, no I am not. But I have worked with many people whom have switched in their full time development and told me about the woes and pitfalls and caveats. Comparatively to other languages, hardly anything scary.

Am I trying to convince you to make the switch from whatever is your favorite language today. Absolutely not. What makes you a badass software developer is whats best for you. Do I believe it should be at the top of your list of languages to explore and learn, Absolutely!

Thats all for now. I hope you guys enjoyed this read and found some value in it. Thanks for reading.
