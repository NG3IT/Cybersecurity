Simple list targets to scan
```bash
nmap -sL <target> 
```

ping scan (disable port scan)
```bash
namp -sn <target>
```

treat all hosts as online (skip host discovery)
```bash
nmap -Pn <target>
```

arp scan (without port scan)
```bash
nmap -PR -sn <target>
```

