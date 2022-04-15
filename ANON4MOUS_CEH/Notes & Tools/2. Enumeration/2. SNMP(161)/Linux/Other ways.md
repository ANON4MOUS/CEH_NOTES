
## Nmap
-   nmap –sU –p 161 10.10.10.12
    
-   nmap -sU -p 161 --script=snmp-brute 10.10.10.12


## Msfconsole

-   msfconsole
    
-   use auxiliary/scanner/snmp/snmp_login
    
-   set RHOSTS and exploit
    
-   use auxiliary/scanner/snmp/snmp_enum
    
-   set RHOSTS and exploit