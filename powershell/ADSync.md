# ADSync

### Force ADSync from PS
```
Import-Module ADSync
Start-ADSyncSyncCycle -PolicyType Delta
```

### Force Full ADSync
```
Import-Module ADSync
Start-ADSyncSyncCycle -PolicyType Initial
```
