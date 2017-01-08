+++
menu = ""
author = "Byron Mansfield"
draft = true
image = ""
share = true
comments = true
slug = "2016/11/25/technology-rants"
date = "2016-11-25T18:40:27-08:00"
title = "Technology Rants"
tags = [
  "technology",
  "rant",
]

+++

#### Preface

The following is just my thoughts and opinions of technology related subjects from OS's, best practices, languages, etc. Not attacks on any one thing in particular. More or less a rant or me just rambling. I am not trying to offend anyone of their beloved technology. If I formed an opinion about something that may be based on false facts or bad experiences (I totally expect this to happen) please write me back and provide me with the correct facts or insights.

As an added note, please see my post of my journey through the technology stack so you can understand the context of where I am coming from. Also it may be helpful to know that I am a minimal-ist. So my opinions will favor less complex technologies.

#### Text Editors / IDE's

It's no secret that I am an avid vim user. I have used a variety of them as daily drivers all the way to just cracking it open and testing it out, to watching people talk about them or give demo's of them.

##### Vim

I'll start with my current favorite, vim. So why am I here now in a love affair with vim after years of going through others?

Well, these days, I have moved towards a keyboard driven environment. Sure you can do that with just any other editor if you set them up right. But it's more than that. I have moved most of my workflow and tools from GUI's over to command line tools because I feel it's more sane to have them all in one place, and I have more fine grained control over what they do and how they react. As well as automating most the things I do through scripts. I also live inside of a tmux session, in which I have vi key bindings. I also use a vimium (a chrome plugin that uses vi key bindings to navigate).

I know how to edit files on pretty much any system I log into without having to install anything.

I've finial taken the time to learn all the key bindings, and tailed my vimrc to total awesomeness. Now it's way less painful.

I know many new vim newcomers will not know how to do a good deal of things in vim like they can in a text editor such as sublime. I was there once and I learned vim years ago, way before it became my daily driver. I just didn't know how to use it to it's full potential so I always defaulted back to whatever it was I was comfortable with.

##### Sublime / Atom

Oh Sublime. How I love thee. Sublime once was my daily driver for many many years. It is quite great. I'm sure I didn't customize it to it's full potential and I could have made it more awesome. I gave atom a good shot as well, when it first came out. It was my daily driver for a few months. It was great. I like it just as well as sublime. I gave it another try after it matured a little. I highly recommend it. But in the end, it was not keyboard driven enough, and it was not inside my terminal.

##### Visual Studio

I worked in a MS shop for a few years and VS was my daily driver there. I was using it during the time that they had the 2012 release. 2012 was much nicer than I had expected. But at the end of the day, it was just too complex for my taste. I get why users favor it for C# development. The autocomplete is unbeatable. But, I don't code in C# so it looses a great deal of it's potential for me. The version control integrations where not quite there for git as well, though I admit my experience was minimal here. It was obviously stronger for team foundation.

##### Eclipse / IntellaJ

Eclipse, the IDE that can do anything. And there are many different flavors of it. For me much the same issues as most other text editors/IDE's. Not home row key driven enough for my taste, and too complex. But other than that, there is a plugin for everything, support for everything, totally customizable. Same goes for IntellaJ. I worked at a few Java shops. Some (like at Apple) the projects we worked on were Spring MVC so everyone used the Spring Tool Suite or STS (another fork of Eclipse). Then I moved to a vanilla Java shop where it was the old schoolers vs the new schoolers, which were rebels and used IntellaJ. I wanted to fit in with the hip coders, so I got cozy with IntellaJ. To me, pretty much the same as Eclipse. It was slightly simpler than Eclipse out of the box, so more lightweight and loads faster, etc, but still extensible. Still, too complex for my taste. That's really my only grip with these.

##### Emacs

Emacs I really need to give more of a chance. It has a strong following and from what I know, it can do *anything*. I just haven't taken the time to get cozy enough with it to where I know how to navigate around.

##### Nano

