# sylvania-mt6261
 
This is a place for me to store anything relating to writing custom code for my funky sylvania mt6261 based watch.

---
Here is the repository that makes it all possible:
- https://github.com/xobs/fernly

...and the fork to keep it going for the MT6261:
 - https://github.com/isogashii/fernly/tree/fernly6261

Here is my fork of flashrom based on the patches from xobs and with support for the W25Q32JV flash chip added: 
- https://github.com/gbryant/flashrom/tree/fernvale-MT6261-sylvania


I can successfully dump my rom using the fernly6261 branch, to dump my flash rom I used the fernly6261 branch, the fernvale-MT6261-sylvania flashrom fork and the scripts in this repo.
___
I run everything from a raspberry pi so I don't have a watch dangling from my laptop.
___
The serial connection from the RPI to the watch would drop during the flashrom dump, so I came up with the scripts in the repo to dump a chunk at a time.
+++
My RPI SD card was low on space so I zipped the parts as they were dumped, there is no unzip script because I just unzipped the files in the GUI on my desktop after downloading them.