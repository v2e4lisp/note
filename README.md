# note

* `sort | uniq -c | sort -nr` count ocurrence of each line and sort them
* `perl -pi -w -e 's/foo/bar/g' **/*` replace foo to bar recursively
* `ps euxf` detail process(tree) info
* `git log -p [filename]` show file's change history
* lsof -n -i4TCP:$PORT | grep LISTEN [Who is listening on a given TCP port on Mac OS X?]http://stackoverflow.com/questions/4421633/who-is-listening-on-a-given-tcp-port-on-mac-os-x

run a shell script on remote host without copying. [SO: how to use ssh to run shell script on a remote machine?](http://stackoverflow.com/questions/305035/how-to-use-ssh-to-run-shell-script-on-a-remote-machine)

```sh
ssh user@host 'bash -s' <<<-'SCRIPT'
# shell script
SCRIPT
```

# tutorials

* [how to setup a basic iptables firewall on centos6](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-basic-iptables-firewall-on-centos-6)
