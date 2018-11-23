**ln** - to create links to apps;

**cd** - to get to the home directory;


To list only directories;
```
ls -d */
```

**whois** - to get info about web site;

**nslookup** - to look up *dns* info;

To watch Task manager:
```
top
```

To get info about command location:
```
which
```

**whoami** - to get user's info;

`pushd/popd` - to put directory on a stack;

`file` - to determine file type;

**locate** - to find files by their name;

**updatedb** - might be necessary for database of the *locate* command;

**free -m** - to watch free RAM;

To get HTTP relpy (-v) for --verbose:
```
time curl -I mblog.smallroom.s-host.net
```

To route domain's trace with IP:
```
sudo traceroute -I domain.com
```

To add user/user's password and sudo rights:
```
# adduser username
# usermod -aG sudo username
# passwd username
```
