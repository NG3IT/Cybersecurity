

## Discovery of hosts alive :

### Layer 2

Arp scan (without port scan)
```bash
sudo nmap -PR -sn <target>/<cidr>
```

ICMP request scan (without port scan)
```bash
sudo nmap -PE -sn <target>/<cidr>
```

### Layer 3

Timestamp ICMP scan (without port scan)
```bash
sudo nmap -PP -sn <target>/<cidr>
```

Netmask ICMP request scan (without port scan)
```bash
sudo nmap -PM -sn <target>/<cidr>
```

Arp-scan tool (local network) 
```bash
arp-scan -I <interface> -l
```

### Layer 4

TCP SYN ping
```bash
sudo nmap -PS<port_numer> -sn <target>/<cidr>
```

TCP ACK ping 
```bash
sudo nmap -PA<port_numer> -sn <target>/<cidr>
```

UDP ping 
```bash
sudo nmap -PU<port_numer> -sn <target>/<cidr>
```

---

## Simple scan

Ping scan (disable port scan)
```bash
namp -sn <target>
```

Treat all hosts as online (skip host discovery)
```bash
nmap -Pn <target>
```
