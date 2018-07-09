---
title: "Koron Game Engine"
categories:
  - Programming
  - Go
  - KGE
tags:
  - gaming
  - go
  - golang
  - kge
  - opengl
---
Ever since I started programming it has always been a dream of mine to build games, although I am a web dev I have in the past made some simple
games in different languages, such as Java, Rust and C++ but nothing notable and mostly following tutorials I have found on the web and adjusting 
what I followed to fit what I wanted.

Recently I have been quite bored with my personal projects as they are all based around web development and building SaaS system, and to be honest
building websites is boring. So I finally decided I will pursue my dream of being a game dev and started working on my own game engine. Although
people say to use what is already around and build an actual game rather than spend years on building an engine, but again, I'm not normal I enjoy
building things that no one really sees or takes notice of, such as the game engine, so why the hell not.

I did some research as I have recently been writing a heap of golang and not much else, my findings were quite disappointing, everyone complains that
cgo is too slow to even bother using for game development, although most of these posts are old, cgo is still not as efficient as using other languages.
This deterred me a little, so I then started digging into resources in Rust, and soon realised it had been such a long time since I had used Rust that 
most of my time would be spent relearning the language, and I didn't really have time for that.

Once I gave up on Rust I decided to do some more research into using Go, finding that their were not many game dev resources for Go as not many have
used go for game dev, I made the bold choice that I would pave the way myself and give it a crack.

So day one of KGE was mostly spent using the opengl and glfw library to get a basic window up, once I was happy with that I started neatening my package
up to make everything easy to initialise for game devs from there I moved on to doing some research into what are the industry "standard" for models and animations etc.
I decided I would support two model types, the OBJ spec and the COLLADA spec.

Most of my recent time spent on KGE has been implementing the OBJ spec so that I can start reading/parsing .obj files into memory for use with OpenGL
so keep an eye on this space as I dare say my next post will be in a bit more detail about implementing the OBJ parser and hopefully have some models
loaded up into my game engine!

