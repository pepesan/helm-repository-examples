# Repositorio de Ejemplos de Charts de Helm

Binevenid@ Este es el repositorio de ejemplos de charts de Helm de Pepesan

## Empezando

Añade este repositorio de Helm

```
helm repo add examples https://pepesan.github.io/helm-repository-examples
```

Instala el ejemplo de aws-sc-ebs (requiere el csi driver de aws ebs)

```
helm install aws-sc-ebs helm-repository-examples/aws-sc-ebs
```

Instala un ejemplo de nginx con pvc.

```
helm install nginx-pvc helm-repository-examples/nginx-pvc
```
