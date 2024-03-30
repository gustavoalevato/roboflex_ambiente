## Ambiente em containers dos sistemas da Roboflex

##### Baixe os projetos dos repositórios do github dentro da pasta workspace. A estrutura de pasta deverá seguir o seguinte padrão abaixo:

Backend (Todos projetos)
- https://github.com/devRoboflex/SGI20
Módulo Acesso (Aplicativo)
- https://github.com/devRoboflex/thalamus_acesso_app
Roboflex (Aplicativo)
- https://github.com/devRoboflex/thalamus_app
Acesso Catraca
- https://github.com/nvieira2/thalamus-acesso
Orçamento
- https://github.com/mariimozzer/Thalamus-orcamento
Gestão de Projetos (Jira)
- https://github.com/mariimozzer/Thalamus-jira-vue3
Estrutura (Permissões)
- https://github.com/mariimozzer/Thalamus-estrutura-vue3
Indicadores
- https://github.com/devRoboflex/Indicadores-vue
Monitoramento
- https://github.com/devRoboflex/monitoramento-vue3


``` 
.
..
roboflex_ambiente
workspace
```

Para iniciar os serviços, acesse o diretório roboflex_ambiente pelo powershell ou terminal linux e execute o seguinte comando abaixo
```
docker compose up -d

```
