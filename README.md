# Catcher
> A tool which can catch hackers trying to get through SSH. It is also know as Honeypot in the wild. This uses microservice to collect malware samples used by the attackers.


# Introduction

A low interaction SSH honeypot which can log the activities of the attacker and also collect the samples of the malware downloaded by the attackers. Docker and Redis are used to create a micro architecture for serving the request without flaws and also make the system modular. 

# Set Up
`docker-compose build`

`docker-compose up`

`ssh test@[honeypot-ip]`

`docker-compose down`
