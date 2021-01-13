+++
title="The Vim Way"
date=2020-05-17

[taxonomies]
categories = ["Tutorial"]
tags = ["vim"]
[extra]
comments = true
+++

_To first learn Vim, one must know how to quit vim_

_- The Internet_

Disclaimer, I am by no means an expert in the usage of Vim. Compared to the
many seniors out there I might as well as a frog within a pond due to this
reason there might be some incorrect information (which I hope not). In such
any critics or advice is highly appreciated.

Now with that tedious disclaimer out of the way, let's hop in!

<!-- more -->

# Introduction to Vim

So you got an assignment to write an essay about the history of memes, or you
want to update your blog that has long since been updated, or maybe you finally
gather enough will to finally work on that project of yours that had long been
left alone in the corner of your mind. Well no matter all you need to do is to
finish them one by one as quickly as possible, and you were just about to
that... until you look to your left and saw your friend writing something on
the command line. You took a closer look, and to your surprised your friend is
actually writing an article about how gachas could save your life. Not only did
he write in such unusual place, but he also edits it so fast just by pressing a
few keystrokes, almost like one of those hacking movie clip you watch last
week. Your interest is piqued, and you desire to have a taste of that cool
looking power, so you ask your friend _how do you do that?_ in which he replied
with the most wise voice you have ever heard in your life _I just use Vim_.

Quite a landish story right? I know, I crafted it after all. But as ridiculous
as it is there are some truth to the story. My interest in Vim started when I
saw an upperclassman of mine write a piece of code on it. I saw him write,
edit, and navigate through the file like a wizard. With a single push of a
button he managed to get to the end of a line, with two presses he changes a
whole word, with 3 he managed to get from line 1 to 52. It was amazing, fast,
and more importantly so cool. I want it, I want to do those cool stuff, I want
to hold those amazing power, and so I began my journey on Vim.

Usually any sane people would start slowly and steady, in a relaxing time when
they could fully devote theirselves without having the extra pressure from any
other tasks, needless to say I wasn't exactly a great follower of that. Midterm
is on its way, and we had a task to finish in a week not to mention that we
have a lab tomorrow. Me being the not-so-sane person who I am decided to
uninstall the text editor that I used at the moment and chose to only use a
pre-configured Vim.

Needless to say many swears were shouted, many walls were harmed from heads, and
many foods were consumed in frustration from that day onward for a whole week.

But that daring yet at the same time brilliant plant of mine work. With
deadlines approaching I was forced to use Vim continuously and with it come
mastery of the basics. Within a single hour I managed to move, type, edit, and
more importantly quit. By the end of the week, I manage to configure it to my
satisfaction (more or less). By the end of the month I'm pretty much stuck with
it, mostly because of the habits that I developed when I start using it.

## What is Vim?

Vim, is a minimal text editor. So minimal in fact that it doesn't have any
graphical interface at all and instead can be used in terminals, with of course
the option of using it with a GUI (But really why would you?). Often time it
is used when editing a file via the terminal such as when you navigate your
system using the tty or when you are accessing a remote server using ssh. You
might even encounter them when a friend of yours suddenly open a terminal
instead of a text editor like Sublime Text or Notepad.

## Why Vim

There are a few advantages of using Vim. One of them being that vim is always
available in any Unix-based system. Meaning that if you were to ssh to a remote
server chances are vim will be available to use. Another advantage would be how
easy to use it would be for you to use since vim can be easily customized. One
final thing would be how easy to it is to edit text once you get the hang of
it. Maybe not faster, but it'll certainly easier to edit a large chunk of text
since you won't be using your mouse plus the many expressive ways that vim has.

## Why not Vim

The first thing come to mind would be the learning curve. It's quite hard to
pick up if you got used to other text editor, meaning you won't be editing
lines after lines of code like a technical warlock. Another bad thing would be
just how ugly it is when you first start using it. Not going to lie if you
transitioned from a modern text editor like Visual Studio Code or Sublime
chances are you'll be turned off using vim when you first saw how it is right
off the bat.

<!-- <img src="{{ resize_image(path=default_vim.png)}}"/> -->

{{ image(src="/img/default_vim.png", alt="default vim", height="100px") }}
{{ image(src="/img/python_without_plugin.png", alt="default vim", height="100px") }}

Pretty ugly right?

The last thing reason why you not to use it is that if you're too
lazy to read the documentation since a lot of information regarding vim is
available in the documentation even regarding plugins.

That said and done if you still choose to use vim then it'll be better to go
and start the basics

[something](@/posts/baby-steps.md)
