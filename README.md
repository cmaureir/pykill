# pykill

Kill processes more "easily".

## How?

Just a couple of `subprocess` call, and a couple of `for-loop`
nothing outside this world.

## Why?

I was tired of doing a:

    ps aux | grep <pattern>
    kill -9 <PID>

every time I wanted to kill some process, so I decided
to write a simple script to do a:

    pykill <pattern>
    <input the number of the process (not pid) and enter>


## Seriously...why?

Boredom?
