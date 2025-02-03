# vcert-rds

A playbook for Venafi's [vcert](https://github.com/Venafi/vcert) that requests and installs a TLS certificate for Remote Desktop Services.

Why use this versus auto-enrollment with ADCS? One use case is the CyberArk PSMs where they are commonly behind a load balancer or part of a DNS round robin and the shared hostname needs to be listed in the subject alternative names.