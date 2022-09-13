# Minecraft Server Checker
Tool to check IPs in the list.  

# How to use
Execution example
```
MinecraftServerChecker.exe -f=ip.txt -tn=3000
```
## Available command line arguments  
| argument | usage | default |
| ------------- | ------------- | ------------- |
| f | Name of file to load | ip.txt |
| tn | thread number | 1000 |
| fm | format mode | 2 |
| wfm | write format mode | 2 |
| p | check port number | 25565 |
| ms | masscan mode | false |
| msf | Name of masscan file to load | masscan.txt |

## Format mode example
1
```
=================================================
IP: 0.0.0.0
VERSION: 1.19
ONLINE: 1/20
PLAYERS: [Player]
MOTD: A Minecraft Server
=================================================
```

2
```
0.0.0.0 | A Minecraft Server | 1.19 | 1/20 | [Player]
```
