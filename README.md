gitsshm:  GIT_SSH Manager.
==========================
Usage:
--------------------------
    source gitsshm [Action]

Action:
-------------------
    -h|help              - show this help.
    -u|setup             - add public keys for github to ssh-agent.
    -r|reset             - reset GIT_SSH environment variables and delete public keys for github from ssh-agent.
    -l|list              - list available user names.
    -L|listkeys          - list all keys registered in ssh-agent.
    -c|current           - print current GIT_SSH setting.
    -s|switch [username] - setup GIT_SSH environment for given username.
    [username]           - shortcut for switch.

Copyright:
--------------------
         Shingo Omura
         github : http://everpeace.github.com
         twitter: http://twitter.com/everpeace

Licence:
----------------------
MIT Licence.

