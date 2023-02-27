Web Stack Debugging
This project contains tasks for learning about how to debug web stacks.

Tasks To Complete
 0. Strace is your friend
0-strace_is_your_friend.pp contains a Puppet manifest that fixes a faulty server.
Info:
Using strace, find out why Apache is returning a 500 error. Once you find the issue, fix it and then automate it using Puppet (instead of using Bash as you were previously doing).
HINT:
strace can attach to a current running process.
You can use tmux to run strace in one window and curl in another one.
