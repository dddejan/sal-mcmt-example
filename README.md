Example how to translate SAL to MCMT, just follow the commits.

End result
```
dejan@hilbert:~/example$ ~/workspace/sally-clean/build/src/sally --engine pdkind --solver y2m5 wbs_simple_7_17.mcmt -v 1 --lsal-extensions --pdkind-minimize-interpolant --pdkind-minimize-frames
[2017-07-17.14:17:36] Processing wbs_simple_7_17.mcmt
[2017-07-17.14:17:36] pdkind: starting search
[2017-07-17.14:17:36] pdkind: working on induction frame 0 (1) with induction depth 1
[2017-07-17.14:17:36] pdkind: pushed 8 of 9
[2017-07-17.14:17:36] pdkind: working on induction frame 1 (7) with induction depth 2
[2017-07-17.14:17:36] pdkind: pushed 7 of 8
[2017-07-17.14:17:36] pdkind: working on induction frame 2 (6) with induction depth 3
[2017-07-17.14:17:36] pdkind: pushed 7 of 8
[2017-07-17.14:17:36] pdkind: working on induction frame 3 (7) with induction depth 4
[2017-07-17.14:17:37] pdkind: pushed 8 of 9
[2017-07-17.14:17:37] pdkind: working on induction frame 5 (8) with induction depth 5
[2017-07-17.14:17:37] pdkind: pushed 15 of 20
[2017-07-17.14:17:37] pdkind: working on induction frame 6 (9) with induction depth 6
[2017-07-17.14:17:41] pdkind: pushed 25 of 31
[2017-07-17.14:17:41] pdkind: working on induction frame 7 (17) with induction depth 7
[2017-07-17.14:17:43] pdkind: pushed 18 of 21
[2017-07-17.14:17:43] pdkind: working on induction frame 8 (13) with induction depth 8
[2017-07-17.14:17:51] pdkind: pushed 21 of 22
[2017-07-17.14:17:51] pdkind: working on induction frame 9 (19) with induction depth 9
[2017-07-17.14:18:16] pdkind: pushed 19 of 23
[2017-07-17.14:18:16] pdkind: working on induction frame 12 (16) with induction depth 10
[2017-07-17.14:18:31] pdkind: pushed 31 of 37
[2017-07-17.14:18:31] pdkind: working on induction frame 13 (24) with induction depth 11
[2017-07-17.14:18:43] pdkind: pushed 40 of 43
[2017-07-17.14:18:44] pdkind: working on induction frame 14 (36) with induction depth 12
[2017-07-17.14:19:14] pdkind: pushed 52 of 54
[2017-07-17.14:19:14] pdkind: working on induction frame 15 (41) with induction depth 13
[2017-07-17.14:19:18] pdkind: pushed 41 of 41
[2017-07-17.14:19:18] pdkind: search done: valid
valid
```
