# airdrop
Airdrop files

## Gitcoin 8 

The data was indexed in Gitcoin database which is managed by an open source codebase: https://github.com/gitcoinco/web/

Script: 

```
select 
    distinct admin_address
from grants_grant
union
select 
    distinct contributor_address
from 
    grants_subscription
```

Data was verified by Gitcoin Team. 
