# Scanning

## Kioptrix is Our Target its ip is "192.168.169.129"

Kioptrix Information, Scanning Reports and Notes are in a Directory named Kiportix.

## Tools

- [netdiscover]
`netdiscover` is a tool which is used to find devices on your network.

- [nmap]
`nmap` is used to scan the device for open ports.

Command to scan the device for open ports:
`sudo nmap -T4 -p- -A 192.168.169.129`

- [nikto]
`nikto` is used to find out the potential vulnerabilities.

Command to scan the device for potential vulnerablities:
`nikto -h http://192.168.169.129`

- [dirbuster]

`dirbuster` is a tool which is used to find the directories on the device.

- [gobuster]

`gobuster` is a alternative tool of `dirbuster`.




