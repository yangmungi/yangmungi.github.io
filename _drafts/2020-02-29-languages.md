---
layout: default
title: "Programming Langauges"
date: 2020-02-29 13:48:00 -0700
comments: true
categories: 
---

So far, after all my studies, I've categorized languages into three dimensions.

One dimension is about a languages closeness to the physical specifications (e.g. machine language).
Another dimension is about a language to provide tools to manipulate itself (a.k.a. metaprogramming).
The last dimension is about a language to provide tools to check that the implementation is correct (e.g. type systems).

Granted that with machine language, any direction can be achieved, meaning that one can create a metaprogramming-focused or type-system supported language, I find this taxonomy is diverse enough to warrant proper conversation.

I guess the next step is to somehow prove that each aspect described is mutually exclusive.
Unfortunately, they are not, as languages that are close to physical specifications may not be only meta-programmable or type-safe, as the physical specifications tend to be a moving target, albeit maybe in the scale of years.

Given that much, we can proceed with the effects of this categorization.

Languages that give to meta-programming tend to be more adaptive and iteration-heavy. 
THey tend to comprise tools that are highly adaptive to change, but are unpredictable.

On the other hand, languages that give to type-safety tend to the highly preventative to change, mainly due to the steep learning curve of any system that is in place to enforce such type enforcements. However, with the type-safety, there are a lot of assumptions that can be utilized when writing a program, and those assumptions ultimarly assist the mindful programmer in modifying a program's behavior utilizning less information.

However, this is not without downside (as most things are not). This means that, although an application is more flexible, it is also more unstable.

As a conclusion, it seems that a classification of languages into: "meta-programming", "type-enforced" and "machine-local" would mean that we're divinding the act of proramming into the following cateogries: 

The things we want the programs to do, the thing that we need programs to do, and the thing that programs need in order to do anything.
