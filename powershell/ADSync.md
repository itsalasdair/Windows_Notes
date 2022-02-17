# ADSync

### Force ADSync from PS
```
Import-Module ADSync
Start-ADSyncSyncCycle -PolicyType Delta
```

### Force Full ADSync for PS
```
Import-Module ADSync
Start-ADSyncSyncCycle -PolicyType Initial
```
