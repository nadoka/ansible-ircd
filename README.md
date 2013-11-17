# ansible-ircd

ansble playbook for ircd servers

## How to use

Add host alias into `~/.ssh/config`.
For example:

```
Host nadoka-ccvps
	Hostname nadoka-ccvps.n-z.jp
	User admin01
	HostKeyAlias nadoka-ccvps
	CheckHostIP no
	UserKnownHostsFile ~/.ssh/nadoka.known_hosts
```

Run ansible:

- `ansible-playbook -i hosts site.yml`
