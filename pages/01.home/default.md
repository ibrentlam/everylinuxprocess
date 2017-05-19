---
title: Home
---
#The Backstory#
I've been a Unix SysAdmin since 1982. Life was simple back then. If you did a ```ps```, you'd see ```init```, a few ```gettys```, ```cron```, not much more. It was a small, tight-knit family. We knew everybody. 

The other day while teaching an Intro to Linux class, I did a ```ps```
. There were over 200 processes listed. I looked through them and didn't see many familiar old faces. In fact, I figured I knew only about half of what was running. This was unacceptable. 

Hence the idea for this site. I just installed a default version of Ununtu 16.04, and did a ```ps auxf``` on May 16, 2017. Below you'll see the results of that and I'll attempt to annotate each and every process present. Wish me luck. 

```
USER       PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root         2  0.0  0.0      0     0 ?        S    May10   0:00 [[kthreadd](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)]
root         4  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/0:0H]
root         6  0.0  0.0      0     0 ?        S    May10   0:00  \_ [ksoftirqd/0]
root         7  0.0  0.0      0     0 ?        S    May10   0:06  \_ [rcu_sched]
root         8  0.0  0.0      0     0 ?        S    May10   0:00  \_ [rcu_bh]
root         9  0.0  0.0      0     0 ?        S    May10   0:00  \_ [migration/0]
root        10  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [lru-add-drain]
root        11  0.0  0.0      0     0 ?        S    May10   0:00  \_ [watchdog/0]
root        12  0.0  0.0      0     0 ?        S    May10   0:00  \_ [cpuhp/0]
root        13  0.0  0.0      0     0 ?        S    May10   0:00  \_ [cpuhp/1]
root        14  0.0  0.0      0     0 ?        S    May10   0:00  \_ [watchdog/1]
root        15  0.0  0.0      0     0 ?        S    May10   0:00  \_ [migration/1]
root        16  0.0  0.0      0     0 ?        S    May10   0:03  \_ [ksoftirqd/1]
root        18  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/1:0H]
root        19  0.0  0.0      0     0 ?        S    May10   0:00  \_ [cpuhp/2]
root        20  0.0  0.0      0     0 ?        S    May10   0:00  \_ [watchdog/2]
root        21  0.0  0.0      0     0 ?        S    May10   0:00  \_ [migration/2]
root        22  0.0  0.0      0     0 ?        S    May10   0:00  \_ [ksoftirqd/2]
root        24  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/2:0H]
root        25  0.0  0.0      0     0 ?        S    May10   0:00  \_ [cpuhp/3]
root        26  0.0  0.0      0     0 ?        S    May10   0:00  \_ [watchdog/3]
root        27  0.0  0.0      0     0 ?        S    May10   0:00  \_ [migration/3]
root        28  0.0  0.0      0     0 ?        S    May10   0:00  \_ [ksoftirqd/3]
root        30  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/3:0H]
root        31  0.0  0.0      0     0 ?        S    May10   0:00  \_ [kdevtmpfs]
root        32  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [netns]
root        33  0.0  0.0      0     0 ?        S    May10   0:00  \_ [khungtaskd]
root        34  0.0  0.0      0     0 ?        S    May10   0:00  \_ [oom_reaper]
root        35  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [writeback]
root        36  0.0  0.0      0     0 ?        S    May10   0:00  \_ [kcompactd0]
root        37  0.0  0.0      0     0 ?        SN   May10   0:00  \_ [ksmd]
root        38  0.0  0.0      0     0 ?        SN   May10   0:02  \_ [khugepaged]
root        39  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [crypto]
root        40  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kintegrityd]
root        41  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root        42  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kblockd]
root        43  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [ata_sff]
root        44  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [md]
root        45  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [devfreq_wq]
root        46  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [watchdogd]
root        52  0.0  0.0      0     0 ?        S    May10   0:00  \_ [kauditd]
root        53  0.0  0.0      0     0 ?        S    May10   0:00  \_ [kswapd0]
root        54  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [vmstat]
root        55  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root        56  0.0  0.0      0     0 ?        S    May10   0:00  \_ [ecryptfs-kthrea]
root        96  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kthrotld]
root        97  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [acpi_thermal_pm]
root        98  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root        99  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       100  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       101  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       102  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       103  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       104  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       105  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       109  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [ipv6_addrconf]
root       130  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [charger_manager]
root       172  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [firewire]
root       173  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [firewire_ohci]
root       176  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_0]
root       177  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_0]
root       178  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_1]
root       179  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_1]
root       180  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_2]
root       181  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_2]
root       182  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_3]
root       183  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_3]
root       184  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_4]
root       185  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_4]
root       186  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_5]
root       187  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_5]
root       192  0.0  0.0      0     0 ?        S    May10   0:00  \_ [i915/signal:0]
root       193  0.0  0.0      0     0 ?        S    May10   0:00  \_ [i915/signal:2]
root       194  0.0  0.0      0     0 ?        S    May10   0:00  \_ [scsi_eh_6]
root       195  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [scsi_tmf_6]
root       196  0.0  0.0      0     0 ?        S    May10   0:13  \_ [usb-storage]
root       198  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       200  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       201  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       203  0.0  0.0      0     0 ?        S<   May10   0:03  \_ [kworker/0:1H]
root       204  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root       207  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/1:1H]
root       221  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [kworker/2:1H]
root       224  0.0  0.0      0     0 ?        S<   May10   0:01  \_ [kworker/3:1H]
root       230  0.0  0.0      0     0 ?        S    May10   0:01  \_ [jbd2/sda1-8]
root       231  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [ext4-rsv-conver]
root     14372  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root     14374  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [xfsalloc]
root     14376  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [xfs_mru_cache]
root     14385  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsIO]
root     14386  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsCommit]
root     14387  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsCommit]
root     14388  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsCommit]
root     14389  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsCommit]
root     14390  0.0  0.0      0     0 ?        S    May10   0:00  \_ [jfsSync]
root     14427  0.0  0.0      0     0 ?        S<   May10   0:00  \_ [bioset]
root      4805  0.0  0.0      0     0 ?        S    May15   0:00  \_ [kworker/2:1]
root      4806  0.0  0.0      0     0 ?        S    May15   0:00  \_ [kworker/0:1]
root      6770  0.0  0.0      0     0 ?        S    07:35   0:00  \_ [kworker/0:0]
root      6772  0.0  0.0      0     0 ?        S    07:35   0:00  \_ [kworker/3:1]
root      6784  0.0  0.0      0     0 ?        S    07:35   0:00  \_ [kworker/1:2]
root      6881  0.0  0.0      0     0 ?        S    08:01   0:00  \_ [kworker/1:1]
root      7041  0.0  0.0      0     0 ?        S    08:48   0:00  \_ [kworker/3:2]
root      7199  0.0  0.0      0     0 ?        S    09:54   0:00  \_ [kworker/2:0]
root      7274  0.0  0.0      0     0 ?        S    10:28   0:00  \_ [kworker/u8:2]
root      7415  0.0  0.0      0     0 ?        S    11:30   0:00  \_ [kworker/u8:1]
root      7477  0.0  0.0      0     0 ?        S    11:59   0:00  \_ [kworker/u8:0]
root      7488  0.0  0.0      0     0 ?        S    12:04   0:00  \_ [kworker/1:0]
root      7489  0.0  0.0      0     0 ?        S    12:04   0:00  \_ [kworker/1:3]
root      7531  0.0  0.0      0     0 ?        S    12:04   0:00  \_ [kworker/2:2]
root      7610  0.0  0.0      0     0 ?        S    12:05   0:00  \_ [kworker/3:0]
root      7638  0.0  0.0      0     0 ?        S    12:05   0:00  \_ [kworker/0:2]
root         1  0.0  0.1 205064  7520 ?        Ss   May10   0:06 /lib/systemd/systemd --system --deserialize 16
root       265  0.0  0.1  59676  6256 ?        Ss   May10   0:03 /lib/systemd/systemd-journald
avahi      714  0.0  0.0  47344  3292 ?        Ss   May10   0:01 avahi-daemon: running [learn.local]
avahi      722  0.0  0.0  47180   356 ?        S    May10   0:00  \_ avahi-daemon: chroot helper
message+   720  0.0  0.1  46920  5816 ?        Ss   May10   0:07 /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
root       724  0.0  0.4 478796 17020 ?        Ssl  May10   0:00 /usr/sbin/NetworkManager --no-daemon
root      1031  0.0  0.0  16116  3676 ?        S    May10   0:00  \_ /sbin/dhclient -d -q -sf /usr/lib/NetworkManager/nm-dhcp-helper -pf /var/run/dhclient-enp0s25.pid -lf /var/lib/NetworkManager/dhclient-cec8792c-e39b-3fc0-81f8-516f817d916a-enp0s25.lease -cf /var/lib/NetworkManager/dhclient-enp0s25.conf enp0s25
root       730  0.0  0.2 305492  8468 ?        Ssl  May10   0:03 /usr/lib/accountsservice/accounts-daemon
root       731  0.0  0.2 349200 11276 ?        Ssl  May10   0:00 /usr/sbin/ModemManager
root       732  0.0  0.2 1020604 11532 ?       Ssl  May10   0:01 /usr/sbin/repowerd
whoopsie   733  0.0  0.3 393804 13740 ?        Ssl  May10   0:00 /usr/bin/whoopsie -f
root       736  0.0  0.1  48336  6652 ?        Ss   May10   0:00 /lib/systemd/systemd-logind
root       744  0.0  0.0  38208  3088 ?        Ss   May10   0:00 /usr/sbin/cron -f
root       751  0.0  0.0   4388  1316 ?        Ss   May10   0:00 /usr/sbin/acpid
syslog     752  0.0  0.0 256416  3648 ?        Ssl  May10   0:00 /usr/sbin/rsyslogd -n
root       794  0.0  0.3 361396 12220 ?        Ssl  May10   0:00 /usr/lib/upower/upowerd
root       801  0.0  0.2 316764 11764 ?        Ssl  May10   0:02 /usr/lib/policykit-1/polkitd --no-debug
root       827  0.0  0.0  19492   244 ?        Ss   May10   0:12 /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
root       974  0.0  0.2 305608  8476 ?        SLsl May10   0:00 /usr/sbin/lightdm
root     25593  0.0  1.9 440836 77868 tty7     Ssl+ May11   2:03  \_ /usr/lib/xorg/Xorg -core :0 -seat seat0 -auth /var/run/lightdm/root/:0 -nolisten tcp vt7 -novtswitch
root     25724  0.0  0.1 243692  6616 ?        Sl   May11   0:00  \_ lightdm --session-child 12 19
brent    25759  0.0  0.0   4496  1660 ?        Ss   May11   0:00      \_ /bin/sh /usr/lib/gnome-session/run-systemd-session ubuntu-session.target
brent    25841  0.0  0.0  11128   312 ?        Ss   May11   0:00          \_ /usr/bin/ssh-agent /usr/bin/im-launch /usr/lib/gnome-session/run-systemd-session ubuntu-session.target
brent    25954  0.0  0.0  48084  2088 ?        S    May11   0:00          \_ systemctl --user start --wait ubuntu-session.target
root      1019  0.0  0.0  23084  1900 tty1     Ss+  May10   0:00 /sbin/agetty --noclear tty1 linux
colord    1091  0.0  0.4 950280 16900 ?        Ssl  May10   0:00 /usr/lib/colord/colord
rtkit     1182  0.0  0.0 185928  3064 ?        SNsl May10   0:02 /usr/lib/rtkit/rtkit-daemon
root      1215  0.0  0.1 261024  4680 ?        Sl   May10   0:00 /usr/lib/x86_64-linux-gnu/unity-greeter-session-broadcast/unity-greeter-session-broadcast-service
brent     1334  0.0  0.1  65420  7060 ?        Ss   May10   0:00 /lib/systemd/systemd --user
brent     1335  0.0  0.0 236772  2148 ?        S    May10   0:00  \_ (sd-pam)
brent     1375  0.0  0.1  46280  5092 ?        Ss   May10   0:07  \_ /usr/bin/dbus-daemon --session --address=systemd: --nofork --nopidfile --systemd-activation
brent     1543  0.0  0.2 290732  8772 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfsd
brent     1550  0.0  0.2 431092  9572 ?        Sl   May10   0:00  \_ /usr/lib/gvfs/gvfsd-fuse /run/user/1000/gvfs -f -o big_writes
brent     1603  0.0  0.1 187608  7028 ?        Sl   May10   0:00  \_ /usr/lib/dconf/dconf-service
brent     1884  0.0  0.7 361832 28700 ?        Sl   May10   0:00  \_ /usr/bin/python3 /usr/bin/libertined --cache-output
brent     1889  0.0  0.6 1282644 26536 ?       Ssl  May10   0:00  \_ /usr/lib/evolution/evolution-source-registry
brent     1905  0.0  0.2 314964 10172 ?        Ssl  May10   0:02  \_ /usr/lib/gvfs/gvfs-udisks2-volume-monitor
brent     1932  0.0  0.2 419908  9412 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfs-afc-volume-monitor
brent     1937  0.0  0.1 273568  4660 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfs-goa-volume-monitor
brent     1941  0.0  0.1 273600  5304 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfs-mtp-volume-monitor
brent     1945  0.0  0.1 285800  5840 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfs-gphoto2-volume-monitor
brent     1952  0.0  0.2 382132 11360 ?        Sl   May10   0:00  \_ /usr/lib/gvfs/gvfsd-trash --spawner :1.7 /org/gtk/gvfs/exec_spaw/0
brent     2004  0.0  0.1 199960  7716 ?        Ssl  May10   0:00  \_ /usr/lib/gvfs/gvfsd-metadata
brent     2064  0.0  0.2 445604 10720 ?        Ssl  May10   0:00  \_ /usr/bin/zeitgeist-daemon
brent     2071  0.0  0.4 329840 17016 ?        Ssl  May10   0:00  \_ /usr/lib/zeitgeist/zeitgeist/zeitgeist-fts
brent     2101  0.0  0.4 675592 18828 ?        Sl   May10   0:03  \_ /usr/lib/x86_64-linux-gnu/unity-scope-home/unity-scope-home
brent     2111  0.0  0.7 667576 28744 ?        Sl   May10   0:04  \_ /usr/bin/unity-scope-loader applications/applications.scope applications/scopes.scope commands.scope
brent     2113  0.0  0.4 729080 16916 ?        Sl   May10   0:00  \_ /usr/lib/x86_64-linux-gnu/unity-lens-files/unity-files-daemon
brent    24239  0.0  0.5 379772 23604 ?        Sl   May11   0:00  \_ /usr/bin/python3 /usr/share/unity-scopes/shotwell/unity_shotwell_daemon.py
brent    24293  0.0  0.2 423468 11932 ?        Sl   May11   0:02  \_ /usr/lib/x86_64-linux-gnu/unity-lens-video/unity-video-lens-daemon
brent    25969  0.0  0.2 388120  8552 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-power/indicator-power-service
brent    25971  0.0  0.8 1011080 32368 ?       Ssl  May11   0:04  \_ /usr/lib/x86_64-linux-gnu/indicator-datetime/indicator-datetime-service
brent    25972  0.0  0.6 570480 27952 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-printers/indicator-printers-service
brent    25973  0.0  0.3 419344 15660 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-application/indicator-application-service
brent    25977  0.0  0.8 609564 33472 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-keyboard/indicator-keyboard-service --use-gtk
brent    25979  0.0  0.2 661980  8900 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-session/indicator-session-service
brent    25980  0.0  0.2 388612  9560 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-messages/indicator-messages-service
brent    25981  0.0  0.3 962608 12648 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-sound/indicator-sound-service
brent    25983  0.0  0.2 367356 10172 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/indicator-bluetooth/indicator-bluetooth-service
brent    25984  0.0  0.2 175812 10220 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/hud/window-stack-bridge
brent    26009  0.0  0.8 1005396 34852 ?       Ssl  May11   0:08  \_ /usr/lib/unity-settings-daemon/unity-settings-daemon
brent    26012  0.0  0.7 469056 29020 ?        Ssl  May11   0:01  \_ /usr/lib/x86_64-linux-gnu/bamf/bamfdaemon
brent    26020  0.0  0.4 658560 16320 ?        Ssl  May11   0:00  \_ /usr/lib/gnome-session/gnome-session-binary --session=ubuntu
brent    26240  0.0  0.6 456660 24336 ?        Sl   May11   0:00  |   \_ /usr/lib/policykit-1-gnome/polkit-gnome-authentication-agent-1
brent    26241  0.0  0.8 693172 33120 ?        Sl   May11   0:00  |   \_ nm-applet
brent    26246  0.0  0.6 601996 24712 ?        Sl   May11   0:00  |   \_ /usr/lib/unity-settings-daemon/unity-fallback-mount-helper
brent    26249  0.0  1.5 905588 63660 ?        Sl   May11   0:05  |   \_ nautilus -n
brent    26257  0.0  9.4 1446692 380016 ?      SLl  May11   0:53  |   \_ /usr/bin/gnome-software --gapplication-service
brent    26323  0.0  0.5 539288 21020 ?        Sl   May11   0:02  |   \_ zeitgeist-datahub
brent    26352  0.0  0.6 555420 27540 ?        Sl   May11   0:02  |   \_ update-notifier
brent    26386  0.0  0.2 459796  8948 ?        Sl   May11   0:00  |   \_ /usr/lib/x86_64-linux-gnu/deja-dup/deja-dup-monitor
brent    26041  0.0  0.2 364872  8536 ?        Ssl  May11   0:00  \_ /usr/lib/at-spi2-core/at-spi-bus-launcher
brent    26064  0.0  0.0  45300  3992 ?        S    May11   0:00  |   \_ /usr/bin/dbus-daemon --config-file=/usr/share/defaults/at-spi2/accessibility.conf --nofork --print-address 3
brent    26073  0.0  0.2 1165468 11236 ?       S<l  May11   0:00  \_ /usr/bin/pulseaudio --start --log-target=syslog
brent    26075  0.0  0.1 216060  5280 ?        Sl   May11   0:00  \_ /usr/lib/at-spi2-core/at-spi2-registryd --use-gnome-session
brent    26127  0.0  0.8 878932 34588 ?        Ssl  May11   0:00  \_ /usr/lib/evolution/evolution-calendar-factory
brent    26142  0.0  0.6 884896 24772 ?        Sl   May11   0:00  |   \_ /usr/lib/evolution/evolution-calendar-factory-subprocess --factory contacts --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.Calendarx26127x2 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/Calendar/26127/2
brent    26163  0.0  0.5 857536 23492 ?        Sl   May11   0:00  |   \_ /usr/lib/evolution/evolution-calendar-factory-subprocess --factory local --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.Calendarx26127x3 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/Calendar/26127/3
brent    26138  0.1  2.7 1421196 111276 ?      Ssl  May11  14:46  \_ /usr/bin/compiz
brent    26151  0.0  0.9 876740 36660 ?        Ssl  May11   0:10  \_ /usr/lib/x86_64-linux-gnu/unity/unity-panel-service
brent    26161  0.0  0.5 731208 22772 ?        Ssl  May11   0:00  \_ /usr/lib/evolution/evolution-addressbook-factory
brent    26174  0.0  0.5 875208 22660 ?        Sl   May11   0:00  |   \_ /usr/lib/evolution/evolution-addressbook-factory-subprocess --factory local --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.AddressBookx26161x2 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/AddressBook/26161/2
brent    26300  0.0  0.5 427000 21356 ?        Ssl  May11   0:00  \_ /usr/lib/x86_64-linux-gnu/hud/hud-service
brent     7616  0.9  0.9 704928 36600 ?        Ssl  12:05   0:00  \_ /usr/lib/gnome-terminal/gnome-terminal-server
brent     7626  0.0  0.1  29580  5120 pts/0    Ss   12:05   0:00      \_ bash
brent     7655  0.0  0.0  47020  3640 pts/0    R+   12:06   0:00          \_ ps auxf
brent     1460  0.0  0.2 376796  9256 ?        Ssl  May10   0:01 /usr/bin/ibus-daemon --daemonize --xim --address unix:tmpdir=/tmp/ibus
brent     1562  0.0  0.2 295732  8168 ?        Sl   May10   0:00  \_ /usr/lib/ibus/ibus-dconf
brent     1611  0.0  0.1 219872  7796 ?        Sl   May10   0:00  \_ /usr/lib/ibus/ibus-engine-simple
root      1914  0.0  0.3 393600 12272 ?        Ssl  May10   1:07 /usr/lib/udisks2/udisksd --no-debug
root      2033  0.0  1.4 567900 58116 ?        Ssl  May10   0:05 /usr/lib/fwupd/fwupd
root      2212  0.0  0.0 182284   772 ?        Ss   May10   0:06 gpg-agent --homedir /var/lib/fwupd/gnupg --use-standard-socket --daemon
root      2426  0.0  0.3 331772 14704 ?        Ssl  May10   0:00 /usr/lib/packagekit/packagekitd
brent    25754  0.0  0.1 221504  6744 ?        Sl   May11   0:00 /usr/bin/gnome-keyring-daemon --daemonize --login
systemd+  9131  0.0  0.1  50120  5548 ?        Ss   May14   0:00 /lib/systemd/systemd-resolved
systemd+  9146  0.0  0.1 125564  4224 ?        Ssl  May14   0:00 /lib/systemd/systemd-timesyncd
root      9685  0.0  0.4 573320 19620 ?        Ssl  May14   0:04 /usr/lib/snapd/snapd
root      9790  0.0  0.0  46768  4004 ?        Ss   May14   0:00 /lib/systemd/systemd-udevd
root      6773  0.0  0.2 105604  8348 ?        Ss   07:35   0:00 /usr/sbin/cupsd -l
lp        6776  0.0  0.1  83884  5976 ?        S    07:35   0:00  \_ /usr/lib/cups/notifier/dbus dbus://
lp        6819  0.0  0.1  83884  5844 ?        S    07:35   0:00  \_ /usr/lib/cups/notifier/dbus dbus://
root      6774  0.0  0.2 298328 10884 ?        Ssl  07:35   0:00 /usr/sbin/cups-browsed
```
