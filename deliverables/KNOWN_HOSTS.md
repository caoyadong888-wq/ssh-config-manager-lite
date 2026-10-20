# ValidateKnownHosts

OpenSSH has no `ValidateKnownHosts` keyword. Leave `StrictHostKeyChecking yes`.

`accept-new` stores the first key and still fails if that key later changes. `ask` needs a person at the terminal. `no` disables the check. Do not use `no`.

Before the first login to `bastion.example.com`, compare the fingerprint with a channel you already trust, then connect. `ssh-keyscan` shows whatever the network returns. It is not that comparison.

`ProxyJump` checks the jump host and the target. Both names belong in `known_hosts`.

`IdentityFile` is a path. Do not paste a private key into the config.
