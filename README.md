# note

* `sort | uniq -c | sort -nr` count ocurrence of each line and sort them
* `perl -pi -w -e 's/foo/bar/g' **/*` replace foo to bar recursively
* `ps euxf` detail process(tree) info

run a shell script on remote host without copying. [SO: how to use ssh to run shell script on a remote machine?](http://stackoverflow.com/questions/305035/how-to-use-ssh-to-run-shell-script-on-a-remote-machine)

```sh
ssh user@host 'bash -s' <<<-SCRIPT
# shell script
SCRIPT
```

# tutorials

* [how to setup a basic iptables firewall on centos6](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-basic-iptables-firewall-on-centos-6)
