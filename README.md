# Utilização dentro do Docker

Para utilização desta lib para python utilizar o seguinte passo a passo:



### Docker Compose

Adicionar a seguinte linha no arquivo docker-compose.yml
```dockerfile
volumes:
- ./satcfe/satcfe:/usr/local/lib/python3.5/dist-packages/satcfe
```

### Armazenamento

A clonagem deste repositório deve ser feita na raiz da pasta do docker-compose.