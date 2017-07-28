## Overview

The lab environment consists of two virtual machines, accessible via the
following local IP addresses.

* _deploy_: **`192.168.122.100`**
* _alice_: **`192.168.122.111`**

The _deploy_ node is the only machine with a publicly available IP address.
Your terminal automatically connects to _deploy_.

When you connect to _deploy_, you automatically enter a `screen` session.
`screen` is a terminal multiplexer that, among other things, allows you
reconnect to a previous session.  This means that if you close the browser page
and return to the exercise later on, your session, including scrollback and
command history, will be exactly as you left it.

## SSH Between Nodes

You can use SSH from _deploy_ to hop to the other nodes.  To connect to
_alice_, follow these instructions using the terminal below:

1. From the _deploy_ node (it's where you start out), SSH into _alice_ by
   entering:

        $ ssh alice

2. To confirm the authenticity of the host, enter "yes" at the prompt.

3. Type the following to return to `deploy`:

        $ exit

> Note: Whenever specific instructions are given as the ones above, do your
> best to execute them as stated.  You will be graded on the results.
