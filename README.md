# MITM Guard

It detects MITM attacks and confuses the attacker by sending fake ARP packets

## Usage

1. It's quite simple to use. Just start the program with calling the "mitm-guard.py" file as in the example command below.
```
python3 mitm-guard.py
```

The program will find your ip address and scan for same MAC addresses in the ARP table. Don't worry when it detects an attack, fake arp packets will be already sent.
