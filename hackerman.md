# Hackerman commands

## kubens
```
wget https://raw.githubusercontent.com/ahmetb/kubectx/master/kubens
```

```
chmod +x kubens
```

```
sudo mv ./kubens /usr/local/bin/kubens
```

## Kube ops view

## Kubebox
Consola de linea de comandos para kubernetes + metricas
### Desplegar metricas
Descargar cadvisor
```
git clone https://github.com/google/cadvisor.git
```

```
https://github.com/google/cadvisor/tree/master/deploy/kubernetes
```

```
curl -Lo kubebox https://github.com/astefanutti/kubebox/releases/download/v0.8.0/kubebox-linux
```
Dar permisos de ejecucion
```
chmod +x kubebox
```
Mover al PATH
```
sudo mv ./kubebox /usr/local/bin/kubebox
```

## k9s
Consola de linea de comandos para kubernetes
https://github.com/derailed/k9s

Descargar el binario
```
wget https://github.com/derailed/k9s/releases/download/v0.21.4/k9s_Linux_x86_64.tar.gz
```
Descomprimir el binario
``
tar -xvzf ./k9s_Linux_x86_64.tar.gz
```
Dar permisos de ejecucion
```
chmod +x ./k9s
```
Mover al PATH
```
sudo mv ./k9s /usr/local/bin/k9s
```

[Reference](https://www.youtube.com/watch?v=wEQJi7_4V9Q)
[Reference](https://www.youtube.com/watch?v=auVLHYSZM_A)