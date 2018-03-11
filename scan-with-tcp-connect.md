# Scan with TCP Connect

> This opens up a connection with the target system.
>
> * Using the **-P0 **switch here.
>
>   * Suppresses the ping that nmap sends out by and is blocked by most firewalls

.

```
nmap -sT -P0 <Target IP Address>
```

> **This is a load scan and will create a log in the Windows Security events**



