```mermaid
sequenceDiagram
participant Attacker
participant BotNet
participant WebServer
participant Firewall
Attacker ->> BotNet: Creates a botnet to shut down website for nefarious purposes
BotNet -->> Attacker: Helps attacker to flood webserver
BotNet ->> WebServer: Accesses webserver in massive numbers causing the webserver to severly slow or shut down
Webserver ->> Firewall: Relies on firewall to protect it
Firewall ->> WebServer: Protects server from botnet floods by protecting IP and using traffic analysis
```
# Steps of a DDoS Attack
1. An attacker creates a botnet, a group of devices that are infected by malware and thus controlled by the attacker, to flood a webserver, software that allows users to acess websites.
2. Once botnet is created, they are unleashed to the webserver by the attacker all at once to flood and disrupt it. This is called a DDoS (Distributed Denial-of-Service) attack.
3. Webserver can use what's called a firewall, a common defensive system that watches server traffic, to find the harmful botnets, protecting the server.
4. Firewall helps protect webserver by blocking the IP and using traffic analysis.
5. DDoS attack is stopped by firewall and webserver begins process of repairing its infrastructure.
