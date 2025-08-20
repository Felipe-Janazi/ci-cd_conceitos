# Gatilho: Workflow run
- [Workflow dispatch documentação](https://docs.github.com/pt/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#workflow_run)

## O que é Workflow run
    É a um trigger que permite que a execução de um fluxo de trabalho seja triggado por meio de outro fluxo de trabalho.
    
## Exemplos
- 1_basic_on_workflow_run.yml
- 2_types_on_workflow_run.yml
- 3_branch_on_workflow_run.yml
- 4_workflows_on_workflow_run.yml

## Observações importantes
- Não é possível usar workflow_run para encadear mais de três níveis de fluxos de trabalho
- Podemos usar o filtros para especificar os branches em que o fluxo de trabalho de gatilho precisa ser executado para disparar o fluxo de trabalho:
    - branches
    - branches-ignore