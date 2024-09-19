Probando el codigo base

Requerimeintos

Cluster en kubernetes iniciado (Rancher desktop, minikube u otros)

Podemos probar el codigo con los siguientes pasos

1. Compilando el proyecto y generando la imagen con

```bash
docker build -t python-flask-app .
```

2. Desplegar el proyecto en kubernetes

```bash
kubectl apply -f deployment.yaml
```

3. Verificar el despliegue

   ```bash
   kubectl get podskubectl get svc
   ```
4.
