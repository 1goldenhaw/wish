# wish
Bash-script with IPv4-address like parameter. 

It's a little bit more beautiful output for util 'whois' (must be installed in system).
Also it checks for Private IP addressess. Not perfect, but readable.

1) sudo apt install whois
2) Locate it in /usr/local/bin/
3) sudo chmod +x /usr/local/bin/wish

Examples:
$ wish 9.9.9.9
🌐 IP Address: 9.9.9.9
🛡️  AS Number: AS19281
🗺️  Country: United States
🏙️  City: Berkeley
🏢 Operator: NetName:        CLEAN-97 Quad9/Quad9 (CLEAN-97)

📇 Contacts
📞 Phone: +14158313111,+14158313129 +17039298954
✉️  E-mail: abuse@quad9.net,dkara@quad9.net kabindra@pch.net,noc@quad9.net
🔗 Website: https://quad9.net/

$ wish 8.8.8.8
🌐 IP Address: 8.8.8.8
🛡️  AS Number: AS15169 Google LLC
🗺️  Country: United States
🏙️  City: Ashburn
🏢 Operator: Google LLC Google LLC (GOGL)/Google Public DNS NetName:        GOGL

📇 Contacts
📞 Phone: +16502530000
✉️  E-mail: arin-contact@google.com,network-abuse@google.com
🔗 Website: http://support.google.com/legal,https://www.google.com/contact/

$ wish 1.1.1.1
🌐 IP Address: 1.1.1.1
🛡️  AS Number: AS13335
🗺️  Country: Australia
🏙️  City: South Brisbane
🏢 Operator: APNIC and Cloudflare DNS Resolver project APNIC-LABS/APNIC Research and Development Research prefix for APNIC Labs Routed globally by AS13335/Cloudflare

📇 Contacts
📞 Phone: +61738583100,+61738583199
✉️  E-mail: helpdesk@apnic.net,resolver-abuse@cloudflare.com


(Who Is SH)