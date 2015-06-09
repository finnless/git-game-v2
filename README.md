#Level 7

You made it to level 7! Awesome!!!

Are you ready for an even bigger git challenge? Yes? Okay!
It appears that a group of malicious [hackers](http://en.wikipedia.org/wiki/Anonymous_%28group%29) have hacked GitHub and deleted an important file in our repo.
This file contained the hidden personal email of Linus Torvalds and the name of the next branch!
They also made hundreds commits after so we can't look through the commit history by hand.
Now this is where you come in!

You must use [```git grep```](http://git-scm.com/docs/git-grep) to search through the whole commit history to find these emails.
Your next clue is the name of the user that is before the domain name ```hint.edu```.

*Hint:* It's best to use git grep with git rev-list as specificied by [this](http://stackoverflow.com/questions/2928584/how-to-grep-search-committed-code-in-the-git-history) stack overflow post.
