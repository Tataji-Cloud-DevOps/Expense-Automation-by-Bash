1. $ sudo set-hostname frontend --- To set the hostname
2. $ bash 001-frontend.sh --------It is for to excute the script.
3. $ id ------ To know the user if executing the script is root user or not
    "uid=1001(ec2-user) gid=1001(ec2-user) groups=1001(ec2-user)"
4. $ sudo id --------- To check the root user
    "uid=0(root) gid=0(root) groups=0(root)"
     If uid = 0 then it is a root user
     If uid not equal to 0 it is not a root account
5. $ man id ------- it is more information (man for manual)
    ID(1)                                                                                  User Commands                                                                                  ID(1)

NAME
       id - print real and effective user and group IDs

SYNOPSIS
       id [OPTION]... [USER]...

DESCRIPTION
       Print user and group information for each specified USER, or (when USER omitted) for the current user.

       -a     ignore, for compatibility with other versions

       -Z, --context
              print only the security context of the process

       -g, --group
              print only the effective group ID

       -G, --groups
              print all group IDs

       -n, --name
              print a name instead of a number, for -ugG

       -r, --real
              print the real ID instead of the effective ID, with -ugG

       -u, --user
              print only the effective user ID

       -z, --zero
              delimit entries with NUL characters, not whitespace;

              not permitted in default format

       --help display this help and exit

       --version
              output version information and exit
