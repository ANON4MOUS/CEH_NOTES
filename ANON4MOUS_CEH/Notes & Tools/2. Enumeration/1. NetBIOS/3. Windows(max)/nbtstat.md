- ### To display all the NETBIOS name tables of the Remote Windows Computer
	- nbtstat -a 10.10.10.x
- ### Display NETBIOS name cache of Windows Computer
	- nbtstat -c 10.10.10.x
- ### use the NETBIOS share on Windows Computer
	- net use


```
nbtstat [/a <remotename>] [/A <IPaddress>] [/c] [/n] [/r] [/R] [/RR] [/s] [/S] [<interval>]
```

 ------
#### [](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/nbtstat)Parameters

Parameter

#### Description

/a `<remotename>`

Displays the NetBIOS name table of a remote computer, where _remotename_ is the NetBIOS computer name of the remote computer. The NetBIOS name table is the list of NetBIOS names that corresponds to NetBIOS applications running on that computer.

/A `<IPaddress>`

Displays the NetBIOS name table of a remote computer, specified by the IP address (in dotted decimal notation) of the remote computer.

/c

Displays the contents of the NetBIOS name cache, the table of NetBIOS names and their resolved IP addresses.

/n

Displays the NetBIOS name table of the local computer. The status of **registered** indicates that the name is registered either by broadcast or with a WINS server.

/r

Displays NetBIOS name resolution statistics.

/R

Purges the contents of the NetBIOS name cache and then reloads the pre-tagged entries from the **Lmhosts** file.

/RR

Releases and then refreshes NetBIOS names for the local computer that is registered with WINS servers.

/s

Displays NetBIOS client and server sessions, attempting to convert the destination IP address to a name.

/S

Displays NetBIOS client and server sessions, listing the remote computers by destination IP address only.

`<interval>`

Displays selected statistics, pausing the number of seconds specified in _interval_ between each display. Press CTRL+C to stop displaying statistics. If this parameter is omitted, **nbtstat** prints the current configuration information only once.

/?

Displays help at the command prompt.