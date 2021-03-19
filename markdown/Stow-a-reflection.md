---
date: 2019-11-12
---

	   _______________ _       __
	  / ___/_  __/ __ \ |     / /
	  \__ \ / / / / / / | /| / /
	 ___/ // / / /_/ /| |/ |/ /
	/____//_/  \____/ |__/|__/


I made a [Video about GNU Stow](https://youtu.be/vo1KUAb-ghc) a while back. The general idea behind it is that it works by using symlinks to essentially automatically manage your files. Most people use them for DOT (Config) Files.

Heres a super basic guide so you know how to use it...

1. install Stow (sudo pacman -S stow)
2. Make a folder in home, call its DOTS for easy remembering.
3. make a folder for each application you want to stash... store... stow.
4. in that folder mirror the location the file is found. for instance in my example I'm backing up the config for mpv. If its found in ~/.config/mpv/config.conf (its not) I would make a folder in DOTS like this ~/DOTS/.config/mpv/ and then MOVE all the shit from the old place to the new one.
5. repeat as required for all the shit you want to back up
6. Run 'stow mpv' (or other application name. )
7. Profit.

Now you can back up your shit to a git service REALLY easy. Even I did it!

The reason I have been thinking a lot about stow is because I had my /home drive die the other week. Poof. 3TB gone! - sad times - Anyway... I had my Home drive die and while I did not have to reinstall my system I did have all my configs ripped out of my soul! so, I git cloned my own dot files. and then I ran my StowRestore script and I was done! Before I knew about stow, I had all sorts of shitty restore scripts and odd folder ideas. It was terrible.

When I find a program, and make a video about it I always wonder how much interest people will have in it. In the case of Stow, I can now say will all certainty that you SHOULD be using it because its GREAT and it saved me a LOT of work. All you have to do is remember to Stow new files as required! :)
