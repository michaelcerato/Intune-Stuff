Sophos exclusion for Intune MDM requirements, updated at 23/02/2026
Based by official requirements:
https://learn.microsoft.com/en-us/intune/intune-service/fundamentals/intune-endpoints?tabs=north-america

You can import the list from Sophos, in the import-export menu of the firewall

<img width="1565" height="643" alt="image" src="https://github.com/user-attachments/assets/ab8c4889-1d53-4636-8266-358fb5e63584" />

You will find a Host Group and a FQDN Group, named Intune-IP & Intune-FQDN

<img width="1536" height="534" alt="image" src="https://github.com/user-attachments/assets/adfd668c-033d-4a80-9020-ac8b0373e6cb" />

Use it as a whitelist rule on the top of the firewall policies.
