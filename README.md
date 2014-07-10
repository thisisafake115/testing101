Just a demo. Anyway, Java just got beaten seriously by C.

After a commit, all tracked files are set to the 'unmodified state'. Then we edit the file in this state, it is in 'modified stated

Basically, files which are in unmodified being modified then we have 2 option: add or checkout.
If we add, that's ok. What if do checkout? I just screwed up last time, didn't know how to fix. Need digging more.

Then we add not yet make a commit, then we edit again, what happens?
There would be two version of that file. One is waiting to be committed, one is wating to be added to the cache.
If we do the add then git will override to the cache, which is waiting for commiting.
