### Compilar imagem
```bash
docker build -t nome_imagem .
```

### Executar container
```bash
docker run --name nome_container nome_imagem
```

**OBS:** Foi gerado uma imagem e publicada no dockerhub, para acessar a imagem clique  [aqui](https://hub.docker.com/r/urameshe/codeeducation).

### Executar o container com imagem gerada no dockerhub
```bash
docker run --rm urameshe/codeeducation
```
