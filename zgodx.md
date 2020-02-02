---
layout: default
title: zGODx Module
---

## zGODx Module
![cpuraminfo](https://raw.githubusercontent.com/jkmods/jkmods.github.io/master/zgodx.png)

This module gives the zadmin complete control over what is happening on their server.

***Works on Windows AND POSIX systems.***

Module was rewritten from ZGod for zpanel6. Thanks to Russell which created zGod module!

Main features:
- See complete totals of hosting accounts, mailboxes, vhosts, packages, cronjobs and everything else no matter who’s account it is under.
- Complete stats of everything that is on a users account/s.
- Complete bandwidth/disk usage on the server and a break down of each account bandwidth, as well as be able to reset, and the percentage of total server resources they are using.
- Ability to LOCK accounts rather than delete them (locks their password, and maxes their bandwidth and diskspace making website offline), you can also lock mailboxes, delete crons, and FTP accounts.
- See user activity on the server for the day, as well as for the week, or month.
- List reseller packages as well as any clients that are on that account.
- Ability to start / stop / restart server services, such as zDaemon, ftp, apache, hmail, mysql.. as well as show the actual status of them.
- View webalizer stats for any domain on your server.
- Show a speciffic users activity on the server for the last 30 days.
- Ability to restore deleted records
- Send a daily html email report to the admin with updated stats and useful information on the server.
- Now you can specify more then one email address to send the report to



Direct download:
[https://jkmods.github.io/zgodx.zpp](https://jkmods.github.io/zgodx.zpp)

How to add my REPO:
```
zppy repo add jkmods.github.io
zppy update
```

Install module:
```
zppy install zgodx
```

Upgrade module:
```
zppy upgrade zgodx
```

Remove module:
```
zppy remove zgodx
```

Enjoy!
