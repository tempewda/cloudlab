strip perms:
```
icacls "tempewdakey.pem" /inheritance:r
```

add new perms:
```
icacls "tempewdakey.pem" /grant:r "%username%":"(R)"
```
