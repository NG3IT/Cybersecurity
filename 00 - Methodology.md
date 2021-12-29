# The hacker methodology

This sumary is inspired by the THM room - [The Hacker Methodology](https://tryhackme.com/room/hackermethodology)

Also, see the writeups of the THM room [A faire](futur lien)

---

## Steps of process

The steps to perform a penetration test are as follows :

1. [Reconnaissance](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#reconnaissance)
2. [Enumeration/Scanning](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#enumerationscanning)
3. [Gaining access](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#exploitation)
4. [Privilege Escalation](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#reconnaissance)
5. [Covering Tracks](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#reconnaissance)
6. [Reporting](https://github.com/NG3IT/Sec/blob/main/00%20-%20Methodology.md#reconnaissance)

---

## Reconnaissance

This phase concerns the entire information gathering phase. No interaction with the target is necessary.

See as follow different examples about tools who helps for this phase :

1. General research informations -> Google, Wikipedia
2. Research about personn -> PeopleFinder
3. Informations about Domain name or IP -> who.is, sublist3r
4. Email finder -> hunter.io
5. Tech analyzer of websites -> WappAlyzer, builtwith

---

## Enumeration/Scanning

This phase will make it possible to detect and identify the attack surface of the target. Now, there is an interaction with the target.

See as follow different examples about tools who helps for this phase :

1. Scanning open ports and more -> nmap
2. Find directories on a website -> dirb
3. Find system Linux vulnerabilities -> enum4linux

---

## Gaining access

This phase concerns the exploitation of a vulnerability found previously. The tools to be used depends about vulnerability finded. One of more famous of this tools is Metasploit (for hacking with eyes closed :expressionless:).

---

## Privilege Escalation

This phase appears when the attacker have an entrypoint on the target with a specific user. Now, the objectif is to get a higher privileges user account like Administrator or root. There is some ways to get it and depend the family OS, version OS, ...

---
