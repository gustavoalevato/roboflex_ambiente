## Ambiente em containers dos sistemas da Roboflex

##### Faça o clone do projeto thalamus-ambiente

```
git clone https://github.com/gustavoalevato/roboflex_ambiente.git thalamus-ambiente
```

##### Baixe os projetos dos repositórios do github dentro da pasta workspace. A estrutura de pasta deverá seguir o seguinte padrão abaixo:

Thalamus SSO Backend
- https://github.com/gustavoalevato/thalamus-sso.git

Thalamus Portal Frontend
- https://github.com/gustavoalevato/thalamus-portal-frontend.git

Thalamus Backend
- https://github.com/devRoboflex/thalamus-backend-laravel

Thalamus Projeto
- https://github.com/devRoboflex/thalamus-projeto-frontend-vue3

Thalamus Orçamento
- https://github.com/devRoboflex/thalamus-orcamento-frontend-vue3

Thalamus Acesso(Catraca)
- https://github.com/devRoboflex/thalamus-acesso-frontend-vue3

Thalamus Estrutura
- https://github.com/devRoboflex/thalamus-estrutura-frontend-vue3

Thalamus Monitoramento Dispositivos Móveis
- https://github.com/devRoboflex/thalamus-monitoramento-frontend-vue3

Thalamus Indicador
- https://github.com/devRoboflex/thalamus-indicador-frontend-vue3

Thalamus Acesso(Catraca) -App
- https://github.com/devRoboflex/thalamus-acesso-frontend-flutter

Thalamus App Base
- https://github.com/devRoboflex/thalamus-app-frontend-flutter


``` 
.
..
thalamus_ambiente
workspace
```

Para iniciar os serviços, acesse o diretório thalamus_ambiente pelo powershell ou terminal linux e execute o seguinte comando abaixo
```
docker compose up -d

```


Para rodar os projetos resolvendo o nome dos subdominios, adicione esta lista abaixo no arquivo hosts do seu sistema operacional

#### Linux
```
sudo nano /etc/hosts
```

#### Linux
```
c:/Windows/System32/drivers/etc/hosts
```

## Lista de nomes

```
127.0.0.1       sso.thalamus.ind.br
127.0.0.1       api.thalamus.ind.br
127.0.0.1       indicadores.thalamus.ind.br
127.0.0.1       monitoramento.thalamus.ind.br
127.0.0.1       acesso.thalamus.ind.br
127.0.0.1       estrutura.thalamus.ind.br
127.0.0.1       projetos.thalamus.ind.br
127.0.0.1       orcamento.thalamus.ind.br
127.0.0.1       phpmyadmin.thalamus.ind.br
127.0.0.1       jenkins.thalamus.ind.br
127.0.0.1       portal.thalamus.ind.br
127.0.0.1       prototipos.thalamus.ind.br
``` 