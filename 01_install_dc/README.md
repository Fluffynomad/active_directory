# Installing the Domain Controller

1. Use `sconfig` to:
    - Change the hostnamr
    - Change the IP address to static
    - Chnge the DNS server to own IP address 

2. Install the Active Directory Windoes Feature 

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```
