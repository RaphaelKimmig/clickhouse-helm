# ClickHouse Helm Chart  

Fully functioning replicated ClickHouse environment.  
  
It can use build-in zookeeper or external one.  
If you use just one replica zookeeper can be turned off at all by setting `zookeeper.enabled=false` and `externalZookeeper.enabled=false`.    
Default user `default` . 
## Run  

```bash
helm install --name clickhouse ./clickhouse
```
