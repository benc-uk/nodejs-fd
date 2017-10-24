# Docker pre demo commands
```
docker login futuredecoded.azurecr.io -u futuredecoded -p 4oBoxpYgMQQ+s6+yu3rbcjJm9BhE7mpG
```

# Docker Commands
```
docker build . -t futuredecoded.azurecr.io/apps/nodejs-demoapp

docker push futuredecoded.azurecr.io/apps/nodejs-demoapp
```

# Create Windows Web App Commands
```
az appservice plan create -n fd-windows-plan -g Demo.FutureDecoded -l northeurope --sku S2

az webapp create --plan fd-windows-plan -g Demo.FutureDecoded --name fd-slotdemo
```