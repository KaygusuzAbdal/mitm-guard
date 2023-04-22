# MITM Guard

A simple IPS(Intrusion Prevention Systems) tool to detect MITM attacks and response. You can use it in public areas that serve free wifi. The MITM Guard will confuse the attacker by sending fake packets. (HTTPS requests etc.)

## Usage

1. It's quite simple to use. Just start the program with calling the `mitm-guard.py` file as in the example command below.
```
python3 mitm-guard.py
```

The MITM Guard will find your public IP address and scan for same MAC addresses in the ARP table. Don't worry when it detects an attack, fake packets will already be sent.
