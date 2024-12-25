In preparation for the upcoming TestNet launch, we’ve reset the DevNet backend today to enhance system performance and stability. To ensure your node continues to operate smoothly, please follow these steps:

**1.Relogin**
```
/opt/dcdn/pipe-tool login --node-registry-url="https://rpc.pipedev.network"
```

**2.Generate a new registration token**
```
/opt/dcdn/pipe-tool generate-registration-token --node-registry-url="https://rpc.pipedev.network"
```

**3.Restart the dcdn service**
```
systemctl restart dcdnd
```

**4.Confirm your node is registered**
```
/opt/dcdn/pipe-tool list-nodes --node-registry-url="https://rpc.pipedev.network"
```
