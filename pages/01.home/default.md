---
title: Home
---
#The Backstory#
I've been a Unix SysAdmin since 1982. Life was simple back then. If you did a ```ps```, you'd see ```init```, a few ```gettys```, ```cron```, not much more. It was a small, tight-knit family. We knew everybody. 

The other day while teaching an Intro to Linux class, I did a ```ps```
. There were over 200 processes listed. I looked through them and didn't see many familiar old faces. In fact, I figured I knew only about half of what was running. This was unacceptable. 

Hence the idea for this site. I just installed a default version of Ununtu 16.04, and did a ```ps auxf``` on May 16, 2017. Below you'll see the results of that and I'll attempt to annotate each and every process present. Wish me luck. 

USER       PID  COMMAND
root         2  [kthreadd]
root         4   \_ [kworker/0:0H]
root         6   \_ [ksoftirqd/0]
root         7   \_ [rcu_sched]
root         8   \_ [rcu_bh]
root         9   \_ [migration/0]
root        10   \_ [lru-add-drain]
root        11   \_ [watchdog/0]
root        12   \_ [cpuhp/0]
root        13   \_ [cpuhp/1]
root        14   \_ [watchdog/1]
root        15   \_ [migration/1]
root        16   \_ [ksoftirqd/1]
root        18   \_ [kworker/1:0H]
root        19   \_ [cpuhp/2]
root        20   \_ [watchdog/2]
root        21   \_ [migration/2]
root        22   \_ [ksoftirqd/2]
root        24   \_ [kworker/2:0H]
root        25   \_ [cpuhp/3]
root        26   \_ [watchdog/3]
root        27   \_ [migration/3]
root        28   \_ [ksoftirqd/3]
root        30   \_ [kworker/3:0H]
root        31   \_ [kdevtmpfs]
root        32   \_ [netns]
root        33   \_ [khungtaskd]
root        34   \_ [oom_reaper]
root        35   \_ [writeback]
root        36   \_ [kcompactd0]
root        37   \_ [ksmd]
root        38   \_ [khugepaged]
root        39   \_ [crypto]
root        40   \_ [kintegrityd]
root        41   \_ [bioset]
root        42   \_ [kblockd]
root        43   \_ [ata_sff]
root        44   \_ [md]
root        45   \_ [devfreq_wq]
root        46   \_ [watchdogd]
root        52   \_ [kauditd]
root        53   \_ [kswapd0]
root        54   \_ [vmstat]
root        55   \_ [bioset]
root        56   \_ [ecryptfs-kthrea]
root        96   \_ [kthrotld]
root        97   \_ [acpi_thermal_pm]
root        98   \_ [bioset]
root        99   \_ [bioset]
root       100   \_ [bioset]
root       101   \_ [bioset]
root       102   \_ [bioset]
root       103   \_ [bioset]
root       104   \_ [bioset]
root       105   \_ [bioset]
root       109   \_ [ipv6_addrconf]
root       130   \_ [charger_manager]
root       172   \_ [firewire]
root       173   \_ [firewire_ohci]
root       176   \_ [scsi_eh_0]
root       177   \_ [scsi_tmf_0]
root       178   \_ [scsi_eh_1]
root       179   \_ [scsi_tmf_1]
root       180   \_ [scsi_eh_2]
root       181   \_ [scsi_tmf_2]
root       182   \_ [scsi_eh_3]
root       183   \_ [scsi_tmf_3]
root       184   \_ [scsi_eh_4]
root       185   \_ [scsi_tmf_4]
root       186   \_ [scsi_eh_5]
root       187   \_ [scsi_tmf_5]
root       192   \_ [i915/signal:0]
root       193   \_ [i915/signal:2]
root       194   \_ [scsi_eh_6]
root       195   \_ [scsi_tmf_6]
root       196   \_ [usb-storage]
root       198   \_ [bioset]
root       200   \_ [bioset]
root       201   \_ [bioset]
root       203   \_ [kworker/0:1H]
root       204   \_ [bioset]
root       207   \_ [kworker/1:1H]
root       221   \_ [kworker/2:1H]
root       224   \_ [kworker/3:1H]
root       230   \_ [jbd2/sda1-8]
root       231   \_ [ext4-rsv-conver]
root     14372   \_ [bioset]
root     14374   \_ [xfsalloc]
root     14376   \_ [xfs_mru_cache]
root     14385   \_ [jfsIO]
root     14386   \_ [jfsCommit]
root     14387   \_ [jfsCommit]
root     14388   \_ [jfsCommit]
root     14389   \_ [jfsCommit]
root     14390   \_ [jfsSync]
root     14427   \_ [bioset]
root      4805   \_ [kworker/2:1]
root      4806   \_ [kworker/0:1]
root      6770   \_ [kworker/0:0]
root      6772   \_ [kworker/3:1]
root      6784   \_ [kworker/1:2]
root      6881   \_ [kworker/1:1]
root      7041   \_ [kworker/3:2]
root      7199   \_ [kworker/2:0]
root      7274   \_ [kworker/u8:2]
root      7415   \_ [kworker/u8:1]
root      7477   \_ [kworker/u8:0]
root      7488   \_ [kworker/1:0]
root      7489   \_ [kworker/1:3]
root      7531   \_ [kworker/2:2]
root      7610   \_ [kworker/3:0]
root      7638   \_ [kworker/0:2]
root         1  /lib/systemd/systemd --system --deserialize 16
root       265  /lib/systemd/systemd-journald
avahi      714  avahi-daemon: running [learn.local]
avahi      722   \_ avahi-daemon: chroot helper
message+   720  /usr/bin/dbus-daemon --system --address=systemd: --nofork --nopidfile --systemd-activation
root       724  /usr/sbin/NetworkManager --no-daemon
root      1031   \_ /sbin/dhclient -d -q -sf /usr/lib/NetworkManager/nm-dhcp-helper -pf /var/run/dhclient-enp0s25.pid -lf /var/lib/NetworkManager/dhclient-cec8792c-e39b-3fc0-81f8-516f817d916a-enp0s25.lease -cf /var/lib/NetworkManager/dhclient-enp0s25.conf enp0s25
root       730  /usr/lib/accountsservice/accounts-daemon
root       731  /usr/sbin/ModemManager
root       732  /usr/sbin/repowerd
whoopsie   733  /usr/bin/whoopsie -f
root       736  /lib/systemd/systemd-logind
root       744  /usr/sbin/cron -f
root       751  /usr/sbin/acpid
syslog     752  /usr/sbin/rsyslogd -n
root       794  /usr/lib/upower/upowerd
root       801  /usr/lib/policykit-1/polkitd --no-debug
root       827  /usr/sbin/irqbalance --pid=/var/run/irqbalance.pid
root       974  /usr/sbin/lightdm
root     25593   \_ /usr/lib/xorg/Xorg -core :0 -seat seat0 -auth /var/run/lightdm/root/:0 -nolisten tcp vt7 -novtswitch
root     25724   \_ lightdm --session-child 12 19
brent    25759       \_ /bin/sh /usr/lib/gnome-session/run-systemd-session ubuntu-session.target
brent    25841           \_ /usr/bin/ssh-agent /usr/bin/im-launch /usr/lib/gnome-session/run-systemd-session ubuntu-session.target
brent    25954           \_ systemctl --user start --wait ubuntu-session.target
root      1019  /sbin/agetty --noclear tty1 linux
colord    1091  /usr/lib/colord/colord
rtkit     1182  /usr/lib/rtkit/rtkit-daemon
root      1215  /usr/lib/x86_64-linux-gnu/unity-greeter-session-broadcast/unity-greeter-session-broadcast-service
brent     1334  /lib/systemd/systemd --user
brent     1335   \_ (sd-pam)
brent     1375   \_ /usr/bin/dbus-daemon --session --address=systemd: --nofork --nopidfile --systemd-activation
brent     1543   \_ /usr/lib/gvfs/gvfsd
brent     1550   \_ /usr/lib/gvfs/gvfsd-fuse /run/user/1000/gvfs -f -o big_writes
brent     1603   \_ /usr/lib/dconf/dconf-service
brent     1884   \_ /usr/bin/python3 /usr/bin/libertined --cache-output
brent     1889   \_ /usr/lib/evolution/evolution-source-registry
brent     1905   \_ /usr/lib/gvfs/gvfs-udisks2-volume-monitor
brent     1932   \_ /usr/lib/gvfs/gvfs-afc-volume-monitor
brent     1937   \_ /usr/lib/gvfs/gvfs-goa-volume-monitor
brent     1941   \_ /usr/lib/gvfs/gvfs-mtp-volume-monitor
brent     1945   \_ /usr/lib/gvfs/gvfs-gphoto2-volume-monitor
brent     1952   \_ /usr/lib/gvfs/gvfsd-trash --spawner :1.7 /org/gtk/gvfs/exec_spaw/0
brent     2004   \_ /usr/lib/gvfs/gvfsd-metadata
brent     2064   \_ /usr/bin/zeitgeist-daemon
brent     2071   \_ /usr/lib/zeitgeist/zeitgeist/zeitgeist-fts
brent     2101   \_ /usr/lib/x86_64-linux-gnu/unity-scope-home/unity-scope-home
brent     2111   \_ /usr/bin/unity-scope-loader applications/applications.scope applications/scopes.scope commands.scope
brent     2113   \_ /usr/lib/x86_64-linux-gnu/unity-lens-files/unity-files-daemon
brent    24239   \_ /usr/bin/python3 /usr/share/unity-scopes/shotwell/unity_shotwell_daemon.py
brent    24293   \_ /usr/lib/x86_64-linux-gnu/unity-lens-video/unity-video-lens-daemon
brent    25969   \_ /usr/lib/x86_64-linux-gnu/indicator-power/indicator-power-service
brent    25971   \_ /usr/lib/x86_64-linux-gnu/indicator-datetime/indicator-datetime-service
brent    25972   \_ /usr/lib/x86_64-linux-gnu/indicator-printers/indicator-printers-service
brent    25973   \_ /usr/lib/x86_64-linux-gnu/indicator-application/indicator-application-service
brent    25977   \_ /usr/lib/x86_64-linux-gnu/indicator-keyboard/indicator-keyboard-service --use-gtk
brent    25979   \_ /usr/lib/x86_64-linux-gnu/indicator-session/indicator-session-service
brent    25980   \_ /usr/lib/x86_64-linux-gnu/indicator-messages/indicator-messages-service
brent    25981   \_ /usr/lib/x86_64-linux-gnu/indicator-sound/indicator-sound-service
brent    25983   \_ /usr/lib/x86_64-linux-gnu/indicator-bluetooth/indicator-bluetooth-service
brent    25984   \_ /usr/lib/x86_64-linux-gnu/hud/window-stack-bridge
brent    26009   \_ /usr/lib/unity-settings-daemon/unity-settings-daemon
brent    26012   \_ /usr/lib/x86_64-linux-gnu/bamf/bamfdaemon
brent    26020   \_ /usr/lib/gnome-session/gnome-session-binary --session=ubuntu
brent    26240   |   \_ /usr/lib/policykit-1-gnome/polkit-gnome-authentication-agent-1
brent    26241   |   \_ nm-applet
brent    26246   |   \_ /usr/lib/unity-settings-daemon/unity-fallback-mount-helper
brent    26249   |   \_ nautilus -n
brent    26257   |   \_ /usr/bin/gnome-software --gapplication-service
brent    26323   |   \_ zeitgeist-datahub
brent    26352   |   \_ update-notifier
brent    26386   |   \_ /usr/lib/x86_64-linux-gnu/deja-dup/deja-dup-monitor
brent    26041   \_ /usr/lib/at-spi2-core/at-spi-bus-launcher
brent    26064   |   \_ /usr/bin/dbus-daemon --config-file=/usr/share/defaults/at-spi2/accessibility.conf --nofork --print-address 3
brent    26073   \_ /usr/bin/pulseaudio --start --log-target=syslog
brent    26075   \_ /usr/lib/at-spi2-core/at-spi2-registryd --use-gnome-session
brent    26127   \_ /usr/lib/evolution/evolution-calendar-factory
brent    26142   |   \_ /usr/lib/evolution/evolution-calendar-factory-subprocess --factory contacts --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.Calendarx26127x2 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/Calendar/26127/2
brent    26163   |   \_ /usr/lib/evolution/evolution-calendar-factory-subprocess --factory local --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.Calendarx26127x3 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/Calendar/26127/3
brent    26138   \_ /usr/bin/compiz
brent    26151   \_ /usr/lib/x86_64-linux-gnu/unity/unity-panel-service
brent    26161   \_ /usr/lib/evolution/evolution-addressbook-factory
brent    26174   |   \_ /usr/lib/evolution/evolution-addressbook-factory-subprocess --factory local --bus-name org.gnome.evolution.dataserver.Subprocess.Backend.AddressBookx26161x2 --own-path /org/gnome/evolution/dataserver/Subprocess/Backend/AddressBook/26161/2
brent    26300   \_ /usr/lib/x86_64-linux-gnu/hud/hud-service
brent     7616   \_ /usr/lib/gnome-terminal/gnome-terminal-server
brent     7626       \_ bash
brent     7655           \_ ps auxf
brent     1460  /usr/bin/ibus-daemon --daemonize --xim --address unix:tmpdir=/tmp/ibus
brent     1562   \_ /usr/lib/ibus/ibus-dconf
brent     1611   \_ /usr/lib/ibus/ibus-engine-simple
root      1914  /usr/lib/udisks2/udisksd --no-debug
root      2033  /usr/lib/fwupd/fwupd
root      2212  gpg-agent --homedir /var/lib/fwupd/gnupg --use-standard-socket --daemon
root      2426  /usr/lib/packagekit/packagekitd
brent    25754  /usr/bin/gnome-keyring-daemon --daemonize --login
systemd+  9131  /lib/systemd/systemd-resolved
systemd+  9146  /lib/systemd/systemd-timesyncd
root      9685  /usr/lib/snapd/snapd
root      9790  /lib/systemd/systemd-udevd
root      6773  /usr/sbin/cupsd -l
lp        6776   \_ /usr/lib/cups/notifier/dbus dbus://
lp        6819   \_ /usr/lib/cups/notifier/dbus dbus://
root      6774  /usr/sbin/cups-browsed
