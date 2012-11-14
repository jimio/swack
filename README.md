# swack - the security swiss army knife
=====================================

ever find yourself jumping into a terminal, then grepping through your bash
history to try and figure out the syntax for that obscure command you always
run? or accidentally pasting some sensitive information into one of those
'decode your encoded blob here' websites?

enter swack, the 'security swiss army knife' (swak was already claimed, and
it turns out that swack is slang for intercourse, so.. just as well). this quick
command attempts to be a one-stop-shop for all of your daily security needs.

to install without building:
    gem install swack

when aliased to 's', you get this super-handy interface:

    s <your_data_here>

when invoked without paramters, swack will spit out a bunch of helpful, 
syntactically-correct strings that you'll probably use at some point or another.
when you pass an argument, it tries to do a whole bunch of helpful stuff on it.

TODOs:
-check certificates on URLs (expiration, subject info, etc )
-dump http headers from responses
-format things nicely
-handy-dandy script to build & install & alias