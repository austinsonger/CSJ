# Scan with SYN Flag

> You can use the TCP protocol that just uses SYN flag
>
> * It never completes the three-way handshake
>   * Thus it will never be logged by Windows Security Events

```
nmap -sS -P0 <Target IP Address>
```