Nano is actually alright. It has many of the same things I love about vim, but also lacks a lot of more complex features that I love about vim. It's simple and gets out of your way. I can use it pretty much no matter where. But I can do all the text editing ninja moves that I use in vim.
##### Textmate ++

Textmate ++ is pretty great, but what can I say. Windows only. :(

#### OS's


#### Languages

I'm note going to go through every language that I have written in. Rather I'm just going to list features I dislike and feature that I love.

If you've read this far, you probably already know that I'm a minimalist and favor simplicity. I'll start with managing libraries/packages. This is probably one of the biggest nit-picky things I usually have strong opinions over. As well as, this is an extremely hard problem to solve from the languages create side. I hate spending most of my time dealing/managing libraries/packages. Since when did working on a project become all about making sure your dependencies are happy? I get it, all developers have just learned this is a part of life developing code. And it is good so that you understand the libraries/packages that your using. But I mean come on? When I spend too much time dealing with them, it only cuts into my time working on the actual project. There are languages out there that it's just handled for you, and you can spend more of your time, worrying about the code you write. Examples: Golang, Python.

Next on my list for things to criticize when I'm inspecting languages to use. Application. Is it the right one to use for the job? I despise when people just write only in one language because they thing it is the ultimate language. There are so many other things to consider. Is it thread safe, does it require a lot of memory, am I going to have to install a lot of tools just to deal with the language, is it over complicating things when there is a simpler alternative, compiled vs runtime, the list goes on. They made multiple languages to solve different kinds of problems. One language is not the answer to everything.

I suppose my next preference is more a generalization, in a use case scenario. But I prefer to spend my time learning and using languages that are going to have similar characteristics of majority of other languages. Ones that are so unique when a new comer whom might not be as familiar with the language looks at the code and no freakn' clue what the language is doing, this means it's very specialized. What I mean by this, is not how the project is structured. There is no escaping that, and this topic is more the language it's. But when it has all kinds of native funky syntax. Sure it might be very convenient to use these special built in methods, but unless you are a frequent user of the language where you write in it fluently every day, most will not have a clue what is going on. These languages are not usually my top choice, because the typical practices are not following the masses.

Next on my list, it's sorta a two fold; community and support. This I have seen on both ends of the spectrum. Too little support and community, to way to active. The too little I think is self explanatory. If not, quick example; say you're working on a project and you get stumped on something, so you have to google it. What is the likelihood you will find your answer on the first page. On the other end of the spectrum, too active. Well, lets say your using a new language or even framework, tools, libraries, etc. Which is pushing new version very very rapidly. Well this makes it very hard to keep up, and even sift through forums and documentation trying to find something helpful. That is a huge amount of wasted time. Not necessarily old and trusty, but not bleeding edge either. Don't get me wrong, I love playing around with new languages. Just be mindful of it when you select these languages.

Another big thing I look at when trying to decide which language to use for a project is the amount of allowance for ability to be *explicit vs implicit*. In my opinion languages that allow for too much loosey goosey-ness allow developers to shoot themselves in the foot. Example, locking dependency version, or not specifying types correctly. Let's use these languages as the way they were designed. Just because they allow you to do something, doesn't mean you should.

Build toolchain. what I mean by this is, compilation. Does it take a whole bunch of tools and conversion to and from C code just to make this run. I don't want to have to iterate over a project thousands of time and have to wait for a million years for it just to build. Totally unnecessary. In my opinion, you should just be able to write it and run it for the project needs. JavaScript for the browser (ES5) fine, using ES7 and node(whatever the latest version is) where you build a ton of crazy tools like `ng` and such, OVERKILL!

Lastly, I typically stay away from things that *simulate* anything. Things like **multi-threading**. If it has to *simulate it* then it's the wrong tool. Use one that actually does this. Otherwise when the project becomes larger and more complex, your risk of build breaking goes up. This is not scalable.

#### Deployment and Provisioning

#### Best Practices

##### Source Control

##### Agile Development

##### Code Reviews
