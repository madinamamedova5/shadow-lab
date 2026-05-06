Shadow-Lab
#Scenario:
A legacy server has been left running by a departing admin. It’s unpatched, misconfigured, and full of breadcrumbs. Your mission is to breach the system and capture the root flag.
#Quick Start:
#Download the file
curl -L [https://raw.githubusercontent.com/madinamamedova5/shadow-lab/main/docker-compose.yml](https://raw.githubusercontent.com/madinamamedova5/shadow-lab/main/docker-compose.yml) -o docker-compose.yml

# Start the lab
docker-compose up -d

#Discovery:
nmap -p- -sV localhost

#Objective

Gain entry.

Escalate privileges.

Read /root/flag.txt.

