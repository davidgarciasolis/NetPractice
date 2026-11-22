*This project has been created as part of the 42 curriculum by davgarc4.*

# NetPractice

## Description

NetPractice is a 42 project for learning the basics of TCP/IP networking. Each of the ten levels presents a simulated network with connectivity goals. You edit the available IP addresses, subnet masks and routes so that the hosts can communicate across the network.

## Instructions

### Run the simulator

You need Bash, Python 3 and a web browser. Download `net_practice.1.9.tar` from the NetPractice project page on the 42 intranet and extract it with `tar -xf net_practice.1.9.tar`.

```sh
cd net_practice
./run.sh
```

The script starts a local web server and opens the training interface in your browser. If the script fails, run this command from inside `net_practice` and open `http://localhost:49242` in your browser.

```sh
python3 -m http.server 49242 --bind 127.0.0.1
```

### Complete and export the levels

1. Open **Training**, enter your 42 intranet login and click **Start!**. Your login determines your personal configuration.
2. Read the connectivity goals, then adjust the editable fields. Click **Check again** to verify the configuration. If a goal fails, use the logs at the bottom of the page to see where the packet stopped.
3. Once the level passes, click **Get my config** to export its JSON file. Export it before clicking **Next level**.
4. Repeat for all ten levels. Submit `README.md` and the ten exported configuration files, `level1.json` through `level10.json`, at the root of the Git repository.

## Resources

- TCP/IP addressing and IPv4 packet structure. [RFC 791 — Internet Protocol](https://www.rfc-editor.org/rfc/rfc791)
- Subnet masks and CIDR prefix lengths. [RFC 1878 — Variable Length Subnet Table for IPv4](https://www.rfc-editor.org/rfc/rfc1878)
- Default gateways and host routing. [RFC 1122 — Requirements for Internet Hosts](https://www.rfc-editor.org/rfc/rfc1122)
- Routers and switches. [Cisco — What is a switch vs a router?](https://www.cisco.com/site/us/en/learn/topics/small-business/network-switch-vs-router.html)
- The seven OSI layers. [IBM — What is the OSI model?](https://www.ibm.com/think/topics/osi-model)

### AI use

Within this project, AI was used only to write this README.
