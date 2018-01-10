# About

This Ansible play was build to check hosts with the spectre-meltdown-checker from speed47.
https://github.com/speed47/spectre-meltdown-checker.

# Usage

Run `ansible-playbook play-check-vulnerability.yml` to check again
a set of hosts.

Using `--tags=` you can specify the following variants. The check will 
fail on the first variant that is vulnerable. 

- variant-1
- variant-2
- variant-3
- meltdown
- spectre