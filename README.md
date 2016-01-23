# SYNOPSIS

outthentic smoke tests for telegraf

# Check list

TDB

# Sample Output

    /tmp/.outthentic/13304/home/vagrant/outth-telegraf/cpu-metric/story.t ...
    ok 1 - perl /home/vagrant/outth-telegraf/modules/make-config/story.pl succeeded
    ok 2 - stdout saved to /tmp/.outthentic/13304/I83Gybg4Ma
    ok 3 - output match 'OK'
    ok 4 - perl /home/vagrant/outth-telegraf/cpu-metric/story.pl succeeded
    ok 5 - stdout saved to /tmp/.outthentic/13304/WDXaZ5PaxR
    ok 6 - output match 'cpu'
    ok 7 - output match /Plugin:\s+cpu,\s+Collection/
    1..7
    ok
    /tmp/.outthentic/13304/home/vagrant/outth-telegraf/usage-mysql/story.t ..
    ok 1 - perl /home/vagrant/outth-telegraf/usage-mysql/story.pl succeeded
    ok 2 - stdout saved to /tmp/.outthentic/13304/LmTxmOT99_
    ok 3 - output match 'Read metrics from one or many mysql servers'
    1..3
    ok
    /tmp/.outthentic/13304/home/vagrant/outth-telegraf/version/story.t ......
    ok 1 - perl /home/vagrant/outth-telegraf/version/story.pl succeeded
    ok 2 - stdout saved to /tmp/.outthentic/13304/P7goW5t2B4
    ok 3 - output match /Telegraf - Version \S+/
    ok 4 - 'Telegraf - Version 0.2.4' match /Version (\S+)/
    1..4
    ok
    All tests successful.
    Files=3, Tests=14,  1 wallclock secs ( 0.02 usr  0.00 sys +  0.19 cusr  0.05 csys =  0.26 CPU)
    Result: PASS
    


# Author

Alexey Melezhik
    
