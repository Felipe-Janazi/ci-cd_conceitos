# Sintaxe de variáveis

- ${{  }}                   --> Sintaxe de variáveis
- ${{ github.actor }}       --> Nome de usuário: qagesmachado                   
- ${{ github.event_name }}  --> Trigger [on]: push, cron, workflow_dispatch, etc
- ${{ runner.os }}          --> Sistema operacional configurado em “runs-on”
- ${{ github.ref }}         --> Branch de referência
- ${{ github.repository }}  --> Nome do repositório
- ${{ github.workspace }}   --> Lista os arquivos do repositório
- ${{ job.status }}         --> Status do job: success, fail
