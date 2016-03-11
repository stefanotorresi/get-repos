# get-repos

```
usage: get-repos [-h] [-p, --pattern PATTERN] [-f, --format FORMAT]
                 [-c, --clear-cache]
                 name

List public repos of a Github user.

positional arguments:
  name                  the name of the Github user

optional arguments:
  -h, --help            show this help message and exit
  -p, --pattern PATTERN
                        a regex pattern to match repo names against
  -f, --format FORMAT   a format string to use for each line
  -c, --clear-cache     invalidates the cache
```

## Example

```
$ ./get-repos stefanotorresi -p '^thorr-'
thorr-advent
thorr-ansible-user-playbook
thorr-fib
thorr-nonce
thorr-oauth2
thorr-oauth2-cli
thorr-oauth2-doctrine
thorr-persistence
thorr-persistence-doctrine
```
