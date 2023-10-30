# digipick
**Starfield Digipick Solver**

Here is my 'Starfield Digipick Solver'. It's working on my 1920 x 1080 fullscreen shots but it should work on anything at 16:9 ratio. Just take a screenshot in game (no borders) then click 'Choose file'. **New!** Now you can just paste the image (Ctrl-V or Shift-Insert) after a screenshot.

Just be carefull to keep the cursor away from tne places on the screen I'm looking at, like around the digipicks keys and the lock empty slots. I put mine in the center of the lock or the edges. See warning2.jpg

**Important!** 99% of the puzzles are solved in less than a secound but I have come across one [Master Lock]('1 min Master Lock.jpg') that took almost a minute!

<!--
**note:** In the solved-master-lock.jpg, `n` is the number of recursive calls to `solveLock2()` and elapse runtime is in `ms`.

`solveLock2()` was an attempt to speed up the original `solveLock()` and it did decrease the number of recursive calls, but it was a disappointment in the reduction of runtime. You get the old solver by clicking the checkbox. 

Also, if you `[Choose file]` and it's the same file, nothing gets triggered. Default browser behaviour <sub><sup>☹️</sup></sub>

```
solveLock2()
n: 6941, 102.2 ms, lock,[pins]: [1,[3,4,10,14],ø,ø,0,[1,7,8,14], ...

solveLock()
n: 102522, 110.7 ms, lock,[pins]: [1,[3,4,10,14],ø,ø,0,[1,7,8,14], ...
```
-->
