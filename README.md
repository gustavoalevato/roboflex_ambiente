## Ambiente em containers dos sistemas da Roboflex

##### Faça o clone do projeto thalamus-ambiente

```
git clone https://github.com/gustavoalevato/roboflex_ambiente.git thalamus-ambiente
```

##### Baixe os projetos dos repositórios do github dentro da pasta workspace. A estrutura de pasta deverá seguir o seguinte padrão abaixo:

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
