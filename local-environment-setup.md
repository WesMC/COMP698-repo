# How to setup for COMP 698

First what we need to do is blame whomever wanted us to document our own setup
because a workplace should be able to help it's employees to setup correctly. I
mean seriously, what workplace doesn't help their employees setup so that they
don't make a huge mistake.

The actual first thing we want to do is to write a list of all the technologies
that we are going to be working with. In this class we need:

 * Bash Shell
 * Git and Github account
 * Docker

# Setup Git and Github

You should be able to do this on your own. But in case, open a command terminal
and type in:

`sudo dnf install git`

When prompted, say yes to install. Be smart, think with common sense. Next is to
setup a github account. Google `github.com` and follow the steps to setup that.

# Docker

Docker, according from their own website:

>Docker containers wrap a piece of software in a complete filesystem that contains everything needed to run: code, runtime, system tools, system libraries – anything that can be installed on a server. This guarantees that the software will always run the same, regardless of its environment.

This is our software for virtualization. Luckily for us Fedora users, it can be installed very similarly though:

`sudo dnf install docker`

Once installed, you want to run the command `sudo docker run hello-world` to confirm that you have it installed and running correctly. After you have that confirmed, you want to run the command `sudo docker run -it ubuntu:xenial /bin/bash` to setup the container we're going to use.
