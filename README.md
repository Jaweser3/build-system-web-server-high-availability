# Build System Web Server High Availability
![image](https://user-images.githubusercontent.com/96831921/176250154-1d79870b-24bf-4c1f-a288-9672d33112de.png)

Script Automatically Build System High Availability

- Condition: 5 Server - OS Ububnu

- Set environment variables suitable for the lesson lab:

  - ENV Server1-Server2:
  
          curl -skLO https://raw.githubusercontent.com/Jaweser3/build-system-web-server-high-availability/main/ENV-S1-S2.sh
          
  - ENV DBA1-DBA2-DBA3:
  
          curl -skLO https://raw.githubusercontent.com/Jaweser3/build-system-web-server-high-availability/main/ENV-DBA.sh
  
Install and Configuration:

- Script build Server1-Server2

```console  
 curl -skLO https://raw.githubusercontent.com/Jaweser3/build-system-web-server-high-availability/main/Script-Config%2BInstall-S1-S2.sh
 
```

- Script build DBA1-DBA2-DBA3
 
```console  
  curl -skLO https://raw.githubusercontent.com/Jaweser3/build-system-web-server-high-availability/main/Script-Config%2BInstall-DBA1-2-3.sh
```
