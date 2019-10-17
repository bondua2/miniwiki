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
To add SSH keys to the host (public/private):
```
ssh-keygen -t rsa
ssh-copy-id username@remotehost
```

To scan ports on host
```
nmap IP
```
<<<<<<< HEAD
**Environment variable**
```
varname=varvalue
echo $varname
```
To set a variable globally:
```
export varname
export varname=varvalue
declare -x varname
```
To display global vars:
```
export
declare -x
```
To remove a variable:
```
unset varname
```
To reset a value of the variable:
```
varname=
```
To see a type of the command:
```
type set
type env
```
**$OLDPWD** - a variable for a last working folder;

add a new path to PATH variable:
```
PATH=$PATH:new_path
```
=================================
=======
To see built-in commands in bash:

**man bash-builtins**
>>>>>>> a559140186a013d48e343dfd964dfdd6496cb7f4
