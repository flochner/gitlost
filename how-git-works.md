# Freddie Lochner

Git Research Summary

**1. Things I know about Git**

* It has revision control, or, it's main function is revision control.  
* Somehow, it manages group submissions.  
* People/Groups use it to share code and programs with the world.

**2. Things I don't know about Git**

* How does it control group versioning?
* I know what a fork is, but I think I've seen a fork re-committed to the original and I don't know how that is managed.
* Hundreds of people commit to the Linux kernel.  In general, how is a large group managed?  How do they know which commmits to incorporate?  Are they automatically merged?

**3. What I have learned about Git in the last thirty minutes?**

* Not much.  To be honest, it took me over an hourr just to start actually typing.  It seems most of my time has been spent on making sure I can get this commited properly with decent markdown, even though markdown is not the point of the research (I think).  
* Regarding markdown, why does github not recognize newlines?  One on the tutorials showed it working.  Using Sublime; I checked line endings.
* I read the [wikipedia page](https://en.wikipedia.org/wiki/Git) and learned some interesting things:
  * Linus Torvalds created Git.  Would have never guessed.  Seems like a recent Internet phenomenon.
  * This is going to hurt: [Git Operations](https://en.wikipedia.org/wiki/Git#/media/File:Git_operations.svg) (visual)
* My understanding of the basic commands:
  * **init** prepares the local directory (creates a hidden config/status file)
  * **remote** makes a link back to the repository on github so you don't have to type in the url every time.
  * **clone** makes a local copy of a remote repository.  It can be any public repo.
  * **add** tells the local git to track the specified file.
  * **commit** takes a snapshot of the specified files on the local repository.
  * **push** takes the 'commit' and posts it to the remote repo on github.
* Even with the 'git --help' I had trouble figuring out why my commands weren't working.
  * 'git commit' requires a filename or a global symbol (*).
  * When I set up a remote to 698 Notes (maybe it was my repo), I don't remember having to type my password in for every push.
  * 'Push'ing takes forever to refresh on github.  The first half-dozen times it made me think I was doing something wrong.  Edit: apparently I still am.  This is supposed to be easy.
* I feel I have not met the requirements of the assignment, research-wise.  Lots of reading and thinking, but I only feel moderately more enlightened than before.  

**References**

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines) - github/adam-p
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/) - github
- [Git](https://en.wikipedia.org/wiki/Git) - wikipedia
