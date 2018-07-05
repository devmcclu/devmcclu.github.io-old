---
layout: post
title: "More Projects, Less Time"
date: 2018-07-05
---

It is already July. It doesn't feel like it at all. At least I have done some things with my time. Outside of family duties and such, I have been slowly working on Project FreeGUN. I don't know how much as actually changed since the last time I made a post, but it does feel like a well put together game, compared to where it was at the end of April. Character movement won't break the game later on, I have done my best to keep the code open for multiplayer once I feel the project has all core features implemented, and I feel so much more comfortable working in Godot. The documentation for Godot is amazing, and without it I would be lost. FreeGUN has been light on features lately though, and that is for good reason.

##Iso Dark Theme
I wanted an easy way to theme Project FreeGUN's UI so it makes it easier for other devs to have something almost plug and play like. So when starting to build the UI, I remembered stumbling across [Awesome Godot](https://github.com/Calinou/awesome-godot), a GitHub repository with a list of free software made in/for the Godot Engine. Luckily enough, one theme was there for game GUI's called [Iso Themes](https://github.com/GalanCM/Iso-Themes). Only one theme existed, called Iso Dark. Unfortunately, it was built somewhere during Godot 2/2.1, which meant it either had to be converted or rebuilt from the ground up. I tried to export it to 3.0 using Godot 2.1.5 RC 1, but that failed. So, I rebuilt as much as I could of it using what limited knowledge of Godot's theme engine I had, and trial and error. I made it work, but there are some issues that need to be ironed out. Check out the project over at [GitHub](https://github.com/devmcclu/Iso-Themes) or [GitLab](https://gitlab.com/devmcclu/Iso-Themes) if you want to use it yourself or help me fix the tiny issues with it. Now with that out of the way, the first step to making the UI of Project FreeGUN easily modified is done.

##What Now?
Now, it is time for FreeGUN to have a UI! Since Project FreeGUN is a shooter "template," staples of shooters such as ammo count, gun, and health will be the basis of the UI. How it will look, we'll find out.
