# digipick
**Starfield Digipick Solver**

Here is my 'Starfield Digipick Solver'. It's working on my 1920 x 1080 fullscreen shots but it should work on anything at 16:9 ratio. Just take a screenshot in game (no borders) then click 'Choose file'. 

Just be carefull to keep the cursor away from tne places on the screen I'm looking at, like around the digipicks keys and the lock empty slots. I put mine in the center of the lock or the edges.


note: In the solved-master-lock.jpg, `n` is the number of recursive calls to `solveLock` and elapse runtime is in `ms`.

solveLock2() was an attempt to speed up the original solver and it did decrease the number of recursive calls, but it was a disapointment in the reduction of runtime.


 solveLock2(0)
 n: 6941, 102.2 ms, lock,[pins]: [1,[3,4,10,14],ø,ø,0,[1,7,8,14], ...

  solveLock(0, 0)
 n: 102522, 110.7 ms, lock,[pins]: [1,[3,4,10,14],ø,ø,0,[1,7,8,14], ...
