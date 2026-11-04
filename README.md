# Material para testes de aulas de DevOps


Usando: 
```
    git clone https://github.com/CarlosWGama/aula-devops.git 
    cd aula-devops
    git checkout tag-aula
```


As tag das aulas são:
- inicio - Material cru, sem nada ainda
- testes - Material com integração de testes
- docker - Material com uso de docker
- gh-actions - Material com o uso do Github Actions


---------
### MATERIAL DE TESTE

Os testes são usando Jest, por isso é preciso também executar o seguinte comando:

```
    npm install
```

---------
### MATERIAL DE DOCKER

Para subir o projeto em Docker basta rodar o comando

```
    docker compose up
```

O projeto terá rodando:
 - http://localhost
 - http://localhost:4444


---------
### MATERIAL DO GITHUB ACTIONS

O workflow de teste e publicação está disponivel em:

[.github/workflow/pipeline.yml](https://github.com/CarlosWGama/aula-devops/blob/gh-actions/.github/workflows/pipeline.yml)

---------

*Autor:* Carlos W. Gama
Licença: MIT