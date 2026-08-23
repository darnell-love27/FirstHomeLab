# FirstHomeLab
Creating beginner homelab for learning networking &amp; microservices on a small scale
# Day 1
Downloaded Rufus on my main Windows PC + Ubuntu
Used a 128 GB USB drive for booting Ubuntu
Formatted the USB drive to be a bootable device
Downloaded the ISO and set up Ubuntu on Dell laptop
Configured network settings
Installations went through + set up OpenSSH
Named it ‘testserver’
On main PC, I SSH into testserver first using testserver@testserver which didnt work
Went through the configuration YAML file on testserver laptop to troubleshoot
With assistance, figured out that the issue was a overlap of set-name between MAC address and interface (wlp-s0203…)
Deleted both properties and works as long as I enter testserver@IP-Address
Set up Docker + Docker Engine
On the main pc, set up a context called homeserver on Docker Desktop to testserver Docker Engine.
## Next Day Plan:
Look into container options and what all I can run. I’m thinking of having development and experimentation be on testserver and what I like/will use will be added to the main pc. More ideas to come on bigger projects.
