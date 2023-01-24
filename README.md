# JS

```bash
sudo dotnet workload install wasm-tools
dotnet publish src/MyApp --configuration Release
```

#  Run

```bash
dotnet tool restore
dotnet serve --directory src/MyApp/bin/Release/net7.0/browser-wasm/AppBundle
```