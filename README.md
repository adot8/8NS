# 8NS
Not inventing the wheel with this one.

8NS is a bash script used to automate the use of various DNS and website recon tools such as [Assetfinder](https://github.com/tomnomnom/assetfinder), [Domain-Security-Scanner](https://github.com/globalcyberalliance/domain-security-scanner), [dnsenum](https://www.kali.org/tools/dnsenum/), [EyeWitness](https://github.com/RedSiege/EyeWitness) and the [Shodan CLI](https://cli.shodan.io/).

This tool has been very useful on engagements, as it can be ran in the background while other manual recon tactics are performed.

## Installation
```bash
sudo apt update && sudo apt -y install assetfinder dnsenum eyewitness && pip3 install shodan
```

```bash
git clone https://github.com/globalcyberalliance/domain-security-scanner.git
cd domain-security-scanner
make
sudo cp dss /bin
```

```bash
git clone https://github.com/adot8/8NS.git && cd 8ns && chmod +x 8NS && sudo cp 8ns /bin
```

## Usage
```bash
8ns <domain> <subdomain_wordlist>

8ns adot8.com /opt/wordlists/subdomains_custom.txt
```
