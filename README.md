# CSEC 504 HW #2 Reference Implementation

__This repo is only relevant to students enrolled in the CSEC 504 (Fall 2017/18) course.__

## About

This is my implementation of the CSEC 504 HW #2 assignment. It complies with the specifications that were defined for the assignment.

It is important to note that this is only one of many possible solutions to the problems given. Your solution might look nothing like this one, and that is perfectly fine, provided that the functionality complies with the specifications.

There are a couple of things to point out:

1. The required output of your code is in the form of files (i.e. `hosts.txt` and `login.txt`). Nothing is said about displaying any progress through `stdout`. I decided to add some progress indication to make it easier for you to understand what’s going on in the code. It is totally fine if your code doesn’t show any progress.
2. Notwithstanding the progress indication, I tried to make the code as straightforward and to-the-point as much as possible. For example, a better implementation would feature more input validation and more robust error handling. However, adding code to deal with contingencies can make it more difficult to follow the core logic.

Basically, this implementation tries to match the specs. (Almost) nothing more and (hopefully) nothing less.

You are more than welcome to open issues to start discussions on the code, provide feedback, or ask questions about it.

## Screencast

You can watch the screencast by clicking on the link below.

[![asciicast](https://asciinema.org/a/9jAp3nKcOfLYprwtoSDejrAwq.png)](https://asciinema.org/a/9jAp3nKcOfLYprwtoSDejrAwq)

What you do not see in this screencast is, after `arpattack` is ready, the following command is executed on `10.10.10.20`:

    $ curl http://csec504:homework@10.10.10.30/