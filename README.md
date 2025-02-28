# 8NS
Not inventing the wheel with this one.

8NS is a bash script used to automate the use of various DNS and website recon tools such as [Assetfinder](https://github.com/tomnomnom/assetfinder), [Domain-Security-Scanner](https://github.com/globalcyberalliance/domain-security-scanner), [dnsenum](https://www.kali.org/tools/dnsenum/), [EyeWitness](https://github.com/RedSiege/EyeWitness) and the [Shodan CLI](https://cli.shodan.io/).

This tool has been very useful on engagements, as it can be ran in the background while other manual recon tactics are performed.

## Usage
`git clone https://github.com/adot8/8NS.git`

`cd 8NS && chmod +x 8NS`

`./8NS <domain> <subdomain_wordlist> `
