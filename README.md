# x

Pentest environment scaffolding.

For deployment instructions, refer to [SETUP](SETUP.md). Tested in Kali 2 (Sana).

```
 ~/x/
   ├── b/  - binary installations
   ├── e/  - extras
   ├── p/  - pentest tools
   └── t/  - undergoing tests
```

Tools map:

```
b/
b/eclipse                           - Eclipse IDE
b/endec                             - Encrypt / Decrypt using aes-256-cbc
b/firefox                           - Firefox (aside to Iceweasel, with -no-remote switch)
b/jdk                               - Oracle Java Development Kit
b/jre                               - Oracle Java Runtime
b/soap-ui                           - SOAP-based API testing
b/sqldeveloper                      - Oracle SQL Developer
b/ve                                - Python 2,3, NodeJS virtualenvs rapid setup and use
e/
e/windows-binaries/foolav.exe       - AV bypass
e/msf                               - msfconsole handler templates
e/webshells/webshell.war            - .war webshell
e/rtl8188eu                         - Hostapd configs (rtl8188eu and original)
p/
p/blns                              - The Big List of Naughty Strings
p/bsql-injector                     - Blind-SQL server responses retrieval / data extraction
p/burp                              - Burp pro, Burp free, addons and unofficial plugins
p/ciphr                             - Data transposition, encryption, decryption, hashing etc
p/clusterd                          - Application server attacking
p/discover                          - Pentest supporting tools and notes
p/empire                            - Powershell attack framework
p/fuzzdb                            - Fuzzing database (old)
p/gwt-toolset                       - GWT application testing support
p/hashid                            - Hash identifier
p/heartbleed                        - Heartbleed vulnerability exploitation
p/hqlmap                            - Sqlmap for HQL (Hibernate Query Language)
p/httpscreenshot                    - Screenshooting web pages
p/inyourface                        - Java Faces attack tool
p/ipport                            - Rapid ICMP/TCP/UDP scanning scripts
p/jdwp-shellifier                   - JDWP (Java Debug Wire Protocol) to RCE
p/liffy                             - LFI (Local File Inclusion) exploitation
p/net-creds                         - Sniff searches / creds from interface or .pcap file
p/nishang                           - Powershell-aided penetration testing
p/nosqlmap                          - Sqlmap for NoSQL
p/odat                              - Oracle Database Attacking Tool
p/owtf                              - Offensive Web Testing Framework + nice Kali Linux fine-tune
p/praedasploit                      - Printer attacks
p/rdp-sec-check                     - RDP security checks
p/responder                         - LLMNR/NBT-NS/MDNS poisoner, rogue HTTP/SMB/MSSQL/FTP/LDAP
p/rtl8188eu                         - rtl8188 specific hostapd + setup scripts
p/seclists                          - Fuzzing database (new)
p/smbexec                           - psexec style attacks
p/sqlmap                            - Sqlmap
p/sublistbrute                      - Subdomains enumeration and brute-forcing
p/testssl                           - Testing for SSL vulnerabilities
p/the-backdoor-factory              - TBF - backdooring MITM
p/udp-proto-scanner                 - UDP enumeration and probing
p/vpnbook                           - Free VPN
p/wifiphisher                       - Wifi attack framework
p/wifite                            - Automated wireless attack tool
p/windows-exploit-suggester         - systeminfo comparison against exploit database
p/xxei                              - XXE Injector
p/ysoserial                         - Java Deserialization Attacks
```

## License

[MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE)
