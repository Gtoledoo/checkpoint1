Claro, vou adicionar essa informação ao README:

---

## 🚀 README.md

Este repositório contém a aplicação Fiap Checkpoint 01.

### Instruções de Uso

Antes de executar a aplicação, você precisa obter a imagem do Docker Hub. Para fazer isso, utilize o seguinte comando:

```bash
docker pull toledo123/fiap-checkpoint1
```

Isso irá baixar a imagem necessária para executar a aplicação em seu ambiente local.

Em seguida, para executar a aplicação a partir do Docker Hub do respectivo membro com perfil "dev", utilize o seguinte comando:

```bash
docker run -d -p 8080:8080 -e PROFILE=dev toledo123/fiap-checkpoint1
```

Para executar a aplicação a partir do Docker Hub do respectivo membro com perfil "stg", utilize o seguinte comando:

```bash
docker run -d -p 8080:8080 -e PROFILE=stg toledo123/fiap-checkpoint1
```

Para executar a aplicação a partir do Docker Hub do respectivo membro com perfil "prd", utilize o seguinte comando:

```bash
docker run -d -p 8080:8080 -e PROFILE=prd toledo123/fiap-checkpoint1
```

Certifique-se de ter o Docker instalado e em execução em sua máquina antes de executar os comandos acima.

### Acesso à Aplicação

Após a execução da aplicação, você poderá acessá-la em `http://localhost:8080/ping`.

### Autor

Este projeto foi desenvolvido por [Gabriel Oliveira Toledo, Matheus Perestrelo].

--- 

Espero que isso atenda às suas necessidades!
