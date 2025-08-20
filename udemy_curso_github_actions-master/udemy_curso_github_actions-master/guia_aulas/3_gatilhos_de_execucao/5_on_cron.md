# Gatilho: Cron Job
- [Workflow dispatch documentação](https://docs.github.com/pt/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#schedule)

## O que é Cron job
    É a um trigger que permite que você agenda a execução de um fluxo de trabalho.
    
## Exemplos
- 1_on_cron.yml

## Legenda
┌───────────── minute (0 - 59)
│ ┌───────────── hour (0 - 23)
│ │ ┌───────────── day of the month (1 - 31)
│ │ │ ┌───────────── month (1 - 12 or JAN-DEC)
│ │ │ │ ┌───────────── day of the week (0 - 6 or SUN-SAT)
│ │ │ │ │
│ │ │ │ │
│ │ │ │ │
* * * * *

## Observações importantes
- Horário utilizado é UTC (horário do Brasil + 3 horas)
- Use para auxiliar na montagem do cron job: https://crontab.guru/
- Horário não será exato, depende da disponibilidade do GitHub Actions
